# Serverless Cron Job Tutorial

This is the repository for the [Serverless Cron Job](https://docs.stackery.io/docs/tutorials/cron-job-tutorial/) from Stackery.

This tutorial will show you how to trigger a Lambda function to run regularly on a schedule.

## Deploy this to your AWS account

You can deploy this application to your own AWS account using the following two Stackery CLI commands:

`stackery create` will initialize a new repo in your GitHub account, initializing it with the contents of the referenced template repository.

```bash
stackery create --stack-name 'cron-job-example' \
--git-provider 'github' \
--blueprint-git-url 'https://github.com/stackery/sam-cron-demo'
```

`stackery deploy` will deploy the newly created stack into your AWS account.

```bash
stackery deploy --stack-name 'cron-job-example' \
--env-name 'development' \
--git-ref 'master'
```
