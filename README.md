# AWS Certified Solutions Architect - Associate (SSA-C03) exam preparation

## Introduction about exam

<p>The exam AWS Certified Solutions Architect - Associate is intended for people who perform the role of solutions architect.</p>

<p>The exam validates the candidate's ability to complete the following tasks:</p>

 - Design solutions that incorporate services to meet business requirements and future needs.

 - Design secure, resilient, high-performance and cost-effective architectures.

 - Analyze existing solutions and determine how to make improvements.

## IAM & AWS CLI

![IAM](/home/cristiano/Documentos/fontes/guia-estudo-cetificacao-solutions-architect/images/iam.jpg)

### What is the IAM? 
<p>IAM (AWS Identity and Access Management), is an internet service that helps you control access to the resources securely.</p> 

<p>Root account created by default, shouldn't be used or shared </p>

<p>Users are people within your organization, and can be grouped</p>

<p>Groups only contain users, not other groups</p>

### IAM: Permissions

 - Users or Groups can be assigned JSON document called policies.

 - These policies define the permissions of the users.

 - In aws you apply the least privilege principle: don't give more permissions than a user needs. 