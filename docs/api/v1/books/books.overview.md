# SocialBooks Api reference Books

This doc explain all the api's used in the SocialBooks project

## Methods

The following methods are used by the frontEnd Application and all must require a authentication:

[**list**](books.list.md)

[**get**](books.get.md)

[**new**](books.new.md)

Book Resource representation

```json
	{
		"_id":string,
		"short":string,
		"bookInfo":{
			"title":string,
			"subtile":string,
			"authors":[
				string
			],
			"publisher":string,
			"publishedDate":string,
			"pageCount":integer,
			"mainCategory":string,
			"categories":[
				string
			],
			"imageLinks": {
				"thumbnail":string,
				"mainImage":string,
			}
		},
		"selfLink":string,
		"averageRating":double,
		"ratingCount":integer,
		"userInfo":{
			"userReview":string,
			"userRate":double,
			"isPurchased":boolean
		}

	}
```

| Propertie name                | Value   | Description                                  |
| ----------------------------- | ------- | -------------------------------------------- |
| \_id                          | string  | Unique identifier for a object               |
| short                         | string  | Unique short identifier for a book           |
| bookInfo                      | object  | General book Information                     |
| bookInfo.tile                 | string  | Book title                                   |
| bookInfo.subtile              | string  | Book title                                   |
| bookInfo.authors[]            | list    | Book title                                   |
| bookInfo.publisher            | string  | Book title                                   |
| bookInfo.publishedDate        | string  | Book title                                   |
| bookInfo.pageCount            | string  | Book title                                   |
| bookInfo.mainCategory         | string  | Book title                                   |
| bookInfo.categories[]         | list    | Book title                                   |
| bookInfo.imageLinks           | object  | Book title                                   |
| bookInfo.imageLinks.thumbnail | string  | Book title                                   |
| bookInfo.imageLinks.mainImage | string  | Book title                                   |
| selfLink                      | string  | URL to this book                             |
| averageRating                 | double  | Review rating for this book (1~5)            |
| ratingCount                   | integer | Review count for this book                   |
| userInfo                      | object  | Object with user specific information        |
| userInfo.userReview           | string  | User review for this book                    |
| userInfo.userRate             | double  | User rating for this book (1~5)              |
| userInfo.isPurchased          | boolean | If the user have already purchased this book |
