[![Build Status](https://travis-ci.org/cloudfoundry/admin-vmc-plugin.png)](https://travis-ci.org/cloudfoundry/admin-vmc-plugin)

## Admin
### Info
This plugin allows you to make manual HTTP requests to the Cloud Foundry REST API.

### Installation
```
gem install admin-vmc-plugin
```

### Usage

```
curl MODE PATH HEADERS...                       Execute a raw request
service-auth-tokens                           	List service auth tokens
create-service-auth-token [LABEL] [PROVIDER]  	Create a service auth token
update-service-auth-token [SERVICE_AUTH_TOKEN]	Update a service auth token
delete-service-auth-token [SERVICE_AUTH_TOKEN]	Delete a service auth token
```
