---
title: OBTO API Reference

language_tabs: # must be one of https://git.io/vQNgJ
  - javascript: NodeJs
  - python: Python
  - java: Java

toc_footers:
  - <a href='https://sofos.obto.co'>Sign Up for Developer Account</a>
  - <a href='https://sofos.obto.co'>Privacy Policy</a>
  - <a href='https://sofos.obto.co'>Terms Of Use</a>
  - <a href='https://sofos.obto.co'>Security Policy</a>

includes:
  - oblibrary
  - system_endpoints
  - reports
  - errors

search: true
---

# Introduction

Welcome to the OBTO API! You can use our API to access OBTO API endpoints, which can get information on various reports, collections, and routes on the platform.

We have language bindings in NodeJs, C#, and Python! You can view code examples in the dark area to the right, and you can switch the programming language of the examples with the tabs in the top right.

# Authentication

> To obtain an access token, use this code:

```javascript

```

> Make sure to replace `Username & Password` with your login credentials.

SOFOS uses API keys to allow access to the API. You can register a new SOFOS API key at our [developer portal](http://sofos.obto.co/developers).

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

