# Plarform Endpoints

## Authentication

> To obtain an access token, use this code:

```javascript

```

> Make sure to replace `Username & Password` with your login credentials.

SOFOS uses API keys to allow access to the API. You can register a new SOFOS API key at our [developer portal](https://www.obto.co/site/ob/documentation).

SOFOS expects a security tokem to be included in all API requests to the server in a header that looks like the following:

`Authorization: Bearer <GENERATED TOKEN>`

This endpoint retrieves all kittens.

### HTTP Request

`POST http://*.obto.co/auth`

### Query Parameters

Parameter | Default | Description
--------- | ------- | -----------
user_name | NA    | Your user name which is used to login
password  | NA    | Your password which is used to login

<aside class="notice">
You must replace <code>GENERATED TOKEN</code> with your personal API key.
</aside>

## Important

Every collection in SOFOS is accessible via a HTTP API.

Example :

https://*.obto.co/o/recs/<collection_name>?stream=true&project=<comma seperate list of fields to show>&oquery=<db query>


```python

```

```javascript

```

<aside class="success">
Remember — always use your AUTH TOKEN to access API's
</aside>

## Fetch API

```python

```

```javascript

```

```json

```

This endpoint retrieves a specific kitten.

<aside class="warning">Inside HTML code blocks like this one, you can't use Markdown, so use <code>&lt;code&gt;</code> blocks to denote code.</aside>

### HTTP Request

`GET http://example.com/kittens/<ID>`

### URL Parameters

Parameter | Description
--------- | -----------
ID | The ID of the kitten to retrieve

## Post API

```python

```

```shell

```

```javascript

```

This endpoint deletes a specific kitten.

### HTTP Request

`DELETE http://example.com/kittens/<ID>`

### URL Parameters

Parameter | Description
--------- | -----------
ID | The ID of the kitten to delete

