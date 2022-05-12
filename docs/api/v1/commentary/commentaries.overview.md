# SocialBooks Api reference Commentaries

This doc explain all the api's used in the SocialBooks project

## Methods

The following methods are used by the frontEnd Application and all must require a authentication:

[**list**](commentaries.list.md)

[**get**](commentaries.get.md)

[**new**](commentaries.new.md)

Commentary Resource representation

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

| Propertie name                | Value   | Description                                  |
| ----------------------------- | ------- | -------------------------------------------- |
| \_id                          | string  | Unique identifier for a object               |
| usedId                        | integer | User Id identifier for a commentary   		 |
| discussionId                  | integer | Discussion Id for a commentary               |
| commentary                    | string  | Commentary     								 |
| registerDate                  | dateTime| Register datetime for a commentary     		 |
| deactiveDate                  | dateTime| Deactive dateTime for a commentary     		 |