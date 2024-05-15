---

copyright:
  years: 2024
lastupdated: "2024-05-14"

subcollection: security-verify

keywords: 

---

{{site.data.keyword.attribute-definition-list}}

# Managing your service instance
{: #tenant-management}

An {{site.data.keyword.verify_full_notm}} instance is a logically separated environment, where each instance is its own unique environment running in a multi-tenant SaaS operational model. 

You can create multiple {{site.data.keyword.verify_full_notm}} instances per IBM Cloud account. These instances are created with the defined capabilities corresponding to each of the plans. 

## Creating a service instance
{: #create-instance}
Create {{site.data.keyword.verify_full_notm}} instances to use when protecting consumer and workforce identities. 
See [Getting Started](/docs/security-verify?topic=security-verify-get-started#create).

## Deleting a service instance
{: #delete-instance}
The delete action will trigger {{site.data.keyword.verify_full_notm}} to suspend the instance for 7 days, which allows for recovery of data if the service instance is accidentally deleted. 
If an instance is accidentally deleted and needs to be recovered, reach out to IBM Cloud support for assistance before the 7 days window is over.
The service instance will be deleted and data cannot be recovered after the 7 days window.

1. In the IBM Cloud Catalog Resource list page, search your service instance.
2. Click the Actions icon and select Delete. You are prompted to confirm the delete action. Note: Deleting the service removes it from all connected apps and deletes all aliases from spaces that are using it. In addition, all of its data is permanently deleted. 
3. Click Delete. The {{site.data.keyword.verify_full_notm}} instance is removed from the resource list and {{site.data.keyword.verify_full_notm}} sends an email notification that your service instance account is suspended.

## Upgrading a service instance
{: #upgrade-instance}
Upgrading {{site.data.keyword.verify_full_notm}} with additional capabilities beyond what is provided in the “Lite” plan requires engagement with an IBM Security or IBM Cloud representative. 

1. In the IBM Cloud Catalog Resource list page, search and click your service instance. 
2. Click Open dashboard to launch {{site.data.keyword.verify_full_notm}}.
3. Sign in with your IBMid account.
4. In the {{site.data.keyword.verify_full_notm}} Admin page, click Request upgrade or demo.
5. Complete the IBM Registration form with your contact details. IBM representatives will reach out to you within the next few days.
