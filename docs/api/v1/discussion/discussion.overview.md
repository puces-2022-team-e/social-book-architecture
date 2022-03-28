## SocialBooks Api reference Discussion

This doc explain all the api's used in the SocialBooks project

## Methods

The following methods are used by the frontEnd Application and all must require a authentication:

[**list**](discussion.list.md)

[**get**](discussion.get.md)

[**newDiscussion**](discussion.new.md)

[**addComment**](discussion.comment.md)

[**editComment**](discussion.comment.md)

Discussion Representation

```json
	{
		"_id":string,
		"bookId":string,
		"userId":string,
		"created":datetime,
		"updated":datetime,
		"deleted":datetime,
		"comments": [
			{
				"id":string,
				"order":integer,
				"userId":string,
				"created":datetime,
				"updated":datetime,
				"deleted":datetime,
				"text":string,
			}
		]
		}

	}
```

| Propertie name   | Value    | Description                            |
| ---------------- | -------- | -------------------------------------- |
| \_id             | string   | Unique identifier for a discussion     |
| bookId           | string   | Book where the discussion belongs      |
| userId           | string   | User who initiated the discussion      |
| created          | string   | Discussion create date                 |
| updated          | string   | Discussion update date                 |
| deleted          | string   | Discussion delete date                 |
| comments[]       | list     | List of Comments under this discussion |
| comments.id      | string   | Comment id                             |
| comments.order   | integer  | Display position of the comment        |
| comments.userId  | string   | User who make the comment              |
| comments.created | datetime | Comment creation date                  |
| comments.updated | datetime | Comment update date                    |
| comments.deleted | datetime | Comment delete date                    |
| comments.text    | string   | Comment content                        |
