1\. From Azure Security, you create a custom alert rule. You need to configure which users will receive an email message when the alert is triggered. What should you do?

- [ ]  A. From Azure Monitor, create an action group.

- [ ]  B. From Security Center, modify the Security policy settings of the Azure subscription.

- [ ]  C. From Azure Active Directory (Azure AD). modify the members of the Security Reader role group.

- [ ]  D. From Security Center, modify the alert rule.


Scenario:
Litware identifies the following identity and access requirements: All San Francisco users and their devices must be members of Group1.
The tenant currently contain this group:
![](https://www.examtopics.com/assets/media/exam-media/02797/0000500001.png)
References:
https://docs.microsoft.com/en-us/azure/active-directory/users-groups-roles/groups-dynamic-membership https://docs.microsoft.com/en-us/azure/active-directory/fundamentals/active-directory-groups-create-azure-portal
2\. You need to meet the identity and access requirements for Group1. What should you do?

- [ ]  A. Add a membership rule to Group1.

- [ ]  B. Delete Group1. Create a new group named Group1 that has a membership type of Office 365. Add users and devices to the group.

- [ ]  C. Modify the membership rule of Group1.

- [ ]  D. Change the membership type of Group1 to Assigned. Create two groups that have dynamic memberships. Add the new groups to Group1.

3\. You have multiple development teams that will create apps in Azure. You plan to create a standard development environment that will be deployed for each team. You need to recommend a solution that will enforce resource locks across the development environments and ensure that the locks are applied in a consistent manner. What should you include in the recommendation?

- [ ]  A. an Azure policy

- [ ]  B. an Azure Resource Manager template

- [ ]  C. a management group

- [ ]  D. an Azure blueprint

4\. You are troubleshooting a security issue for an Azure Storage account. You enable the diagnostic logs for the storage account. What should you use to retrieve the diagnostics logs?

- [ ]  A. Azure Storage Explorer

- [ ]  B. SQL query editor in Azure

- [ ]  C. File Explorer in Windows

- [ ]  D. Azure Security Center

5\. You have an Azure Sentinel deployment. You need to create a scheduled query rule named Rule1. What should you use to define the query rule logic for Rule1?

- [ ]  A. a Transact-SQL statement

- [ ]  B. a JSON definition

- [ ]  C. GraphQL

- [ ]  D. a Kusto query

6\. You company has an Azure subscription named Sub1. Sub1 contains an Azure web app named WebApp1 that uses Azure Application Insights. WebApp1 requires users to authenticate by using OAuth 2.0 client secrets. Developers at the company plan to create a multi-step web test app that preforms synthetic transactions emulating user traffic to Web App1. You need to ensure that web tests can run unattended. What should you do first?

- [ ]  A. In Microsoft Visual Studio, modify the .webtest file.

- [ ]  B. Upload the .webtest file to Application Insights.

- [ ]  C. Register the web test app in Azure AD.

- [ ]  D. Add a plug-in to the web test app.

7\. You have a Azure subscription that contains an Azure Container Registry named Registry1. The subscription uses the Standard use tier of Azure Security Center. You upload several container images to Register1. You discover that vulnerability security scans were not performed You need to ensured that the images are scanned for vulnerabilities when they are uploaded to Registry1. What should you do?

- [ ]  A. From the Azure portal modify the Pricing tier settings.

- [ ]  B. From Azure CLI, lock the container images.

- [ ]  C. Upload the container images by using AzCopy

- [ ]  D. Push the container images to Registry1 by using Docker

8\. You have an Azure SQL Database server named SQL1. You plan to turn on Advanced Threat Protection for SQL1 to detect all threat detection types. Which action will Advanced Threat Protection detect as a threat? What should you do?

- [ ]  A. A user updates more than 50 percent of the records in a table.

- [ ]  B. A user attempts to sign as SELECT \* from table1.

- [ ]  C. A user is added to the db\_owner database role.

- [ ]  D. A user deletes more than 100 records from the same table.

9\. You have an Azure Active Directory (Azure AD) tenant named contoso.onmicrosoft.com. The User administrator role is assigned to a user named Admin1. An external partner has a Microsoft account that uses the user1@outlook.com sign in. Admin1 attempts to invite the external partner to sign in to the Azure AD tenant and receives the following error message: "Unable to invite user user1@outlook.com Generic authorization exception." You need to ensure that Admin1 can invite the external partner to sign in to the Azure AD tenant. What should you do?

- [ ]  A. From the Roles and administrators blade, assign the Security administrator role to Admin1.

- [ ]  B. From the Organizational relationships blade, add an identity provider.

- [ ]  C. From the Custom domain names blade, add a custom domain.

- [ ]  D. From the Users blade, modify the External collaboration settings.

10\. You have an Azure subscription that contains an app named App1. App1 has the app registration shown in the following table. You need to ensure that App1 can read all user calendars and create appointments. The solution must use the principle of least privilege. What should you do?

![](https://storage.googleapis.com/peopleaps//peopleapspeneraju/1257/Azure-Security-Engineer.PNG?GoogleAccessId=peopleaps-bucket-serivce%40peopleaps-263002.iam.gserviceaccount.com&Expires=1648965748&Signature=QPgjEOqC8NZyLldU9bd6niLE5M%2FG3HBTQAu1PG8aVSmMufzVvQO%2Bu7rHFIyrdoepDirFgzPfIO4FpQ0UwBVAHr5ojyQcIlk1AQjnVU0A%2BY3V0kzHH5FEO5bzhaNbUt5%2BOlXH4of69J2%2FKQX0U31hqUGx8PZ5OU68Ze2AXAgQRm%2BHPSMFTluuwDYS%2FPqzi7RjhofyvnsyThIk6YMUn3fCIixKb2Bajsm6rQ5d0aN0VfVx6wCSYqx6%2BrAn%2B47qZuK%2BgDEIqqk9ElpFUfIo4utymk%2BKjXYPJ8VVVIKpNcHPSrPvTAjDAeMeMyce6U9cDb5kmCcsGyBGlqOFkh6FUeY4cQ%3D%3D)

(click to enlarge the image)

- [ ]  A. Add a new Delegated API permission for Microsoft.Graph Calendars.ReadWrite.

- [ ]  B. Add a new Application API permission for Microsoft.Graph Calendars.ReadWrite.

- [ ]  C. Select Grant admin consent.

- [ ]  D. Add a new Delegated API permission for Microsoft.Graph Calendars.ReadWrite.Shared.

11\. You have an Azure environment. You need to identify any Azure configurations and workloads that are non-compliant with ISO 27001 standards. What should you use?

- [ ]  A. Azure Sentinel

- [ ]  B. Azure Active Directory (Azure AD) Identity Protection

- [ ]  C. Azure Security Center

- [ ]  D. Azure Advanced Threat Protection (ATP)

12\. You have an Azure web app named webapp1. You need to configure continuous deployment for webapp1 by using an Azure Repo. What should you create first?

- [ ]  A. an Azure Application Insights service

- [ ]  B. an Azure DevOps organizations

- [ ]  C. an Azure Storage account

- [ ]  D. an Azure DevTest Labs lab

13\. You plan to deploy Azure container instances. You have a containerized application that validates credit cards. The application is comprised of two containers: an application container and a validation container. The application container is monitored by the validation container. The validation container performs security checks by making requests to the application container and waiting for responses after every transaction. You need to ensure that the application container and the validation container are scheduled to be deployedtogether. The containers must communicate to each other only on ports that are not externally exposed. What should you include in the deployment?

- [ ]  A. application security groups

- [ ]  B. network security groups (NSGs)

- [ ]  C. management groups

- [ ]  D. container groups

14\. You have an Azure resource group that contains 100 virtual machines. You have an initiative named Initiative1 that contains multiple policy definitions. Initiative1 is assigned to the resource group. You need to identify which resources do NOT match the policy definitions. What should you do?

- [ ]  A. From Azure Security Center, view the Regulatory compliance assessment.

- [ ]  B. From the Policy blade of the Azure Active Directory admin center, select Compliance.

- [ ]  C. From Azure Security Center, view the Secure Score.

- [ ]  D. From the Policy blade of the Azure Active Directory admin center, select Assignments.

15\. You need to ensure that User2 can implement PIM. What should you do first?

- [ ]  A. Assign User2 the Global administrator role.

- [ ]  B. Configure authentication methods for contoso.com.

- [ ]  C. Configure the identity secure score for contoso.com.

- [ ]  D. Enable multi-factor authentication (MFA) for User2.

16\. You need to ensure that you can meet the security operations requirements. What should you do first?

- [ ]  A. Turn on Auto Provisioning in Security Center.

- [ ]  B. Integrate Security Center and Microsoft Cloud App Security.

- [ ]  C. Upgrade the pricing tier of Security Center to Standard.

- [ ]  D. Modify the Security Center workspace configuration.

17\. You have an Azure subscription that contains the Azure virtual machines shown in the following table. You create an MDM Security Baseline profile named Profile1. You need to identify to which virtual machines Profile1 can be applied. Which virtual machines should you identify?

![](https://storage.googleapis.com/peopleaps//peopleapspeneraju/1256/Azure-Security-Engineer.PNG?GoogleAccessId=peopleaps-bucket-serivce%40peopleaps-263002.iam.gserviceaccount.com&Expires=1648965748&Signature=jhbw4u86rwT20G%2B0B3oMHZ4HUY%2Bipg8wJlzG2TMwBpfZMm7cf3T%2FlDlVcB8n8275OpSkfmFRpctY6SeEm7FpBF2o%2Bg1y5izf2hmcT61U1YBp2ZUbii%2BfrZmtSE0G3eNNP0llCpwArf%2BL6z%2BsaxhB0rWLsYu0cd0G08RnuqjMiM7oYsLvpkm9KiSvKAXN6AP5%2BB397SG1QbHiCXtZnA1nhFhn%2BDl1S3XQhXiX75dvWxeGC%2BCBiNNpgiDvtf1eQR%2F%2B6NyfbFQ5VVUpwYlml4OZWWFsWyS6WKiTQvqSpeHiLDRRtVy6qtJ9HutX2356%2BKJ%2B42FlJkBnHnznp%2BdV6eaShg%3D%3D)

(click to enlarge the image)

- [ ]  A. VM1 only

- [ ]  B. VM1, VM2, and VM3 only

- [ ]  C. VM1 and VM3 only

- [ ]  D. VM1, VM2, VM3, and VM4

18\. You have an Azure Storage account named storage1 that has a container named container1. You need to prevent the blobs in container1 from being modified. What should you do?

- [ ]  A. From container1, change the access level.

- [ ]  B. From container1 add an access policy.

- [ ]  C. From container1, modify the Access Control (1AM) settings.

- [ ]  D. From storage1 , enable soft delete for blobs.

19\. You have the Azure virtual machines shown in the following table. For which virtual machine can you enable Update Management?

![](https://storage.googleapis.com/peopleaps//peopleapspeneraju/1254/Azure-Security-Engineer.PNG?GoogleAccessId=peopleaps-bucket-serivce%40peopleaps-263002.iam.gserviceaccount.com&Expires=1648965748&Signature=qwbKYnG%2BFnjtWlYAcrxD2AAVGBB2Fo5TLvPXzGc0AeHxBIMojRbh7orMLPfc3t1MblvC%2Bh9qMDH9%2BIhvgba8a3Xk8gGH2I0MKDufoowFsCt7LqphiwIQDJAD9w0zOwEs4xhR8x0J8aNTnnCFessGqyopSACpuYco222IU3Jj7t6vgxFsPtNeDAdVuxvXNGjwesSe943A6CtRmPkPLAteES28kdpkmSFPmCXevhoK4%2FQHJoZABJHHGWlUBnLUOnpfHShheUgu4TrOzWqeCgG7vn3vXfBYE1%2Bt5hvCHFBW4ZN74ICu2pSAT%2FWz9KDiKzyQesUcjcZi9tr88oW3VAoQwA%3D%3D)

(click to enlarge the image)

- [ ]  A. VM2 and VM3 only

- [ ]  B. VM2, VM3, and VM4 only

- [ ]  C. VM1, VM2, and VM4 only

- [ ]  D. VM1, VM2, VM3, and VM4

- [ ]  E. VM1, VM2, and VM3 only

20\. You have an Azure subscription named Subscription1. You need to view which security settings are assigned to Subscription1 by default. Which Azure policy or initiative definition should you review?

- [ ]  A. the Audit diagnostic setting policy definition

- [ ]  B. the Enable Monitoring in Azure Security Center initiative definition

- [ ]  C. the Enable Azure Monitor for VMs initiative definition

- [ ]  D. the Azure Monitor solution 'Security and Audit' must be deployed policy definition

21\. You plan to use Azure Resource Manager templates to perform multiple deployments of identically configured Azure virtual machines. The password for the administrator account of each deployment is stored as a secret in different Azure key vaults. You need to identify a method to dynamically construct a resource ID that will designate the key vault containing the appropriate secret during each deployment. The name of the key vault and the name of the secret will be provided as inline parameters. What should you use to construct the resource ID?

- [ ]  A. a key vault access policy

- [ ]  B. a linked template

- [ ]  C. a parameters file

- [ ]  D. an automation account

22\. You have an Azure subscription that contains the virtual machines shown in the following table. All the virtual networks are peered. You deploy Azure Bastion to VNET2. Which virtual machines can be protected by the bastion host?

![](https://storage.googleapis.com/peopleaps//peopleapspeneraju/1255/Azure-Security-Engineer.PNG?GoogleAccessId=peopleaps-bucket-serivce%40peopleaps-263002.iam.gserviceaccount.com&Expires=1648965748&Signature=S%2FTQNfMcXqWIloqMCoimCnbX6GAOr7qoKvvJ%2BPclNvsok3zClIj1AYR10fE%2BAwq8z3FuDcoHAQmaKv%2FMVeF9ABmv9Zby8vyiIB1TVwTFypRx0JVd6tvxoZXHkg4NYJicloXsTIOpNxcHue99IduTxsS5bNU2LcWPl%2Fw8BE2NBMOUonKfOzm3dfBO78T7dSZ8q24p5S6CVZRL3wsEaGGFt5sHtwcFm1F9m%2FuVjf6bQLO6mP9Pl5aXhnPSuDzcW771ZLs5l9WxeNkS5h%2FyyoSw%2Bfp5Dn6yxeyR8KbNeYuBOkcz2V2khK%2F9TadKAGxX56LTvcM%2FTQaMWR5mOBK6V7hiIg%3D%3D)

(click to enlarge the image)

- [ ]  A. VM1, VM2, VM3, and VM4

- [ ]  B. VM1, VM2, and VM3 only

- [ ]  C. VM2 and VM4 only

- [ ]  D. VM2 only

23\. You need to recommend which virtual machines to use to host App1. The solution must meet the technical requirements for KeyVault1. Which virtual machines should you use?

- [ ]  A. VM1 only

- [ ]  B. VM1 and VM2 only

- [ ]  C. VM1, VM2, and VM4 only

- [ ]  D. VM1, VM2, VM3. and VM4

24\. You have an Azure subscription linked to an Azure Active Directory Premium Plan 1 tenant. You plan to implement Azure Active Directory (Azure AD) Identity Protection. You need to ensure that you can configure a user risk policy and a sign-in risk policy. What should you do first?

- [ ]  A. Purchase Azure Active Directory Premium Plan 2 licenses for all users.

- [ ]  B. Register all users for Azure Multi-Factor Authentication (MFA).

- [ ]  C. Enable security defaults for Azure AD.

- [ ]  D. Upgrade Azure Security Center to the standard tier.

25\. You have an Azure Active Directory (Azure AD) tenant that contains a user named Admin1. Admin1 is assigned the Application developer role. You purchase a cloud app named App1 and register App1 in Azure AD. Admin1 reports that the option to enable token encryption for App1 is unavailable. You need to ensure that Admin1 can enable token encryption for App1 in the Azure portal. What should you do?

- [ ]  A. Upload a certificate for App1.

- [ ]  B. Modify the API permissions of App1.

- [ ]  C. Add App1 as an enterprise application.

- [ ]  D. Assign Admin! the Cloud application administrator role.

26\. You have an Azure Active Directory (Azure AD) tenant. You need to prevent nonprivileged Azure AD users from creating service principals in Azure AD. What should you do in the Azure Active Directory admin center of the tenant?

- [ ]  A. From the Properties Wade, set Enable Security defaults to Yes.

- [ ]  B. From the Properties blade, set Access management fen Azure resources to No

- [ ]  C. From the User settings blade, set Users can register applications to No

- [ ]  D. From the User settings blade, set Restrict access to Azure AD administration portal to Yes.

27\. You have 10 on-premises servers that run Windows Server 2019. You plan to implement Azure Security Center vulnerability scanning for the servers. What should you install on the servers first?

- [ ]  A. the Security Events data connector in Azure Sentinel

- [ ]  B. the Microsoft Endpoint Configuration Manager client

- [ ]  C. the Azure Arc enabled servers Connected Machine agent

- [ ]  D. the Microsoft Defender for Endpoint agent

28\. You have an Azure subscription named Sub1. Sub1 contains a virtual network named VNet1 that contains one subnet named Subnet1. You create a service endpoint for Subnet1. Subnet1 contains an Azure virtual machine named VM1 that runs Ubuntu Server 18.04. You need to deploy Docker containers to VM1. The containers must be able to access Azure Storage resources and Azure SQL databases by using the service endpoint.

- [ ]  A. Create an application security group and a network security group (NSG).

- [ ]  B. Edit the docker-compose.yml file.

- [ ]  C. Install the container network interface (CNI) plug-in.

29\. Note: This question is part of a series of questions that present the same scenario. Each question in the series contains a unique solution that might meet the stated goals. Some question sets might have more than one correct solution, while others might not have a correct solution. After you answer a question in this section, you will NOT be able to return to it. As a result, these questions will not appear in the review screen. You have an Azure Subscription. The subscription contains 50 virtual machines that run Windows Server 2012 R2 or Windows Server 2016. You need to deploy Microsoft Antimalware to the virtual machines. Solution: You connect to each virtual machine and add a Windows feature. Does this meet the goal?

- [ ]  A. Yes

- [ ]  B. No

30\. From Azure Security Center, you need to deploy SecPol1. What should you do first?

- [ ]  A. Enable Azure Defender.

- [ ]  B. Create an Azure Management group.

- [ ]  C. Create an initiative.

- [ ]  D. Configure continuous export.

31\. Your network contains an Active Directory forest named contoso.com. The forest contains a single domain. You have an Azure subscription named Sub1 that is associated to an Azure Active Directory (Azure AD) tenant named contoso.com. You plan to deploy Azure AD Connect and to integrate Active Dire

- [ ]  A. federated identity with Active Directory Federation Services (AD FS)

- [ ]  B. password hash synchronization with seamless single sign-on (SSO)

- [ ]  C. pass-through authentication with seamless single sign-on (SSO)

32\. You have an Azure subscription that contains an Azure SQL database named sql1. You plan to audit sql1. You need to configure the audit log destination. The solution must meet the following requirements: Support querying events by using the Kusto query language. Minimize administrative effort. What should you configure?

- [ ]  A. a Log Analytics workspace.

- [ ]  B. a storage account

- [ ]  C. an event hub

33\. You have Azure Resource Manager templates that you use to deploy Azure virtual machines . You need to disable unused Windows features automatically as instances of the virtual machines are provisioned. What should you use?

- [ ]  A. security policies in Azure Security Center

- [ ]  B. Azure Logic Apps

- [ ]  C. an Azure Desired State Configuration (DSC) virtual machine extension

- [ ]  D. Azure Advisor

34\. Your company plans to create separate subscriptions for each department. Each subscription will be associated to the same Azure Active Directory (Azure AD) tenant. You need to configure each subscription to have the same role assignments. What should you use?

- [ ]  A. Azure Security Center

- [ ]  B. Azure Policy

- [ ]  C. Azure AD Privileged Identity Management (PIM)

- [ ]  D. Azure Blueprints

35\. You need to meet the technical requirements for VNetwork1. What should you do first?

- [ ]  A. Create a new subnet on VNetwork1.

- [ ]  B. Remove the NSGs from Subnet11 and Subnet13.

- [ ]  C. Associate an NSG to Subnet12.

- [ ]  D. Configure DDoS protection for VNetwork1.

36\. Note: This question is part of a series of questions that present the same scenario. Each question in the series contains a unique solution that might meet the stated goals. Some question sets might have more than one correct solution, while others might not have a correct solution. After you answer a question in this section, you will NOT be able to return to it. As a result, these questions will not appear in the review screen. You have an Azure Subscription named Sub1. You have an Azure Storage account named Sa1 in a resource group named RG1. Users and applications access the blob service and the file service in Sa1 by using several shared access signatures (SASs) and stored access policies. You discover that unauthorized users accessed both the file service and the blob service. You need to revoke all access to Sa1. Solution: You generate new SASs. Does this meet the goal?

- [ ]  A. Yes

- [ ]  B. No

37\. You have a web app hosted on an on-premises server that is accessed by using a URL of https://www.contoso.com. You plan to migrate the web app to Azure. You will continue to use https://www.contoso.com. You need to enable HTTPS for the Azure web app. What should you do first?

- [ ]  A. Export the public key from the on-premises server and save the key as a P7b file.

- [ ]  B. Export the private key from the on-premises server and save the key as a PFX file that is encrypted by using AES256.

- [ ]  C. Export the public key from the on-premises server and save the key as a CER file.

- [ ]  D. Export the private key from the on-premises server and save the key as a PFX file that is encrypted by using TripleDES.

38\. You have 15 Azure virtual machines in a resource group named RG1. All virtual machines run identical applications. You need to prevent unauthorized applications and malware from running on the virtual machines. What should you do?

- [ ]  A. Apply an Azure policy to RG1.

- [ ]  B. From Azure Security Center, configure adaptive application controls.

- [ ]  C. Configure Azure Active Directory (Azure AD) Identity Protection.

- [ ]  D. Apply a resource lock to RG1.

39\. You have an Azure virtual machines shown in the following table. You create an Azure Log Analytics workspace named Analytics1 in RG1 in the East US region. Which virtual machines can be enrolled in Analytics1?

![](https://storage.googleapis.com/peopleaps//peopleapspeneraju/1258/Azure-Security-Engineer.PNG?GoogleAccessId=peopleaps-bucket-serivce%40peopleaps-263002.iam.gserviceaccount.com&Expires=1648965748&Signature=U4MGp9X0%2FipWfQ16LHReRRv0QvjW7CKrOXD0tHExDpM3qC%2BahBhPipzznZnKd6MmujGDzGzER4ezzFcnriw%2FyntQvrgrGyUOshSXtbJaY87TOFZH6oWjBgHt6LAIvj4a0WvOQMGKqhu%2BbilpwYw%2BmX8RLyuypI%2BsacsGxt1IcaO74qjAqrSenXoFWjKujzgme0cWtChj2lOvX%2FafQnbfMd54wLfhK2YZR7awYlDTa5d9bZpkG4yfpqzOQ%2Floa1EvvE8vrTYZK3xSow0aM5VaBm2Wc8gVKDLO6FxkXuGZgb1HhRMsHuOHz00eeQYj8UAmtNGpeay0ODO%2FSlisR2EakQ%3D%3D)

(click to enlarge the image)

- [ ]  A. VM1 only

- [ ]  B. VM1, VM2, and VM3 only

- [ ]  C. VM1, VM2, VM3, and VM4

- [ ]  D. VM1 and VM4 only

40\. You have an Azure subscription named Sub1 that is associated to an Azure Active Directory (Azure AD) tenant named contoso.com. You are assigned the Global administrator role for the tenant. You are responsible for managing Azure Security Center settings. You need to create a custom sensitivity label. What should you

- [ ]  A. Create a custom sensitive information type.

- [ ]  B. Elevate access for global administrators in Azure AD.

- [ ]  C. Upgrade the pricing tier of the Security Center to Standard.

- [ ]  D. Enable integration with Microsoft Cloud App Security.

41\. You have been tasked with configuring an access review, which you plan to assigned to a new collection of reviews. You also have to make sure that the reviews can be reviewed by resource owners. You start by creating an access review program and an access review control. You now need to configure the Reviewers. Which of the following should you set Reviewers to?

- [ ]  A. Selected users.

- [ ]  B. Group Owners.

- [ ]  C. Members (Self).

- [ ]  D. Anyone.

42\. Note: This question is part of a series of questions that present the same scenario. Each question in the series contains a unique solution that might meet the stated goals. Some question sets might have more than one correct solution, while others might not have a correct solution. After you answer a question in this section, you will NOT be able to return to rt As a result, these questions will not appear in the review screen. You have an Azure subscription named Sub1. You have an Azure Storage account named Sa1 in a resource group named RG1. Users and applications access the blob service and the file service in Sal by using several shared access signatures {SASs) and stored access policies. You discover that unauthorized users accessed both the rile service and the blob service. You need to revoke all access to Sa1. Solution: You regenerate the access keys. Does this meet the goal?

- [ ]  A. Yes

- [ ]  B. No

43\. Your company uses Azure DevOps. You need to recommend a method to validate whether the code meets the company's quality standards and code review standards. What should you recommend implementing in Azure DevOps?

- [ ]  A. branch folders

- [ ]  B. branch permissions

- [ ]  C. branch policies

- [ ]  D. branch locking

44\. You need to ensure that users can access VM0. The solution must meet the platform protection requirements. What should you do?

- [ ]  A. Move VM0 to Subnet1.

- [ ]  B. On Firewall, configure a network traffic filtering rule.

- [ ]  C. Assign RT1 to AzureFirewallSubnet.

- [ ]  D. On Firewall, configure a DNAT rule.

45\. You are configuring an Azure Kubernetes Service (AKS) cluster that will connect to an Azure Container Registry. You need to use the auto-generated service principal to authenticate to the Azure Container Registry. What should you create?

- [ ]  A. an Azure Active Directory (Azure AD) group

- [ ]  B. an Azure Active Directory (Azure AD) role assignment

- [ ]  C. an Azure Active Directory (Azure AD) user

- [ ]  D. a secret in Azure Key Vault

46\. You need to encrypt storage1 to meet the technical requirements. Which key vaults can you use?

- [ ]  A. KeyVault1 only

- [ ]  B. KeyVault2 and KeyVault3 only

- [ ]  C. KeyVault1 and KeyVault3 only

- [ ]  D. KeyVault1 KeyVault2 and KeyVault3

47\. You have a hybrid configuration of Azure Active Directory (Azure AD). All users have computers that run Windows 10 and are hybrid Azure AD joined. You have an Azure SQL database that is configured to support Azure AD authentication. Database developers must connect to the SQL database by using Microsoft SQL Server Management Studio (SSMS) and authenticate by using their on-premises Active Directory account. You need to tell the developers which authentication method to use to connect to the SQL database from SSMS. The solution must minimize authentication prompts. Which authentication method should you instruct the developers to use?

- [ ]  A. SQL Login

- [ ]  B. Active Directory - Universal with MFA support

- [ ]  C. Active Directory - Integrated

- [ ]  D. Active Directory - Password

48\. You have an Azure subscription named Sub1. In Azure Security Center, you have a workflow automation named WF1. WF1 is configured to send an email message to a user named User1. You need to modify WF1 to send email messages to a distribution group named Alerts. What should you use to modify WF1?

- [ ]  A. Azure Application Insights

- [ ]  B. Azure Monitor

- [ ]  C. Azure Logic Apps Designer

- [ ]  D. Azure DevOps

49\. Your network contains an on-premises Active Directory domain named corp.contoso.com. You have an Azure subscription named Sub1 that is associated to an Azure Active Directory (Azure AD) tenant named contoso.com. You sync all on-premises identities to Azure AD. You need to prevent users who have a givenName attribute that starts with TEST from being synced to Azure AD. The solution must minimize administrative effort. What should you use?

- [ ]  A. Synchronization Rules Editor

- [ ]  B. Web Service Configuration Tool

- [ ]  C. the Azure AD Connect wizard

- [ ]  D. Active Directory Users and Computers

50\. You have an Azure web app named webapp1. You need to configure continuous deployment for webapp1 by using an Azure Repo. What should you create first?

- [ ]  A. an Azure Application Insights service

- [ ]  B. an Azure DevOps organization

- [ ]  C. an Azure Storage account

- [ ]  D. an Azure DevTest Labs lab1\. From Azure Security, you create a custom alert rule. You need to configure which users will receive an email message when the alert is triggered. What should you do?

- [ ]  A. From Azure Monitor, create an action group.

- [ ]  B. From Security Center, modify the Security policy settings of the Azure subscription.

- [ ]  C. From Azure Active Directory (Azure AD). modify the members of the Security Reader role group.

- [ ]  D. From Security Center, modify the alert rule.

2\. You need to meet the identity and access requirements for Group1. What should you do?

- [ ]  A. Add a membership rule to Group1.

- [ ]  B. Delete Group1. Create a new group named Group1 that has a membership type of Office 365. Add users and devices to the group.

- [ ]  C. Modify the membership rule of Group1.

- [ ]  D. Change the membership type of Group1 to Assigned. Create two groups that have dynamic memberships. Add the new groups to Group1.

3\. You have multiple development teams that will create apps in Azure. You plan to create a standard development environment that will be deployed for each team. You need to recommend a solution that will enforce resource locks across the development environments and ensure that the locks are applied in a consistent manner. What should you include in the recommendation?

- [ ]  A. an Azure policy

- [ ]  B. an Azure Resource Manager template

- [ ]  C. a management group

- [ ]  D. an Azure blueprint

4\. You are troubleshooting a security issue for an Azure Storage account. You enable the diagnostic logs for the storage account. What should you use to retrieve the diagnostics logs?

- [ ]  A. Azure Storage Explorer

- [ ]  B. SQL query editor in Azure

- [ ]  C. File Explorer in Windows

- [ ]  D. Azure Security Center

5\. You have an Azure Sentinel deployment. You need to create a scheduled query rule named Rule1. What should you use to define the query rule logic for Rule1?

- [ ]  A. a Transact-SQL statement

- [ ]  B. a JSON definition

- [ ]  C. GraphQL

- [ ]  D. a Kusto query

6\. You company has an Azure subscription named Sub1. Sub1 contains an Azure web app named WebApp1 that uses Azure Application Insights. WebApp1 requires users to authenticate by using OAuth 2.0 client secrets. Developers at the company plan to create a multi-step web test app that preforms synthetic transactions emulating user traffic to Web App1. You need to ensure that web tests can run unattended. What should you do first?

- [ ]  A. In Microsoft Visual Studio, modify the .webtest file.

- [ ]  B. Upload the .webtest file to Application Insights.

- [ ]  C. Register the web test app in Azure AD.

- [ ]  D. Add a plug-in to the web test app.

7\. You have a Azure subscription that contains an Azure Container Registry named Registry1. The subscription uses the Standard use tier of Azure Security Center. You upload several container images to Register1. You discover that vulnerability security scans were not performed You need to ensured that the images are scanned for vulnerabilities when they are uploaded to Registry1. What should you do?

- [ ]  A. From the Azure portal modify the Pricing tier settings.

- [ ]  B. From Azure CLI, lock the container images.

- [ ]  C. Upload the container images by using AzCopy

- [ ]  D. Push the container images to Registry1 by using Docker

8\. You have an Azure SQL Database server named SQL1. You plan to turn on Advanced Threat Protection for SQL1 to detect all threat detection types. Which action will Advanced Threat Protection detect as a threat? What should you do?

- [ ]  A. A user updates more than 50 percent of the records in a table.

- [ ]  B. A user attempts to sign as SELECT \* from table1.

- [ ]  C. A user is added to the db\_owner database role.

- [ ]  D. A user deletes more than 100 records from the same table.

9\. You have an Azure Active Directory (Azure AD) tenant named contoso.onmicrosoft.com. The User administrator role is assigned to a user named Admin1. An external partner has a Microsoft account that uses the user1@outlook.com sign in. Admin1 attempts to invite the external partner to sign in to the Azure AD tenant and receives the following error message: "Unable to invite user user1@outlook.com Generic authorization exception." You need to ensure that Admin1 can invite the external partner to sign in to the Azure AD tenant. What should you do?

- [ ]  A. From the Roles and administrators blade, assign the Security administrator role to Admin1.

- [ ]  B. From the Organizational relationships blade, add an identity provider.

- [ ]  C. From the Custom domain names blade, add a custom domain.

- [ ]  D. From the Users blade, modify the External collaboration settings.

10\. You have an Azure subscription that contains an app named App1. App1 has the app registration shown in the following table. You need to ensure that App1 can read all user calendars and create appointments. The solution must use the principle of least privilege. What should you do?

![](https://storage.googleapis.com/peopleaps//peopleapspeneraju/1257/Azure-Security-Engineer.PNG?GoogleAccessId=peopleaps-bucket-serivce%40peopleaps-263002.iam.gserviceaccount.com&Expires=1648965748&Signature=QPgjEOqC8NZyLldU9bd6niLE5M%2FG3HBTQAu1PG8aVSmMufzVvQO%2Bu7rHFIyrdoepDirFgzPfIO4FpQ0UwBVAHr5ojyQcIlk1AQjnVU0A%2BY3V0kzHH5FEO5bzhaNbUt5%2BOlXH4of69J2%2FKQX0U31hqUGx8PZ5OU68Ze2AXAgQRm%2BHPSMFTluuwDYS%2FPqzi7RjhofyvnsyThIk6YMUn3fCIixKb2Bajsm6rQ5d0aN0VfVx6wCSYqx6%2BrAn%2B47qZuK%2BgDEIqqk9ElpFUfIo4utymk%2BKjXYPJ8VVVIKpNcHPSrPvTAjDAeMeMyce6U9cDb5kmCcsGyBGlqOFkh6FUeY4cQ%3D%3D)

(click to enlarge the image)

- [ ]  A. Add a new Delegated API permission for Microsoft.Graph Calendars.ReadWrite.

- [ ]  B. Add a new Application API permission for Microsoft.Graph Calendars.ReadWrite.

- [ ]  C. Select Grant admin consent.

- [ ]  D. Add a new Delegated API permission for Microsoft.Graph Calendars.ReadWrite.Shared.

11\. You have an Azure environment. You need to identify any Azure configurations and workloads that are non-compliant with ISO 27001 standards. What should you use?

- [ ]  A. Azure Sentinel

- [ ]  B. Azure Active Directory (Azure AD) Identity Protection

- [ ]  C. Azure Security Center

- [ ]  D. Azure Advanced Threat Protection (ATP)

12\. You have an Azure web app named webapp1. You need to configure continuous deployment for webapp1 by using an Azure Repo. What should you create first?

- [ ]  A. an Azure Application Insights service

- [ ]  B. an Azure DevOps organizations

- [ ]  C. an Azure Storage account

- [ ]  D. an Azure DevTest Labs lab

13\. You plan to deploy Azure container instances. You have a containerized application that validates credit cards. The application is comprised of two containers: an application container and a validation container. The application container is monitored by the validation container. The validation container performs security checks by making requests to the application container and waiting for responses after every transaction. You need to ensure that the application container and the validation container are scheduled to be deployedtogether. The containers must communicate to each other only on ports that are not externally exposed. What should you include in the deployment?

- [ ]  A. application security groups

- [ ]  B. network security groups (NSGs)

- [ ]  C. management groups

- [ ]  D. container groups

14\. You have an Azure resource group that contains 100 virtual machines. You have an initiative named Initiative1 that contains multiple policy definitions. Initiative1 is assigned to the resource group. You need to identify which resources do NOT match the policy definitions. What should you do?

- [ ]  A. From Azure Security Center, view the Regulatory compliance assessment.

- [ ]  B. From the Policy blade of the Azure Active Directory admin center, select Compliance.

- [ ]  C. From Azure Security Center, view the Secure Score.

- [ ]  D. From the Policy blade of the Azure Active Directory admin center, select Assignments.

15\. You need to ensure that User2 can implement PIM. What should you do first?

- [ ]  A. Assign User2 the Global administrator role.

- [ ]  B. Configure authentication methods for contoso.com.

- [ ]  C. Configure the identity secure score for contoso.com.

- [ ]  D. Enable multi-factor authentication (MFA) for User2.

16\. You need to ensure that you can meet the security operations requirements. What should you do first?

- [ ]  A. Turn on Auto Provisioning in Security Center.

- [ ]  B. Integrate Security Center and Microsoft Cloud App Security.

- [ ]  C. Upgrade the pricing tier of Security Center to Standard.

- [ ]  D. Modify the Security Center workspace configuration.

17\. You have an Azure subscription that contains the Azure virtual machines shown in the following table. You create an MDM Security Baseline profile named Profile1. You need to identify to which virtual machines Profile1 can be applied. Which virtual machines should you identify?

![](https://storage.googleapis.com/peopleaps//peopleapspeneraju/1256/Azure-Security-Engineer.PNG?GoogleAccessId=peopleaps-bucket-serivce%40peopleaps-263002.iam.gserviceaccount.com&Expires=1648965748&Signature=jhbw4u86rwT20G%2B0B3oMHZ4HUY%2Bipg8wJlzG2TMwBpfZMm7cf3T%2FlDlVcB8n8275OpSkfmFRpctY6SeEm7FpBF2o%2Bg1y5izf2hmcT61U1YBp2ZUbii%2BfrZmtSE0G3eNNP0llCpwArf%2BL6z%2BsaxhB0rWLsYu0cd0G08RnuqjMiM7oYsLvpkm9KiSvKAXN6AP5%2BB397SG1QbHiCXtZnA1nhFhn%2BDl1S3XQhXiX75dvWxeGC%2BCBiNNpgiDvtf1eQR%2F%2B6NyfbFQ5VVUpwYlml4OZWWFsWyS6WKiTQvqSpeHiLDRRtVy6qtJ9HutX2356%2BKJ%2B42FlJkBnHnznp%2BdV6eaShg%3D%3D)

(click to enlarge the image)

- [ ]  A. VM1 only

- [ ]  B. VM1, VM2, and VM3 only

- [ ]  C. VM1 and VM3 only

- [ ]  D. VM1, VM2, VM3, and VM4

18\. You have an Azure Storage account named storage1 that has a container named container1. You need to prevent the blobs in container1 from being modified. What should you do?

- [ ]  A. From container1, change the access level.

- [ ]  B. From container1 add an access policy.

- [ ]  C. From container1, modify the Access Control (1AM) settings.

- [ ]  D. From storage1 , enable soft delete for blobs.

19\. You have the Azure virtual machines shown in the following table. For which virtual machine can you enable Update Management?

![](https://storage.googleapis.com/peopleaps//peopleapspeneraju/1254/Azure-Security-Engineer.PNG?GoogleAccessId=peopleaps-bucket-serivce%40peopleaps-263002.iam.gserviceaccount.com&Expires=1648965748&Signature=qwbKYnG%2BFnjtWlYAcrxD2AAVGBB2Fo5TLvPXzGc0AeHxBIMojRbh7orMLPfc3t1MblvC%2Bh9qMDH9%2BIhvgba8a3Xk8gGH2I0MKDufoowFsCt7LqphiwIQDJAD9w0zOwEs4xhR8x0J8aNTnnCFessGqyopSACpuYco222IU3Jj7t6vgxFsPtNeDAdVuxvXNGjwesSe943A6CtRmPkPLAteES28kdpkmSFPmCXevhoK4%2FQHJoZABJHHGWlUBnLUOnpfHShheUgu4TrOzWqeCgG7vn3vXfBYE1%2Bt5hvCHFBW4ZN74ICu2pSAT%2FWz9KDiKzyQesUcjcZi9tr88oW3VAoQwA%3D%3D)

(click to enlarge the image)

- [ ]  A. VM2 and VM3 only

- [ ]  B. VM2, VM3, and VM4 only

- [ ]  C. VM1, VM2, and VM4 only

- [ ]  D. VM1, VM2, VM3, and VM4

- [ ]  E. VM1, VM2, and VM3 only

20\. You have an Azure subscription named Subscription1. You need to view which security settings are assigned to Subscription1 by default. Which Azure policy or initiative definition should you review?

- [ ]  A. the Audit diagnostic setting policy definition

- [ ]  B. the Enable Monitoring in Azure Security Center initiative definition

- [ ]  C. the Enable Azure Monitor for VMs initiative definition

- [ ]  D. the Azure Monitor solution 'Security and Audit' must be deployed policy definition

21\. You plan to use Azure Resource Manager templates to perform multiple deployments of identically configured Azure virtual machines. The password for the administrator account of each deployment is stored as a secret in different Azure key vaults. You need to identify a method to dynamically construct a resource ID that will designate the key vault containing the appropriate secret during each deployment. The name of the key vault and the name of the secret will be provided as inline parameters. What should you use to construct the resource ID?

- [ ]  A. a key vault access policy

- [ ]  B. a linked template

- [ ]  C. a parameters file

- [ ]  D. an automation account

22\. You have an Azure subscription that contains the virtual machines shown in the following table. All the virtual networks are peered. You deploy Azure Bastion to VNET2. Which virtual machines can be protected by the bastion host?

![](https://storage.googleapis.com/peopleaps//peopleapspeneraju/1255/Azure-Security-Engineer.PNG?GoogleAccessId=peopleaps-bucket-serivce%40peopleaps-263002.iam.gserviceaccount.com&Expires=1648965748&Signature=S%2FTQNfMcXqWIloqMCoimCnbX6GAOr7qoKvvJ%2BPclNvsok3zClIj1AYR10fE%2BAwq8z3FuDcoHAQmaKv%2FMVeF9ABmv9Zby8vyiIB1TVwTFypRx0JVd6tvxoZXHkg4NYJicloXsTIOpNxcHue99IduTxsS5bNU2LcWPl%2Fw8BE2NBMOUonKfOzm3dfBO78T7dSZ8q24p5S6CVZRL3wsEaGGFt5sHtwcFm1F9m%2FuVjf6bQLO6mP9Pl5aXhnPSuDzcW771ZLs5l9WxeNkS5h%2FyyoSw%2Bfp5Dn6yxeyR8KbNeYuBOkcz2V2khK%2F9TadKAGxX56LTvcM%2FTQaMWR5mOBK6V7hiIg%3D%3D)

(click to enlarge the image)

- [ ]  A. VM1, VM2, VM3, and VM4

- [ ]  B. VM1, VM2, and VM3 only

- [ ]  C. VM2 and VM4 only

- [ ]  D. VM2 only

23\. You need to recommend which virtual machines to use to host App1. The solution must meet the technical requirements for KeyVault1. Which virtual machines should you use?

- [ ]  A. VM1 only

- [ ]  B. VM1 and VM2 only

- [ ]  C. VM1, VM2, and VM4 only

- [ ]  D. VM1, VM2, VM3. and VM4

24\. You have an Azure subscription linked to an Azure Active Directory Premium Plan 1 tenant. You plan to implement Azure Active Directory (Azure AD) Identity Protection. You need to ensure that you can configure a user risk policy and a sign-in risk policy. What should you do first?

- [ ]  A. Purchase Azure Active Directory Premium Plan 2 licenses for all users.

- [ ]  B. Register all users for Azure Multi-Factor Authentication (MFA).

- [ ]  C. Enable security defaults for Azure AD.

- [ ]  D. Upgrade Azure Security Center to the standard tier.

25\. You have an Azure Active Directory (Azure AD) tenant that contains a user named Admin1. Admin1 is assigned the Application developer role. You purchase a cloud app named App1 and register App1 in Azure AD. Admin1 reports that the option to enable token encryption for App1 is unavailable. You need to ensure that Admin1 can enable token encryption for App1 in the Azure portal. What should you do?

- [ ]  A. Upload a certificate for App1.

- [ ]  B. Modify the API permissions of App1.

- [ ]  C. Add App1 as an enterprise application.

- [ ]  D. Assign Admin! the Cloud application administrator role.

26\. You have an Azure Active Directory (Azure AD) tenant. You need to prevent nonprivileged Azure AD users from creating service principals in Azure AD. What should you do in the Azure Active Directory admin center of the tenant?

- [ ]  A. From the Properties Wade, set Enable Security defaults to Yes.

- [ ]  B. From the Properties blade, set Access management fen Azure resources to No

- [ ]  C. From the User settings blade, set Users can register applications to No

- [ ]  D. From the User settings blade, set Restrict access to Azure AD administration portal to Yes.

27\. You have 10 on-premises servers that run Windows Server 2019. You plan to implement Azure Security Center vulnerability scanning for the servers. What should you install on the servers first?

- [ ]  A. the Security Events data connector in Azure Sentinel

- [ ]  B. the Microsoft Endpoint Configuration Manager client

- [ ]  C. the Azure Arc enabled servers Connected Machine agent

- [ ]  D. the Microsoft Defender for Endpoint agent

28\. You have an Azure subscription named Sub1. Sub1 contains a virtual network named VNet1 that contains one subnet named Subnet1. You create a service endpoint for Subnet1. Subnet1 contains an Azure virtual machine named VM1 that runs Ubuntu Server 18.04. You need to deploy Docker containers to VM1. The containers must be able to access Azure Storage resources and Azure SQL databases by using the service endpoint.

- [ ]  A. Create an application security group and a network security group (NSG).

- [ ]  B. Edit the docker-compose.yml file.

- [ ]  C. Install the container network interface (CNI) plug-in.

29\. Note: This question is part of a series of questions that present the same scenario. Each question in the series contains a unique solution that might meet the stated goals. Some question sets might have more than one correct solution, while others might not have a correct solution. After you answer a question in this section, you will NOT be able to return to it. As a result, these questions will not appear in the review screen. You have an Azure Subscription. The subscription contains 50 virtual machines that run Windows Server 2012 R2 or Windows Server 2016. You need to deploy Microsoft Antimalware to the virtual machines. Solution: You connect to each virtual machine and add a Windows feature. Does this meet the goal?

- [ ]  A. Yes

- [ ]  B. No

30\. From Azure Security Center, you need to deploy SecPol1. What should you do first?

- [ ]  A. Enable Azure Defender.

- [ ]  B. Create an Azure Management group.

- [ ]  C. Create an initiative.

- [ ]  D. Configure continuous export.

31\. Your network contains an Active Directory forest named contoso.com. The forest contains a single domain. You have an Azure subscription named Sub1 that is associated to an Azure Active Directory (Azure AD) tenant named contoso.com. You plan to deploy Azure AD Connect and to integrate Active Dire

- [ ]  A. federated identity with Active Directory Federation Services (AD FS)

- [ ]  B. password hash synchronization with seamless single sign-on (SSO)

- [ ]  C. pass-through authentication with seamless single sign-on (SSO)

32\. You have an Azure subscription that contains an Azure SQL database named sql1. You plan to audit sql1. You need to configure the audit log destination. The solution must meet the following requirements: Support querying events by using the Kusto query language. Minimize administrative effort. What should you configure?

- [ ]  A. a Log Analytics workspace.

- [ ]  B. a storage account

- [ ]  C. an event hub

33\. You have Azure Resource Manager templates that you use to deploy Azure virtual machines . You need to disable unused Windows features automatically as instances of the virtual machines are provisioned. What should you use?

- [ ]  A. security policies in Azure Security Center

- [ ]  B. Azure Logic Apps

- [ ]  C. an Azure Desired State Configuration (DSC) virtual machine extension

- [ ]  D. Azure Advisor

34\. Your company plans to create separate subscriptions for each department. Each subscription will be associated to the same Azure Active Directory (Azure AD) tenant. You need to configure each subscription to have the same role assignments. What should you use?

- [ ]  A. Azure Security Center

- [ ]  B. Azure Policy

- [ ]  C. Azure AD Privileged Identity Management (PIM)

- [ ]  D. Azure Blueprints

35\. You need to meet the technical requirements for VNetwork1. What should you do first?

- [ ]  A. Create a new subnet on VNetwork1.

- [ ]  B. Remove the NSGs from Subnet11 and Subnet13.

- [ ]  C. Associate an NSG to Subnet12.

- [ ]  D. Configure DDoS protection for VNetwork1.

36\. Note: This question is part of a series of questions that present the same scenario. Each question in the series contains a unique solution that might meet the stated goals. Some question sets might have more than one correct solution, while others might not have a correct solution. After you answer a question in this section, you will NOT be able to return to it. As a result, these questions will not appear in the review screen. You have an Azure Subscription named Sub1. You have an Azure Storage account named Sa1 in a resource group named RG1. Users and applications access the blob service and the file service in Sa1 by using several shared access signatures (SASs) and stored access policies. You discover that unauthorized users accessed both the file service and the blob service. You need to revoke all access to Sa1. Solution: You generate new SASs. Does this meet the goal?

- [ ]  A. Yes

- [ ]  B. No

37\. You have a web app hosted on an on-premises server that is accessed by using a URL of https://www.contoso.com. You plan to migrate the web app to Azure. You will continue to use https://www.contoso.com. You need to enable HTTPS for the Azure web app. What should you do first?

- [ ]  A. Export the public key from the on-premises server and save the key as a P7b file.

- [ ]  B. Export the private key from the on-premises server and save the key as a PFX file that is encrypted by using AES256.

- [ ]  C. Export the public key from the on-premises server and save the key as a CER file.

- [ ]  D. Export the private key from the on-premises server and save the key as a PFX file that is encrypted by using TripleDES.

38\. You have 15 Azure virtual machines in a resource group named RG1. All virtual machines run identical applications. You need to prevent unauthorized applications and malware from running on the virtual machines. What should you do?

- [ ]  A. Apply an Azure policy to RG1.

- [ ]  B. From Azure Security Center, configure adaptive application controls.

- [ ]  C. Configure Azure Active Directory (Azure AD) Identity Protection.

- [ ]  D. Apply a resource lock to RG1.

39\. You have an Azure virtual machines shown in the following table. You create an Azure Log Analytics workspace named Analytics1 in RG1 in the East US region. Which virtual machines can be enrolled in Analytics1?

![](https://storage.googleapis.com/peopleaps//peopleapspeneraju/1258/Azure-Security-Engineer.PNG?GoogleAccessId=peopleaps-bucket-serivce%40peopleaps-263002.iam.gserviceaccount.com&Expires=1648965748&Signature=U4MGp9X0%2FipWfQ16LHReRRv0QvjW7CKrOXD0tHExDpM3qC%2BahBhPipzznZnKd6MmujGDzGzER4ezzFcnriw%2FyntQvrgrGyUOshSXtbJaY87TOFZH6oWjBgHt6LAIvj4a0WvOQMGKqhu%2BbilpwYw%2BmX8RLyuypI%2BsacsGxt1IcaO74qjAqrSenXoFWjKujzgme0cWtChj2lOvX%2FafQnbfMd54wLfhK2YZR7awYlDTa5d9bZpkG4yfpqzOQ%2Floa1EvvE8vrTYZK3xSow0aM5VaBm2Wc8gVKDLO6FxkXuGZgb1HhRMsHuOHz00eeQYj8UAmtNGpeay0ODO%2FSlisR2EakQ%3D%3D)

(click to enlarge the image)

- [ ]  A. VM1 only

- [ ]  B. VM1, VM2, and VM3 only

- [ ]  C. VM1, VM2, VM3, and VM4

- [ ]  D. VM1 and VM4 only

40\. You have an Azure subscription named Sub1 that is associated to an Azure Active Directory (Azure AD) tenant named contoso.com. You are assigned the Global administrator role for the tenant. You are responsible for managing Azure Security Center settings. You need to create a custom sensitivity label. What should you

- [ ]  A. Create a custom sensitive information type.

- [ ]  B. Elevate access for global administrators in Azure AD.

- [ ]  C. Upgrade the pricing tier of the Security Center to Standard.

- [ ]  D. Enable integration with Microsoft Cloud App Security.

41\. You have been tasked with configuring an access review, which you plan to assigned to a new collection of reviews. You also have to make sure that the reviews can be reviewed by resource owners. You start by creating an access review program and an access review control. You now need to configure the Reviewers. Which of the following should you set Reviewers to?

- [ ]  A. Selected users.

- [ ]  B. Group Owners.

- [ ]  C. Members (Self).

- [ ]  D. Anyone.

42\. Note: This question is part of a series of questions that present the same scenario. Each question in the series contains a unique solution that might meet the stated goals. Some question sets might have more than one correct solution, while others might not have a correct solution. After you answer a question in this section, you will NOT be able to return to rt As a result, these questions will not appear in the review screen. You have an Azure subscription named Sub1. You have an Azure Storage account named Sa1 in a resource group named RG1. Users and applications access the blob service and the file service in Sal by using several shared access signatures {SASs) and stored access policies. You discover that unauthorized users accessed both the rile service and the blob service. You need to revoke all access to Sa1. Solution: You regenerate the access keys. Does this meet the goal?

- [ ]  A. Yes

- [ ]  B. No

43\. Your company uses Azure DevOps. You need to recommend a method to validate whether the code meets the company's quality standards and code review standards. What should you recommend implementing in Azure DevOps?

- [ ]  A. branch folders

- [ ]  B. branch permissions

- [ ]  C. branch policies

- [ ]  D. branch locking

44\. You need to ensure that users can access VM0. The solution must meet the platform protection requirements. What should you do?

- [ ]  A. Move VM0 to Subnet1.

- [ ]  B. On Firewall, configure a network traffic filtering rule.

- [ ]  C. Assign RT1 to AzureFirewallSubnet.

- [ ]  D. On Firewall, configure a DNAT rule.

45\. You are configuring an Azure Kubernetes Service (AKS) cluster that will connect to an Azure Container Registry. You need to use the auto-generated service principal to authenticate to the Azure Container Registry. What should you create?

- [ ]  A. an Azure Active Directory (Azure AD) group

- [ ]  B. an Azure Active Directory (Azure AD) role assignment

- [ ]  C. an Azure Active Directory (Azure AD) user

- [ ]  D. a secret in Azure Key Vault

46\. You need to encrypt storage1 to meet the technical requirements. Which key vaults can you use?

- [ ]  A. KeyVault1 only

- [ ]  B. KeyVault2 and KeyVault3 only

- [ ]  C. KeyVault1 and KeyVault3 only

- [ ]  D. KeyVault1 KeyVault2 and KeyVault3

47\. You have a hybrid configuration of Azure Active Directory (Azure AD). All users have computers that run Windows 10 and are hybrid Azure AD joined. You have an Azure SQL database that is configured to support Azure AD authentication. Database developers must connect to the SQL database by using Microsoft SQL Server Management Studio (SSMS) and authenticate by using their on-premises Active Directory account. You need to tell the developers which authentication method to use to connect to the SQL database from SSMS. The solution must minimize authentication prompts. Which authentication method should you instruct the developers to use?

- [ ]  A. SQL Login

- [ ]  B. Active Directory - Universal with MFA support

- [ ]  C. Active Directory - Integrated

- [ ]  D. Active Directory - Password

48\. You have an Azure subscription named Sub1. In Azure Security Center, you have a workflow automation named WF1. WF1 is configured to send an email message to a user named User1. You need to modify WF1 to send email messages to a distribution group named Alerts. What should you use to modify WF1?

- [ ]  A. Azure Application Insights

- [ ]  B. Azure Monitor

- [ ]  C. Azure Logic Apps Designer

- [ ]  D. Azure DevOps

49\. Your network contains an on-premises Active Directory domain named corp.contoso.com. You have an Azure subscription named Sub1 that is associated to an Azure Active Directory (Azure AD) tenant named contoso.com. You sync all on-premises identities to Azure AD. You need to prevent users who have a givenName attribute that starts with TEST from being synced to Azure AD. The solution must minimize administrative effort. What should you use?

- [ ]  A. Synchronization Rules Editor

- [ ]  B. Web Service Configuration Tool

- [ ]  C. the Azure AD Connect wizard

- [ ]  D. Active Directory Users and Computers

50\. You have an Azure web app named webapp1. You need to configure continuous deployment for webapp1 by using an Azure Repo. What should you create first?

- [ ]  A. an Azure Application Insights service

- [ ]  B. an Azure DevOps organization

- [ ]  C. an Azure Storage account

- [ ]  D. an Azure DevTest Labs lab