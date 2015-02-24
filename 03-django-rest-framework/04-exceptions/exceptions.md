## Exceptions, Permissions

### Preparation
[Exceptions](http://www.django-rest-framework.org/api-guide/exceptions/)
[HTTP Status Codes](http://httpstatus.es/)
[Throttling](http://www.django-rest-framework.org/api-guide/throttling/)
[Permissions](http://www.django-rest-framework.org/api-guide/permissions/)

### Exercise
- Set the permissions on the checkout view set to only allow creating a checkout if the request's
    user matches
- Return the HTTP status code 418 for a checkout POST request that contains more than the member's
    limit allows