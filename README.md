# Amazon Cognito Identity SDK for JavaScript for Node.js

## Install
```sh
npm install amazon-cognito-identity-node
```

## Usage
``
var AWS = require('aws-sdk');
var CognitoSDK = require('amazon-cognito-identity-js-node');

AWS.CognitoIdentityServiceProvider.AuthenticationDetails = CognitoSDK.AuthenticationDetails;
AWS.CognitoIdentityServiceProvider.CognitoUserPool = CognitoSDK.CognitoUserPool;
AWS.CognitoIdentityServiceProvider.CognitoUser = CognitoSDK.CognitoUser;
``
