# Tenant Management

An {{site.data.keyword.verify_full_notm}} instance is a logically separated environment, where each instance is its own unique environment running in a multi-tenant SaaS operational model. 

You can create multiple {{site.data.keyword.verify_full_notm}} instances per IBM Cloud account. These instances are created with the defined capabilities corresponding to each of the plans. 

## Creating a service instance
Create {{site.data.keyword.verify_full_notm}} instances to use when protecting consumer and workforce identities. 
See [Getting Started](getting-started.md).

## Deleting a service instance
Delete will suspend the instance for 7 days, which allows for recovery of data if the service instance is accidentally deleted. 
If an instance is accidentally deleted and needs to be recovered, reach out to IBM Cloud support for assistance before the 7 days window is over.
The service instance will be deleted and data cannot be recovered after the 7 days window.

1. In the IBM Cloud Catalog Resource list page, search your service instance.
2. Click the context-menu and select Delete.
3. The instance should  be removed from  their list of resources 
4. ISV should get a request to suspend the tenant; isv suspends the tenant and sends an email to the contact (the person that provisioned the instance)
5. After 7 days, ISV should get a request from IBM Cloud to deprovsion/delete the tenant.  Again, ISV will send an email

## Upgrading a service instance
Upgrading {{site.data.keyword.verify_full_notm}} with additional capabilities beyond what is provided in the “Lite” plan requires engagement with an IBM Security or IBM Cloud representative. 

1. In the IBM Cloud Catalog Resource list page, search and click your service instance. 
2. Click Open dashboard to launch {{site.data.keyword.verify_full_notm}}.
3. Sign in with your IBMid account.
4. In the {{site.data.keyword.verify_full_notm}} Admin page, click Upgrade now.
5. Complete the form with your contact details. IBM representatives will reach out to you within the next few days.
