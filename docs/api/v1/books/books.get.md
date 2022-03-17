# Books: Get

Retrives a [**book**](books.overview.md) based on id.

## Request
```url
GET ../v1/b/bookId
```
## Parameters
| Parameter name | Value | Description |
| ---      | ---      | ---      |
| **Required Params**     |
| bookId   | string  | Book Id to be retrieved   |
| **Optional Params**     |
| projection   | string  | Restrict information returned to a set of selected fields. Acceptable values are: "**full**" - Includes all book data.\ "**lite**" - Includes a subset of fields in bookInfo and userInfo. |

## Request Body
Do not supply a request body with this method.

## Response
If successful, this method returns a [**book**](books.overview.md) resource in the response body.