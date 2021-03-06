# AWS CloudFormation Template
Some sample AWS CloudFormation templates to demonstrate the functionality. This should not be used at production purposes. 

## How to use the templates?
Can use 'create stack' option both on AWS Console and AWS CLI. If not familiar with CloudFormation, please use [Getting Started](https://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/GettingStarted.Walkthrough.html) walkthrough guide to use the templates in this repository.

## new-iam-user-iam-policy
Template Parameters:
 - ThisCFPwd
    - Password for the new IAM user. 

This template demonstrates:
 - Create a new IAM user
 - Create a new IAM Managed Policy with:
	- All ALLOW on EC2
	- All DENY on CloudTrial
 - Assign the policy to the newly created user.

Can extend this template to:
 - Create and download access keys for the new IAM user. 
 - Enforce a password policy using regular expression

## Reference
For all the supported AWS resources and their properties, see the [Template Reference](http://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/template-reference.html).

