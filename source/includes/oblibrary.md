# Platform Library

## Print

```javascript
ob.print(<log>)
```

This code is used to print logs.


## Request (HTTP: GET,POST,PUT,DELETE)

```javascript
ob.request()
```

This code is used to prepare requests to external API/Endpoints


## Fetch All Sub-domains

```javascript
ob.alldomains(<domain>)
```

This code is used to get all domains on the instance


## Check For Top Domain

```javascript
ob.isTop(<domain_name>)
```

This code is used to check the .


## Encryption

```javascript
ob.utils.encrypt(<text>)
```


This code is used to encrypt text.


## Decryption

```javascript
ob.utils.encrypt(<text>)
```


This code is used to decrypt text.


## Publish Via Emma

```javascript
ob.emma.publish(<message>)
```


This code is used publish message to a topic.

## Log message

```javascript
ob.log(<message>)
```


This code is used to log text.

## Get Property

```javascript
ob.getProperty(<property_name>)
```


This code is used to get property.

## Fetch Global Properties

```javascript
ob.getGloablProps()
```


This code is used to fetch all global properties.

## Send Email

```javascript
ob.sendMailv2(<Email object>)
```

This code is used to send email.

## Send SMS

```javascript
ob.sendSMS(<SMS Object>)
```

This code is used to send SMS.

## Run Aggregation

```javascript
ob.agg(<message>)
```

This code is used to run DB Aggregation.

## Run User Script

```javascript
ob.runScript(<user_script>)
```

This code is used to run user script.

## Check If Edu Collection

```javascript
ob.isEdu(<collection_name>)
```

This code is used to check if the collection belong to EDU domain.

## Sign Token

```javascript
ob.sign(<message>)
```

This code is used to sign and return user token.

## Database API

Database API is accessible via the global "ob" object as "ob.db".

### getCount = function (collection, query, options, _callback)

###findDistinct = function (collection, key, query, options, _callback)
###findAndModify = function (collection, query, sort, replacement, options, _callback)
###findStream = function (tableName, query, options, _eod, _com)
###agg = function (collection, agg, _eod, _com)
###create = function (tableName, _data, options, _callback)
###createMultiple = function (tableName, _data, options, _callback)
###update = function (tableName, query, options, options2, options3, _callback)
###updateMany = function (collection, query, options, options2, options3, _callback)
###listCollections = function (filter, _callback)
###readFile = function (fileId, res, opts)

