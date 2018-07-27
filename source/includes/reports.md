# Reports (SOFOS)


<!--///////////////////////////////////////////////////////////////////////////////////-->

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

<!--///////////////////////////////////////////////////////////////////////////////////-->

## Get Daily Fee Collection

```ruby

```

```python

```

```shell

```

```javascript

```

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


<!--///////////////////////////////////////////////////////////////////////////////////-->

## Get Student Concession

```ruby

```

```python

```

```shell

```

```javascript

```

```json

```

This endpoint retrieves current consession for a student

### HTTP Request

`POST https://*.obto.co/o/recs/fee_concession?stream=true&`

### URL Parameters

Parameter | Mandatory | Description
--------- | ------- | -----------
name.value | true | Student ID

<!--///////////////////////////////////////////////////////////////////////////////////-->

## Get Daily Leave Report

```ruby

```

```python

```

```shell

```

```javascript

```

```json

```

This endpoint fetches all the leave requests for a given date.

### HTTP Request

`GET https://*.obto.co/o/recs/leave_request?stream=true&oquery=created_on=today`

### URL Parameters

Parameter | Description
--------- | -----------
ID | The ID of the kitten to delete


<!--///////////////////////////////////////////////////////////////////////////////////-->

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

`GET https://*.obto.co/`

### URL Parameters

Parameter | Description
--------- | -----------
ID | The ID of the kitten to delete

<!--///////////////////////////////////////////////////////////////////////////////////-->

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

This endpoint fetches daily rollbacked reciepts.

### HTTP Request

`GET https://*.obto.co/`

### URL Parameters

Parameter | Description
--------- | -----------
ID | The ID of the kitten to delete

<!--///////////////////////////////////////////////////////////////////////////////////-->

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

<!--///////////////////////////////////////////////////////////////////////////////////-->

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

`GET https://*.obto.co/attendancebyclassbymonth/:class/:start/:end`

### URL Parameters

Parameter | Description
--------- | -----------
class | Class Name
start | Start Date
end | End Date


<!--///////////////////////////////////////////////////////////////////////////////////-->

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
sequence | Student's Admission No#

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

`GET https://*.obto.co/o/recs/pltf_user?stream=true&oquery=active=true,roles=*teacher`

### URL Parameters

Parameter | Description
--------- | -----------
roles | Role that needs to be searched

<!--///////////////////////////////////////////////////////////////////////////////////-->

## Get Teacher's Attendance

```javascript

```

```python

```

```java

```

<!-- > The above command returns JSON structured like this: -->

```json

```

This endpoint fetches Teacher's Attendance.

### HTTP Request

`GET https://*.obto.co/o/recs/teacher_attendance?stream=true&oquery=created_on=today,name.value=`*Teacher's User ID*

### URL Parameters

Parameter | Description
--------- | -----------
name.value | User ID
created_on | Date


<!--///////////////////////////////////////////////////////////////////////////////////-->
## Get Student Grade Book

```javascript

```

```python

```

```java

```

<!-- > The above command returns JSON structured like this: -->

```json

```

This endpoint fetches Student grade book for a term.

### HTTP Request

`GET https://*.obto.co/o/recs/result?stream=true&oquery=session=2018-19,term=halfyear,admission_no=`*STUDENT ADMISSION NO*

### URL Parameters

Parameter | Description
--------- | -----------
session | Current Session
term | halfyear,finalyear
admission_no | Student's Admission No#
