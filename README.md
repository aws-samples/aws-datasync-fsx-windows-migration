# Migrate to FSx Windows File Server using AWS DataSync

© 2020 Amazon Web Services, Inc. and its affiliates. All rights reserved.
This sample code is made available under the MIT-0 license. See the LICENSE file.

Errors or corrections? Contact [jeffbart@amazon.com](mailto:jeffbart@amazon.com).

---

## Workshop scenario

In your data center, you have a Windows Server that is starting to age out.  This server provides user shares and home directories for groups within your organization.  To reduce your data center footprint and to free up resources, you would like to move the data on the Windows Server into the AWS cloud.

After doing some research, you have learned that you can use [AWS DataSync](https://aws.amazon.com/datasync/) to migrate the data from your on-premises Windws Server to [Amazon FSx for Windows File Server](https://aws.amazon.com/fsx/windows/).

This workshop will walk you through this scenario, using a CloudFormation template to deploy resources and the AWS Management console to configure those resources accordingly.

## Topics covered

- Deploying resources using CloudFormation
- Creating and managing FSx for Windows File Server shares
- Using AWS DataSync to copy data from a Windows Server to FSx

## Prerequisites

#### AWS Account

In order to complete this workshop, you will need an AWS account with rights to create AWS IAM roles, EC2 instances, FSx file systems, DataSync agents, and CloudFormation stacks in the AWS regions you select.

#### Software

- **Internet Browser**  – It is recommended that you use the latest version of Chrome or Firefox for this workshop.

## Cost

It will cost approximately **10.00 USD** to run this workshop.  It is recommended that you follow the cleanup instructions once you have completed the workshop to remove all deployed resources and limit ongoing costs to your AWS account.

## Related workshops

- [NFS server migration using AWS DataSync and Storage Gateway](https://github.com/aws-samples/aws-datasync-migration-workshop/blob/master/workshops/nfs-migration)
- [Migrate millions of files using AWS DataSync](https://github.com/aws-samples/aws-datasync-migration-workshop/blob/master/workshops/nfs-million-files)
- [Get hands-on with online data migration options to simplify & accelerate your journey to AWS](https://github.com/aws-samples/aws-online-data-migration-workshop)

## Workshop modules

This workshop consists of the following modules:

- **Module 1** - Deploy resources using CloudFormation
- **Module 2** - Configure file shares on the Windows Server and FSx
- **Module 3** - Copy files from the Windows Server to FSx using DataSync
- **Module 4** - Cleanup resources

To get started, go to [Module 1](/module1).
