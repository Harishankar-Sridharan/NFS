---
description: Store the credentials and access points used by Circulation in encrypted form, and migrate an existing Circulation configuration to the vault.
---

# Secure credentials with the vault

The vault stores, in encrypted form, the credentials and access points used by Circulation: passwords, accounts, keys, tokens, connection strings, remote server URLs, and more. The Circulation file only references them. It no longer contains any secret in clear text and can be copied from one environment to another without exposing production access.

## Before you start

The server operator configures the vault in the server parameters, through an environment variable, or through a system property.

| Server parameter | Role | Default value |
| --- | --- | --- |
| `nfs.environment` | Name of the server environment (for example PROD, TEST). The vault refuses to open if it was created for another environment. | (empty) |
| Master key: environment variable `CREDENTIAL_VAULT_MASTER_KEY` (recommended) or `credential.vault.master-key` | Encryption key: 32 bytes encoded in base64. Without a key, the vault is closed. | none |
| `credential.vault.backend` | Storage: `database` (application database, shared by all instances) or `file` (JSON file on the server). | `database` |
| `credential.vault.path` | File storage only: location of the vault file. | in the server parameters directory |
| `credential.vault.read-only` | File storage only: `true` on instances that read a vault written by another instance. | `false` |
| `credential.vault.strict` | Strict mode: refuses credentials and access points written in clear text in Circulation (see Migrate an existing Circulation configuration to the vault below). | `false` |

{% hint style="warning" %}
Keep a backup of the master key separately from the vault: a lost key cannot be recovered. Never place the key in the parameter file delivered with the application: it is refused there.
{% endhint %}

## Access the vault

**Navigation:** `Administration > XML Files > Vault`

The screen displays:

* the **Vault status**: **Storage**, **Environment**, **File**, and the **Open** or **Closed** state;
* the list of **Credentials**: **Domain**, **Identifier**, **Properties**, **Updated**.

<!-- REVIEW: screen labels (Vault status, Storage, Environment, File, Open, Closed, Credentials, Domain, Identifier, Properties, Updated) are translated from the French UI; check them against the English UI. -->

## Reference the vault in Circulation

In the Circulation file, a sensitive value is replaced by a reference of the form:

<!-- REVIEW: the French page announces a reference of this form but the example is missing from the source; the guide elsewhere uses the `${vault:…}` form. -->

* The credentials used by Circulation are stored in the `circulation` domain of the vault.
* By convention, the identifier is the `id` of the object that uses the value (connection, medium, and so on). The property is the name of the tag (`password`, `user`, `location`, and so on).
* A reference can be the whole value or only a part of it. In a URL, a reference placed in the user / password part is encoded automatically: the `@`, `:`, or `/` characters of the password do not break the URL.
* References are resolved when Circulation loads. A reference that cannot be found prevents Circulation from starting.

Example: an SFTP medium whose account and password are in the vault (identifier `sftp-client`, properties `user` and `password`).

<!-- REVIEW: the XML example is missing from the French source. -->

## Create or modify a credential

1. Open `Administration > XML Files > Vault`.
2. Select **New credential**, or open an existing credential.
3. Enter the **Domain** (`circulation`) and the **Identifier** (without a slash).
4. For each **Property**, enter its name and its **New value**. Use **Add a property** to add one, and select **Delete** to remove one.
5. Save.

**Result:** the message "Credential … saved: added …, replaced …, deleted …" appears. Values are never displayed again; leaving a value empty keeps the current value.

Circulation reads the vault values when it starts, so a change to the vault takes effect only after the next server restart. Circulation is not reloaded automatically.

## Migrate an existing Circulation configuration to the vault

The **Circulation migration** function automatically moves the credentials and access points written in clear text in the server's Circulation file into the vault, and replaces them with references.

1. Open `Administration > XML Files > Vault`, **Circulation migration** section.
2. Select **Analyze Circulation**. The screen lists the values to move (**Circulation element**, **Reference written instead**) or the blocking issues to fix.
3. Fix any blocking issues in the file (for example: an element without an enclosing `id`, or an identifier that contains a slash, a brace, or a space).
4. Select **Migrate Circulation** and confirm.
5. Restart the server, then check the Circulation loading report.
6. Once Circulation is verified, request activation of strict mode (`credential.vault.strict` = `true`).

**Result:** the message "… value(s) moved to the vault. Copy of Circulation before migration: …" appears. A timestamped copy of the original file is kept.

## Points to note

* Email recipients (`to`, `cc`, `bcc`, `from`, `dest`) are not considered sensitive: they stay in the file.
* A remote URL is moved as a whole (account, password, server, and path).
* Strict mode also refuses: passwords, accounts, keys, tokens, connection strings, URLs and server names, HTTP headers or parameters that contain a credential, remote locations, and network shares.
* Restoring a production database on a test server makes the vault refuse to open (`database` storage). Export the test vault before the restore (**Export** button) and import it again afterward (**Import** button).
* If the vault can no longer be opened and no export exists, **Reset the vault** permanently deletes all credentials. You are asked for the environment name to confirm.
