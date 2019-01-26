## VPC with 2 Public Subnets

This template will create the following resources:

* A 10.0.0.0/16 VPC,
* 2 public 10.0.0.0/18 subnets,
* A security group allowing outbound access,
* A VPC endpoint to S3.

Template File: [vpc-2-public-subnets.template](vpc-2-public-subnets.template)

![vpc-2-public-subnets](vpc-2-public-subnets.png?raw=true)

## IAM Role

This template will create the following resources:

* An IAM role,
* An IAM policy allowing:
  * `s3:PutObject`
* An IAM instance profile

Template File: [iam-role.template](iam-role.template)