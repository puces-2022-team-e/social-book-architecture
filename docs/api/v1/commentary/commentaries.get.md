# Commentaries: Get

Retrives a [**commentary**](commentaries.overview.md) based on id.

## Request
```url
GET ../v1/c/commentaryId
```
## Parameters
| Parameter name | Value | Description |
| ---      | ---      | ---      |
| **Required Params**     |
| commentaryId   | string  | Commentary Id to be retrieved   |
| **Optional Params**     |
| projection   | string  | Restrict information returned to a set of selected fields. Acceptable values are: "**full**" - Includes all commentaries data. |

## Request Body
Do not supply a request body with this method.

## Response
If successful, this method returns a [**commentary**](commentary.overview.md) resource in the response body.