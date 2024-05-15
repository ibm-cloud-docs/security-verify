---

copyright:
  years: 2024
lastupdated: "2024-05-14"

subcollection: security-verify

keywords: 

content-type: tutorial
services: # Getting started tutorials tend to be only for the service, so leave empty.
account-plan: lite # Specify 'lite' if tutorial can be completed using only Lite plan of your service; otherwise, specify 'paid'
completion-time: 10m # Estimated time to complete the steps in this tutorial. Minute values are supported up to 90 minutes. Whole hours are also supported; for example: 2h

---

{{site.data.keyword.attribute-definition-list}}

<!-- Name your file `getting-started.md` and include it in the Get started nav group in your toc.yaml file. -->


# Getting started with {{site.data.keyword.verify_full_notm}}
{: #get-started}

<!-- The title of your H1 should be Getting started with _service-name_, where _service-name_ is the non-trademarked short version keyref. -->
In order to take advantage of what {{site.data.keyword.verify_full_notm}} has to offer, you need your own instance. 
In minutes, you can:
- Add your first applications to single sign-on (SSO)
- Try out adaptive MFA across applications
- Connect an existing directory or add new users for authentication
- Provision user accounts to target systems
- Create certification campaigns on sensitive applications and much more!

{: shortdesc}

## Create a service instance
{: #create}
{: step}

1. In the IBM Cloud Catalog, search and select {{site.data.keyword.verify_full_notm}}. The service configuration screen opens.
2. Configure your resource. Complete the following fields:

|  Field | Description |
|----------|-----------------------|
|Service name| Give your service instance a name, or use the preset name. |
|Tags| This is optional. Use tags to organize, track usage costs, and even manage access to your resources and service IDs. You can tag related resources and view them throughout your account by filtering by tags from your resource list. See https://cloud.ibm.com/docs/account?topic=account-tag&interface=ui|
|Access Management Tag| Access management tags are metadata that are added to resources to help organize access control relationships. They create flexible and easy to administer resource groupings. When you use tags to control access to your resources, your team's projects can grow without requiring updates to IAM policies. See https://cloud.ibm.com/docs/account?topic=account-access-tags-tutorial. |
|Hostname| This will the name assigned to your tenant. It must be a unique DNS hostname. Choose a hostname that represents your organization for easy access.|
{: row-headers}
{: caption="Table 3. Responsibilities for identity and access management" caption-side="bottom"}
{: summary="The rows are read from left to right. The first column describes the task that the customer or IBM might be responsibility for. The second column describes {{site.data.keyword.verify_full_notm}} responsibilities for that task. The third column describes your responsibilities as the customer for that task."}

4. Select the check box to confirm that you have read and agree to the Terms / License Agreements.	
5. Click Create. The service account is created and you will receive an email notification about your subscription.

## Sign-in to your Service instance
{: #sign-in}
{: step}

1. Click Open dashboard to launch {{site.data.keyword.verify_full_notm}}.
2. Sign in with your IBMid account.
3. For the initial log-in, you are required to enroll a device to secure your account.
4. Set up IBMid multifactor authentication with your preferred method. Follow the screen instructions.


## Connect a sample application
{: #connect-app}
{: step}
1. Create a new application.
2. Gather information for the service provider (application).
3. Configure the sample app.
4. Configure {{site.data.keyword.verify_full_notm}}.
5. Test your sample application.

For more details, see [Connect a sample application](https://docs.verify.ibm.com/verify/docs/getting-started-connect-a-sample-application){: external}.

## Connect to an active directory
{: #connect-activedirectory}
{: step}
1. Gather the information. 
2. Create an Identity Agent configuration.
3. Retrieve API Credentials.
4. Install the IBM Verify Bridge.
5. Validate the configuration.

For more details, see [Connect to Active Directory](https://docs.verify.ibm.com/verify/docs/connect-to-active-directory){: external}.

## Use a social provider as an identity source
{: #identity-source}
{: step}
1. Configure the social providers.
2. Enable an application for social sign-on.

For more details, see [Using social providers](https://docs.verify.ibm.com/verify/docs/identity-sources-1-connect-social-providers){: external}.

