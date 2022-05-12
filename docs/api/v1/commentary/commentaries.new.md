# Commentaries: New

Create a new [**commentary**](commentaries.overview.md).

## Request
```url
POST ../v1/c
```

## Parameters
| Parameter name | Value | Description |
| ---      | ---      | ---      |
| **Required Params**     |
| commentaryId   | string    | Commentary Id to be retrieved   |
| usedId   		 | integer   | Commentary Id to be retrieved   |
| discutionId    | integer   | Discution Id to be retrieved    |
| commentary     | string    | Commentary to be retrieved      |
| registerDate   | dateTime  | Register Date to be retrieved   |
| deactiveDate   | dateTime  | Deactive Date to be retrieved   |


| **Optional Params**    |
| projection   | string  | Restrict information returned to a set of selected fields. Acceptable values are: "**full**" - Includes all commentaries data. |