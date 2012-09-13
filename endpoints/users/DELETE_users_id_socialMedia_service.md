# DELETE /users/#{id}/socialMedia/{service}    
***
`/users/#{id}/socialMedia/{service}`

### Description
***
Only available for the authenticated user, this call disconnects a service.

### Parameters
***

|header| description| type |required? |default|
|:---------|:--------------|:----------:|:------------:|:------------:|
|**id**|the user id to retrieve information from|integer|x||
|**service**|the service name|string|x||

### Response
***


200 and confirmation message


[Errors](https://github.com/eyeem/API/blob/master/resources/errors.md)

### Examples
***

`https://www.eyeem.com/api/v2/users/me/socialMedia/facebook`


