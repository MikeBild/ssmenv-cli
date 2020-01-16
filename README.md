# AWS SSM Parameter Store to Environment Variables

Reads key/values from AWS SSM Parameter-Store and applies it to environment variables.

## Install

`npm install -g ssmenv`

## Getting started

1. Create a `.env` or `.env.[NODE_ENV]` file
2. Add CDK_STACK_NAME=MyStackName, CDK_STACK_ENV=MyStackEnvName to the created `.env` file
3. Enter `ssmenv` into the command-line
