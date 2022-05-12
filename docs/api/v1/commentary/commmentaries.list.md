# Commentaries: List

Retrives a list of [**commentary**](commentaries.overview.md).

## Request
```url
GET ../v1/c?q={search terms}
```
## Parameters
| Parameter name | Value | Description |
| ---      | ---      | ---      |
| **Required Params**     |
| q   | string  | Full-text search query string.  |
| **Optional Params**     |
| projection   | string  | Restrict information returned to a set of selected fields. Acceptable values are: "**full**" - Includes all commentaries data.  |
| orderBy   | string  | Sort search results.  |

## Request Body
Do not supply a request body with this method.

## Response
If successful, this method returns:

```json
	{
		"_id":string,
		"usedId":integer,
		"discutionId":integer,
		"commentary":integer,
		"registerDate":dateTime,
		"deactiveDate":dateTime
	}
```