Sample RESTful Web Service using Serverless Application Model
=============================================================

Contents of Repo
----------------

* README.md
* buildspec.yml - used by AWS CodeBuild to package the web service 
  for deployment to AWS Lambda
* app.js - sample Node.js code for the web service
* index.js - contains the AWS Lambda handler code
* template.yml - contains the AWS Serverless Application Model (AWS SAM) used
  by AWS CloudFormation to deploy the web service to AWS Lambda and Amazon API
  Gateway.
* tests/ - this directory contains unit tests for the web service
* template-configuration.json - contains the project ARN with placeholders used for tagging resources with the project ID

What's Next?
------------
* More routes for the web service (example: Products, Customers, Orders, etc...)
* Web service documentation

References
----------

* AWS CodeBuild - https://docs.aws.amazon.com/codebuild/latest/userguide/concepts.html
* AWS Serverless Applicaiton Model - https://github.com/awslabs/serverless-application-model/blob/master/HOWTO.md
* AWS Lambda Developer Guide  - http://docs.aws.amazon.com/lambda/latest/dg/deploying-lambda-apps.html
* AWS CodeStar - http://docs.aws.amazon.com/codestar/latest/userguide/welcome.html
* AWS CodeStar Best Practices - https://docs.aws.amazon.com/codestar/latest/userguide/best-practices.html?icmpid=docs_acs_rm_sec
