# Reports (SOFOS)

## Get Fee Defaulters

```ruby

```

```python

```

```shell

```

```javascript

```

> The above command returns JSON structured like this:

```json

```

This endpoint retrieves all fee defaulters for a given range.

### HTTP Request

`GET https://*.obto.co/getfeedefaultersv2.bto`

### Query Parameters

Parameter | Mandatory | Description
--------- | ------- | -----------
start_month | true | Start month of the range.
end_month | true | End month of the range

### HTTP Response


## Get Daily Fee Collection

```ruby

```

```python

```

```shell

```

```javascript

```

> The above command returns JSON structured like this:

```json

```

This endpoint retrieves daily fee collection for a given date range.

### HTTP Request

`POST https://*.obto.co/getdailyfeecollectionheadwise.bto`

### URL Parameters

Parameter | Mandatory | Description
--------- | ------- | -----------
from | true | Start date.
to | true | End date
payment_type | true | Payment type (cash, cheque, card, neft, all)

## Get Daily Leave Report

```ruby

```

```python

```

```shell

```

```javascript

```

> The above command returns JSON structured like this:

```json

```

This endpoint deletes a specific kitten.

### HTTP Request

`DELETE https://*.obto.co/`

### URL Parameters

Parameter | Description
--------- | -----------
ID | The ID of the kitten to delete


## Get Daily Unique SMS Sent

```ruby

```

```python

```

```shell

```

```javascript

```

> The above command returns JSON structured like this:

```json

```

This endpoint deletes a specific kitten.

### HTTP Request

`DELETE https://*.obto.co/`

### URL Parameters

Parameter | Description
--------- | -----------
ID | The ID of the kitten to delete

## Get Daily Rollbacks

```ruby

```

```python

```

```shell

```

```javascript

```

> The above command returns JSON structured like this:

```json

```

This endpoint deletes a specific kitten.

### HTTP Request

`DELETE https://*.obto.co/`

### URL Parameters

Parameter | Description
--------- | -----------
ID | The ID of the kitten to delete


## Get Class Details

```ruby

```

```python

```

```shell

```

```javascript

```

> The above command returns JSON structured like this:

```json

```

This endpoint deletes a specific kitten.

### HTTP Request

`GET https://*.obto.co/classbycategory.bto`

### URL Parameters

Parameter | Description
--------- | -----------
None | Blank

<>///////////////////////////////////////////
## Get Monthly Class Attendance

```javascript

```

```python

```

```java

```

> The above command returns JSON structured like this:

```json

```

This endpoint deletes a specific kitten.

### HTTP Request

`DELETE https://*.obto.co/attendancebyclassbymonth/:class/:start/:end`

### URL Parameters

Parameter | Description
--------- | -----------
class | Class Name
start | Start Date
end | End Date


<///////////////////////////////////////////////////////////////////////////////////>
## Get Student Attendance

```javascript

```

```python

```

```java

```

> The above command returns JSON structured like this:

```json

```

This endpoint deletes a specific kitten.

### HTTP Request

`GET https://*.obto.co/o/recs/attendance?stream=true&oquery=created=today`

### URL Parameters

Parameter | Description
--------- | -----------
class | Class Name
start | Start Date
end | End Date

<!--///////////////////////////////////////////////////////////////////////////////////-->
## Get Student Information

```javascript

```

```python

```

```java

```

> The above command returns JSON structured like this:

```json

```

This endpoint deletes a specific kitten.

### HTTP Request

`GET https://*.obto.co/o/recs/registration?stream=true&oquery=sequence=`

### URL Parameters

Parameter | Description
--------- | -----------
class | Class Name
start | Start Date
end | End Date


<!--///////////////////////////////////////////////////////////////////////////////////-->
## Get Teacher Information

```javascript

```

```python

```

```java

```

> The above command returns JSON structured like this:

```json

```

This endpoint deletes a specific kitten.

### HTTP Request

`GET https://*.obto.co/o/recs/pltf_user?stream=true&oquery=role=*teacher`

### URL Parameters

Parameter | Description
--------- | -----------
class | Class Name
start | Start Date
end | End Date

<!--///////////////////////////////////////////////////////////////////////////////////-->
## Get Teacher's Attendance

```javascript

```

```python

```

```java

```

> The above command returns JSON structured like this:

```json

```

This endpoint deletes a specific kitten.

### HTTP Request

`GET https://*.obto.co/o/recs/teacher_attendance?stream=true&oquery=sequence=`*STUDENT ADMISSION NO*

### URL Parameters

Parameter | Description
--------- | -----------
class | Class Name
start | Start Date
end | End Date


<!--///////////////////////////////////////////////////////////////////////////////////-->
## Get Student Grade Book

```javascript

```

```python

```

```java

```

> The above command returns JSON structured like this:

```json

```

This endpoint deletes a specific kitten.

### HTTP Request

`GET https://*.obto.co/o/recs/result?stream=true&oquery=admission_no=`*STUDENT ADMISSION NO*

### URL Parameters

Parameter | Description
--------- | -----------
class | Class Name
start | Start Date
end | End Date
