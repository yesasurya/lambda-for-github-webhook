# lambda-for-github-webhook

### What is this?
This is a CloudFormation template which will provision followings:
1. A Lambda function which will receive the GitHub webhook payload
2. A public endpoint (API Gateway) which will route the request from GitHub webhook to the Lambda function

### Resources
Somehow, I found that this is super useful:
https://theburningmonk.com/cloudformation-ref-and-getatt-cheatsheet/
