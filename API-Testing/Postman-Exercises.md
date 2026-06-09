# Postman Exercises

## GET Requests

GET /posts

Validation:

* Status code = 200
* Response body not empty

GET /users

Validation:

* Status code = 200
* User list returned

## POST Requests

POST /posts

Payload:

{
"title": "QA Test",
"body": "API Validation",
"userId": 1
}

Validation:

* Status code = 201

## PUT Requests

PUT /posts/1

Validation:

* Status code = 200
* Updated data returned

## DELETE Requests

DELETE /posts/1

Validation:

* Status code = 200

