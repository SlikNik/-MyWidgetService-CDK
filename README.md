# Welcome to MyWidgetService CDK TypeScript project

This is a starter project for CDK development with TypeScript.

The `cdk.json` file tells the CDK Toolkit how to execute your app.

## Useful commands

-   `npm run build` compile typescript to js
-   `npm run watch` watch for changes and compile
-   `npm run test` perform the jest unit tests
-   `cdk deploy` deploy this stack to your default AWS account/region
-   `cdk diff` compare deployed stack with current state
-   `cdk synth` emits the synthesized CloudFormation template

### URL for server

Outputs:

-   MyWidgetServiceStack.WidgetswidgetsapiEndpoint5B785C68 = https://1hh6dix6ve.execute-api.us-east-1.amazonaws.com/prod/

    -   Testing:
        curl -X GET 'https://1hh6dix6ve.execute-api.us-east-1.amazonaws.com/prod/'
        curl -X POST 'https://1hh6dix6ve.execute-api.us-east-1.amazonaws.com/prod/example'
        curl -X GET 'https://1hh6dix6ve.execute-api.us-east-1.amazonaws.com/prod/'
        curl -X GET 'https://1hh6dix6ve.execute-api.us-east-1.amazonaws.com/prod/example'
        curl -X DELETE 'https://1hh6dix6ve.execute-api.us-east-1.amazonaws.com/prod/example'
        curl -X GET 'https://1hh6dix6ve.execute-api.us-east-1.amazonaws.com/prod/'

        -   The Body for the Post can be anything you like
