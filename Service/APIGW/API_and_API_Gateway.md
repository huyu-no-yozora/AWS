# API and API Gateway

## Table of Contents
<!--toc-->
* [API](#api)
  * [Resource and Method](#resource-and-method)
  * [Lambda Authorizer](#lambda-authorizer)
* [API Gateway](#api-gateway)
  * [Connection to Endpoint](#connection-to-endpoint)
  * [VPCLink](#vpclink)
* [Reference](#reference)
<!--toc-->

## API
### Resource and Method
Resource
: a process in a part of API(means nearly same with URL)
Method
: HTTP Method(GET, POST, PUT, ...)

### Lambda Authorizer
Lambda Authorizer
: A system of authorization and authentification by uning a Lambda function(named Auth Function)


## API Gateway
### Connection to Endpoint
You can select from following.
* Lambda
* AWS Service
* Mock
* VPCLink

### VPCLink
(PrivateLink)

```
APIGW <-> NLB <-> Auto Scaling Group
```



## Reference
* []()



