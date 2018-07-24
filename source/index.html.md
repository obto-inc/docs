---
title: OBTO API Reference

language_tabs: # must be one of https://git.io/vQNgJ
  - javascript: NodeJs
  - python: Python
  - java: Java

toc_footers:
  - <a href='https://sofos.obto.co'>Sign Up for a Developer Key</a>
  - <a href='https://github.com/lord/slate'>Documentation Powered by Slate</a>

includes:
  - reports
  - errors
  - oblibrary
  - system_endpoints

search: true
---

# Introduction

Welcome to the OBTO API! You can use our API to access OBTO API endpoints, which can get information on various reports, collections, and routes on the platform.

We have language bindings in NodeJs, C#, and Python! You can view code examples in the dark area to the right, and you can switch the programming language of the examples with the tabs in the top right.

# Authentication

> To obtain an access token, use this code:

```javascript
require 'kittn'

api = Kittn::APIClient.authorize!('meowmeowmeow');
const kittn = require('kittn');

let api = kittn.authorize('meowmeowmeow');

```

> Make sure to replace `Username & Password` with your login credentials.

SOFOS uses API keys to allow access to the API. You can register a new SOFOS API key at our [developer portal](http://sofos.obto.co/developers).

SOFOS expects for the API key to be included in all API requests to the server in a header that looks like the following:

`Authorization: Bearer GENERATED TOKEN`

<aside class="notice">
You must replace <code>GENERATED TOKEN</code> with your personal API key.
</aside>

