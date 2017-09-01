# Shutdown all EC2 instances.
Date: 2017-08-28

This CloudFormation templates is prepared to lunch as StackSets.

Configuration implements a AWS Lambda and CloudWatch Event Rule that shutdown all EC2 instances at 22:00.

Use and modify as you wish :)

Read more about StackSets:

[https://aws.amazon.com/blogs/aws/use-cloudformation-stacksets-to-provision-resources-across-multiple-aws-accounts-and-regions/](https://aws.amazon.com/blogs/aws/use-cloudformation-stacksets-to-provision-resources-across-multiple-aws-accounts-and-regions/)

How to use it:
1. Go to AWS console -> CloudFormation.
2. From the top left side menu click on CloudFormation and choose a StackSets
3. Deploy the configuration on accounts and regions you wish to.

For details how to implement StackSets please read an link above.


Author:
Łukasz Dorosz [@mrdoro](https://twitter.com/mrdoro)
