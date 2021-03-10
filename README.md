# REST

REST means representational state transfer.

~ Separation of Client and Server.

`Statelessness:` Systems that follow the REST paradigm are stateless, meaning that the server does not need to know anything about what state the client is in and vice versa.

# API

Applaciation Programming Interface. API allows two systems to communicate with one another.

# key points

* resource
* collections
* endpoint
* response
* http status

# HTTP methods

* get - (retrieve data)
* post -  (submit post)
* put - (replace all data)
* patch - (partially update data)
* delete - (delete data)

~ resource
* https://developer.mozilla.org/en-US/docs/Web/HTTP/Methods

# Endpoint

endpoint will be noun and plural form . endpoint will not verb.

segment will be dash as /holiday-schedules
`{baseUrl}/v1/employees/holiday-schedules`

# Header

HTTP headers let the client and the server pass additional information with an HTTP request or response.

```js
Authorization: 'Bearer Token'
Content-Type: 'application/json'
Public-Key: ''
Secret-Key: ''
```

~ resources
* https://developer.mozilla.org/en-US/docs/Web/HTTP/Headers

# Status code

## Success

* 200 (ok) - retrieve data
* 201 (created) - insert data
* 204 (no content) - delete data

## Cilent error

* 400 (bad request)
* 401 (unauthorize)
* 403 (forbidden)
* 404 (not found)
* 405 (method not found)
* 408 (request time out)
* 414 (request get uri so long)
* 429 (so many request)

## server error

* 500 (internal server error)
* 503 (service not available)

* https://httpstatuses.com/
