# JSON-Api-Guide
A guideline to help developers build a robust yet simple and scalable API. This is just to help other developers understand some concepts of API response as understood by me.

## HTTP Verbs
Verb   |  Context
------ |  ----------
Get    |  When you need to retrieve data
Post   |  When you want to create a new record
Put    |  When you want to update an existing record
Delete |  When you want to remove or delete a record

## Status Codes
Code | Definition | Context
---- | ----------- |-------------------------
200 | Ok
201 | Created
304 | Not Modified
400 | 401 UnAuthorized
403 | Forbidden 
404 | Not Found
405 | Method Not Allowed
500 | Internal Server Error
503 | Service Unavailable
