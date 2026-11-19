---
description: Web service authentication modes and security best practices.
---

# Authentication and security

## Exchange web services (SOAP and REST)

The web services authenticate the caller in the application. Three modes are accepted:

| Mode | Principle | Transmission |
| --- | --- | --- |
| Call information (`CommonInfo`) | API protection key, user ID, and user password. On success, Nomadia Field Service creates a session and returns its identifier. | `CommonInfo` block in the request body, or `commonInfo` HTTP header (base64-encoded JSON). You can also pass the key in the `KEY` header. |
| Session | Reuse of the session identifier returned by a first call. | `SessionId` field of the request or `sessionId` HTTP header. |
| Bearer token | OAuth2 / OpenID Connect token issued by an external identity provider, or token issued by Nomadia Field Service itself. | `Authorization: Bearer <token>` header. |

### CommonInfo block

| Element | Required | Description |
| --- | --- | --- |
| `Version` | Yes | Format version; fixed value 1. |
| `Key` | Yes | API protection key, provided by Nomadia for the instance. The check is disabled if no key is configured on the server. |
| `Language` | No | Language of the messages; default `en`. |
| `UserLogin` | Yes | ID of the Nomadia Field Service user on whose behalf the call is made. |
| `UserPassword` | No (schema) | User password. The server can require it (parameter `webservice.isUserPasswordRequired`, enabled by default). |

The inactivity duration of a session is set on the server (`sessionTimeOutInSecond`, 3,600 seconds by default). An expired session returns the error `SESSION_NOT_FOUND` (code 10). You must then authenticate again.

## Security best practices

* Create a dedicated user account for each integration. Do not share a named personal account.
* Send secrets (key, password, token) only over HTTPS, and store them in a vault on the customer side. For Circulation, use the Nomadia Field Service vault (`${vault:…}` references) described in Securing credentials with the vault<!-- TODO-LINK: module-circulation/coffre-fort -->.
* Reuse the session or the token instead of sending the user ID and password with every call.
* Set the `EXTERN_APP` HTTP header to the name of your application. It is recorded in the API connection log and makes diagnosis easier.
