# AWS Certification Notebook

## IAM
- IAM User: Person or App has permanent long-term credentials and is used to directly interact with AWS services

- IAM Group: A set of IAM Users

- IAM Role: Don't has long-term credentials and don't use to directly interact with AWS Services. Allow you to delegate access with defined permissions to trusted entities without having to share long-term access keys. You can use IAM roles to delegate access to IAM users managed within your account, to IAM users under a different AWS account, or to an AWS service such as EC2. AWS Security Token Service (STS) generates a temporary token for anyone who taks a role.

- IAM Policy: Defines permission for identity or resource

- Identity Federation (Web) - Provides a mechanism to access resources without create a IAM User.