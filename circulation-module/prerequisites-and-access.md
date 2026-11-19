---
description: Required rights and Administration screens for Circulation.
---

# Prerequisites and access

## Prerequisites and user rights

| Item | Purpose |
| --- | --- |
| Valid Nomadia Field Service license | Circulation does not start without a valid license. |
| Right "Allows managing system information" | Displays the **XML Files** folder in Administration. |
| Right "Allows access to the import of XML files for creating, modifying, and deleting appointments" | Gives access to **Circulation file** and **Circulation examples**. |
| Right "Allows managing the vault (credentials and access points referenced by the configuration)" | Gives access to **Vault**. |
| Right "Access to CSV import" or "Access to CSV export" | Gives access, in **CSV Files**, to **Circulation Listeners** and **Predefined Export Links**. |

<!-- REVIEW: the right names are translated from the French labels; check them against the English labels in the profile screen. -->

## Circulation Administration screens

| Screen | Navigation | Use |
| --- | --- | --- |
| **Circulation file** | `Administration > XML Files > Circulation file` | Import a new file and view the loading report. |
| **Circulation examples** | `Administration > XML Files > Circulation examples` | View the configuration examples provided with the application. |
| **Vault** | `Administration > XML Files > Vault` | Manage credentials and migrate Circulation to the vault. |
| **Circulation Listeners** | `Administration > CSV Files > Circulation Listeners` | List the HTTP URLs that Circulation listens to and test them. |
| **Predefined Export Links** | `Administration > CSV Files > Predefined Export Links` | Run predefined exports by link. |

For more information about rights management, see [Manage profiles and permissions](../administration/manage-profiles-and-permissions.md).
