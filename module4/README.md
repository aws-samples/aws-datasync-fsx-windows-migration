# Migrate to FSx Windows File Server using AWS DataSync

© 2020 Amazon Web Services, Inc. and its affiliates. All rights reserved.
This sample code is made available under the MIT-0 license. See the LICENSE file.

Errors or corrections? Contact [jeffbart@amazon.com](mailto:jeffbart@amazon.com).

---

# Module 4
## Workshop clean-up

To make sure all resources are deleted after this workshop scenario make sure you execute the steps in the order outlined below (you do not need to wait for CloudFormation to finish deleting before moving to the next step):

1. Go to the AWS management console and go to the **DataSync** service.
2. Select **Tasks** and delete the task you created previously
3. Select **Locations** and delete the locations you created previously
4. Select **Agents** and delete the agent you activated previously.  Note that this **will not** delete the actual DataSync agent EC2 instance.  That will get deleted when the CloudFormation stack is deleted.
5. Go to the CloudFormation page and delete the stack named **MigrationWorkshop**.

To make sure that all CloudFormation templates have been deleted correctly, confirm that any EC2 instances created in this workshop are in the **terminated** state.
