# AWS Certified Solutions Architect - Associate (SSA-C03) exam preparation

## Introduction about exam

<p>The exam AWS Certified Solutions Architect - Associate is intended for people who perform the role of solutions architect.</p>

<p>The exam validates the candidate's ability to complete the following tasks:</p>

 - Design solutions that incorporate services to meet business requirements and future needs.

 - Design secure, resilient, high-performance and cost-effective architectures.

 - Analyze existing solutions and determine how to make improvements.

## IAM & AWS CLI

<img src="./images/iam.jpg" alt="Image IAM">

### What is the IAM? 
<p>IAM (AWS Identity and Access Management), is an internet service that helps you control access to the resources securely.</p> 

<p>Root account created by default, shouldn't be used or shared </p>

<p>Users are people within your organization, and can be grouped</p>

<p>Groups only contain users, not other groups</p>

### IAM: Permissions

 - Users or Groups can be assigned JSON document called policies.

 - These policies define the permissions of the users.

 - In aws you apply the least privilege principle: don't give more permissions than a user needs. 

 - IAM is a global service

### IAM: Polices

Consists of
 - Verion: policy language version, always include "2021-10-17"
 - id: an identifier for the policy (optional)
 - Statement: one or more individual statements (required)
 
Statements consists of
 - Sid: an identifier for the statement (optional)
 - Effect: whether the statement allows or denies access (Allow, Deny)
 - Principal: account/user/role to which this policy applied to
 - Action: list of actions this policy allows or denies
 - Resources: list of resources to which the actions applied to
 - Condition: conditions for when this policy is in effect (optional)

 IAM Policies are JSON documents used to describe permissions within AWS. 

 ### IAM Role
  - IAM Users, applications, and services may assume IAM rules
  - User an IAM policy for permissions

 ### Bringing it all together

 - Step 1: IAM Group
 - Step 2: IAM Policy -> IAM Group
 - Step 3: IAM User -> IAM User

### IAM - Password Policy

 - Strong passwords = higher security for your account
 - In AWS, you can setup a password policy:
  * Set a minimum password lenth
  * Require specific character types:
   - including uppercase letters
   - lowercase letters
   - numbers
   - non-alphanumeric characters

 - Allow all IAM user to change their own passwords
 - Require users to change their password after some time (password expiration)
 - Prevent password re-use

 How can users access AWS ? 

To access AWS, you have three options:
 - AWS Management console (protected by password + MFA)
 - AWS Command line interface (CLI): protected by access keys
 - AWS Software Developer KIt (SDK): for code: protected by access keys

Access keys are generated though the AWS Console
User manager their own access keys
Access Keys are secret, just like a password. Don't share them.
Access key ID ~= Username
Secret Access Key ~= password

What's the AWS SDK? 
 - AWS Software Developement Kit (AWS SDK)
 - Language-specific APIs (set of libraries)
 - Enables you to access and manage AWS services programmatically
 - Embedded within your application
 - Supports
   - SDKs (Javascript, Python, PHP, .NET, Ruby, Java, Go, Node.js, C++)
   - Mobile SDKs (Android, iOS ...)
   - IoT Device SDKs (Embedded C, Arduino ...)

### IAM Roles for services

 - Some AWS service will need to perform actions on your behalf

 - To do so, we will assign permissions to AWS services with IAM Roles

 - Commons roles: 
   - EC2 Instance Roles
   - Lambda Function Roles
   - Roles for CloudFormation

### Security best practices in IAM

 - Require human users to use federation with an identity provider to access AWS using temporary credentials.

 - Require workloads to use temporary credentials with IAM roles to access AWS.

 - Require multi-factor authentication (MFA).

 - Update acces keys when needed for use cases that require long-term credentials.

 - Apply least-privilege permissions.

 - Get started with AWS managed policies and move toward least-privilege permissions.

 - User IAM Access analyzer to generate least-privilege policies based on access activity. 

 - Regular review and remove unused users, roles, permissions, policies, and credentials.

 - Use conditions in IAM policies to further restric access.

 - verify public and cross-account access to resources with IAM access Analyzer.

 - Use IAM Acess Analyzer to validate your IAM policies to ensure secure and functional permissions. 

 - Establish permissions guardrails accrros multiple accounts. 

 - Use permissions boundaries to delegate permissions management within an account. 

