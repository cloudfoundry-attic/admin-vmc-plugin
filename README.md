[![Build Status](https://travis-ci.org/cloudfoundry/admin-vmc-plugin.png)](https://travis-ci.org/cloudfoundry/admin-vmc-plugin)
[![Gem Version](https://badge.fury.io/rb/admin-vmc-plugin.png)](http://badge.fury.io/rb/admin-vmc-plugin)

## Deprecated
VMC and its plugins have been renamed. You can find the current version of the code for this gem at
http://github.com/cloudfoundry/admin-cf-plugin

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
