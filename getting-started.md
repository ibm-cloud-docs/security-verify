---

copyright:
  years: 2024
lastupdated: "2024-05-08"

keywords: 

subcollection: 

content-type: tutorial
services: # Getting started tutorials tend to be only for the service, so leave empty.
account-plan: lite # Specify 'lite' if tutorial can be completed using only Lite plan of your service; otherwise, specify 'paid'
completion-time: 10m # Estimated time to complete the steps in this tutorial. Minute values are supported up to 90 minutes. Whole hours are also supported; for example: 2h

---

{{site.data.keyword.attribute-definition-list}}

<!-- Name your file `getting-started.md` and include it in the Get started nav group in your toc.yaml file. -->


# Getting started with IBM Verify
{: #getting-started}
{: toc-content-type="tutorial"} <!-- Always use this value -->
{: toc-services=""} <!-- Use same value from services metadata above - that is, in most cases, leave empty. -->
{: toc-completion-time="10m"} <!-- Use same value from completion-time metadata above -->

<!-- The title of your H1 should be Getting started with _service-name_, where _service-name_ is the non-trademarked short version keyref. -->

<!-- The goal should be a tutorial of 10 minutes or less. -->

_The short description should be a single, concise paragraph that contains one or two sentences and no more than 50 words. Briefly mention what the user's learning goal is and include the following SEO keywords in the title short description: IBM Cloud, ServiceName, tutorial. If the release phase of your service is experimental or beta, be sure to indicate that in the first occurrence of the service name, for example, Cost and Asset Management (Experimental)._ For example: "In this getting started tutorial, we'll take you through a sample node.js ToDo app that will take you about 10 minutes to deploy."
{: shortdesc}

## _Provisioning a Tenant_
{: #anchor_value}
{: step}

1. From the Catalog, search for {{site.data.keyword.verify_full_notm}}.
2. Select a location.
3. Configure your resource. Complete the following fields:

|  Field | Description |
|----------|-----------------------|
|Service Name| description |
|Resource Group| description |
|Tags| description |
|Access Management Tag| description |
|Short hostname| description |
{: row-headers}
{: caption="Table 3. Responsibilites for identity and access management" caption-side="bottom"}
{: summary="The rows are read from left to right. The first column describes the task that the customer or IBM might be responsibility for. The second column describes {{site.data.keyword.verify_full_notm}} responsibilities for that task. The third column describes your responsibilities as the customer for that task."}

4. Select the check box to Confirm that you read and agree to the Terms / License agreements.	
5. Click Create
6. Click open dashboard to launch ISV.
7. Select the check box to Confirm that you read and agree to the Terms and Conditions and click Continue.	


## _Connect a sample application_
{: #anchor_value}
{: step}
See https://docs.verify.ibm.com/verify/docs/getting-started-connect-a-sample-application.

## _Connect to an active directory_
{: #anchor_value}
{: step}
See https://docs.verify.ibm.com/verify/docs/connect-to-active-directory.

## _Use a social provider as an identity source_
{: #anchor_value}
{: step}
See https://docs.verify.ibm.com/verify/docs/identity-sources-1-connect-social-providers
{: tip}

_You can have multiple "tips" per step. Each tip will output with a *Tip:* label and be formatted in a nested, styled box._

## Next steps
{: #anchor_value}

_What's the single thing the user needs to do next? Think "guided journey." Either provide information that leads the user to production use, for example HA, how to make a service secure, or how to connect to on-premise data. Or you can point the user to another tutorial. Give a choice between two options max._
