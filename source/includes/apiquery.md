# API Query

Querying DB via HTTP Endpoints is really easy and follows a simple key value pair standard.

<aside class="notice">
You must know the field names of the collection to query before building a query
</aside>
<aside class="warning">API Query Builder is only applicable to Platform Endpoints</aside>

Example:

Consider a collection name **TASK**

It has following fields :

Fields | Type | Description
--------- | ------- | -----------
name | text    |
amount  | number    |
created_on  | datetime    |
manager  | reference    |

## Text Queries

### Query on single field

`oquery=name=Dave Smith`

### Query on multiple fields

`oquery=name=Dave Smith,amount=0`

### Starts With Query

`oquery=name==Dave Smith`

<aside class="notice">
Notice the double equal after the name
</aside>

### Does Not Starts with Query

`oquery=name=!=Dave`

### Contains Query

`oquery=name=*Dave`

### Does Not Contain Query

`oquery=name=!*Dave`

## Number Queries

### Equals Than

`oquery=amount===0`

### Greater Than

`oquery=amount=>0`

### Less Than

`oquery=amount=<0`

## Date Queries

### Today

`oquery=created_on=today`

### Yesterday

`oquery=created_on=yesterday`

### Day Before Yesterday

`oquery=created_on=daybeforeyesterday`

### Custom

`oquery=created_on=#in2018-07`

`oquery=created_on=on2018-07-15`
