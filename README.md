 ## Auction Notification Service

The service sends emails. It uses SQS.


## Getting started
Firstly, install dependencies:
```
npm i
```
After that, deploy application
```
sls deploy -v
```
or deploying specific function if there are no changes in the serverless.yml

```
sls deploy -f FUNCTION_NAME -v
```
