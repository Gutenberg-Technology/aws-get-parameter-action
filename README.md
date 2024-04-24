# AWS Get Parameter Composite Action

This GitHub Composite Action (GHCA) retrieves parameters from AWS Systems Manager (SSM) Parameter Store and sets them as environment variables for use in subsequent steps.

This goal to use this GHCA is to reduce code in your CICD workflows. 

This Composite uses two GitHub Actions:
- [aws-actions/configure-aws-credentials@v4](https://github.com/aws-actions/configure-aws-credentials)
- [dkershner6/aws-ssm-getparameters-action@v2](https://github.com/dkershner6/aws-ssm-getparameters-action)

## How to use it

See example.yml.dist