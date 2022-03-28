# Books: List

Retrives a list of [**book**](books.overview.md).

## Request
```url
GET ../v1/b?q={search terms}
```
## Parameters
| Parameter name | Value | Description |
| ---      | ---      | ---      |
| **Required Params**     |
| q   | string  | Full-text search query string.  |
| **Optional Params**     |
| projection   | string  | Restrict information returned to a set of selected fields. Acceptable values are: "**full**" - Includes all book data. "**lite**" - Includes a subset of fields in bookInfo and userInfo. |
| orderBy   | string  | Sort search results.  |

## Request Body
Do not supply a request body with this method.

## Response
If successful, this method returns:

```json
{
  "items": [
    book Resource
  ],
  "totalItems": (value)
}

```