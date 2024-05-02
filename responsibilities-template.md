---

copyright:
  years: 2024
lastupdated: "2024-05-02"

subcollection: security-verify

keywords: 

---

{{site.data.keyword.attribute-definition-list}}

# Understanding your responsibilities when using IBM Verify
{: #your-id}

<!-- The title of your H1 should be Understanding your responsibilities with using _service-name_, where _service-name_ is the non-trademarked short version keyref. -->

Learn about the management responsibilities and terms and conditions that you have when you use _yourproduct-full-keyref_. For a high-level view of the service types in {{site.data.keyword.cloud}} and the breakdown of responsibilities between the customer and {{site.data.keyword.IBM_notm}} for each type, see [Shared responsibilities for {{site.data.keyword.cloud_notm}} offerings](/docs/overview?topic=overview-shared-responsibilities).
{: shortdesc}

Review the following sections for the specific responsibilities for you and for {{site.data.keyword.verify_full_notm}} when you use _yourproduct-full-notm-keyref_. For the overall terms of use, see [{{site.data.keyword.cloud}} Terms and Notices](/docs/overview/terms-of-use?topic=overview-terms).

<!-- If you plan to list resource (see resources listed in each table in the platform shared responsibilities topic linked above) responsibility instead of individual tasks, you do not need to include rows for Hypervisor, Physical Servers and memory, Physical storage, Physical network and devices, and Facilities and data centers unless you need to indicate a 'Shared' or 'Customer' responsibility for one of the areas within those Resources. -->

  
## Incident and operations management
{: #incident-and-ops}

<!-- Use this section description exactly as worded. -->
<!-- If there is a task that is the customer's responsibility and you have associated docs for how a customer completes that task, link to it from the Your responsibilities column. -->

Incident and operations management includes tasks such as monitoring, event management, high availability, problem determination, recovery, and full state backup and recovery.

|  | {{site.data.keyword.IBM_notm}} Responsibilities | Your Responsibilities |
|----------|-----------------------|--------|
|Monitoring| {{site.data.keyword.IBM_notm}} is responsible for hosting monitoring and health services.  | The Client is responsible for revising the IBM Security status page to see where they may be affected. |
|High Availability| {{site.data.keyword.IBM_notm}} is responsible for deploying the service across availability zones and multi data centers. Verify provides replication, fail-over features, and infrastructure maintenance or updates. n  | The Client is responsible for designing application logic to connect to communicating with the service, for example, retry logins, create users, and more that may be caused by temporary failures. |
{: row-headers}
{: caption="Table 1. Responsibilites for incident and operations" caption-side="bottom"}
{: summary="The rows are read from left to right. The first column describes the task that the customer or IBM might be responsibility for. The second column describes {{site.data.keyword.IBM_notm}} responsibilities for that task. The third column describes your responsibilities as the customer for that task."}


## Change management
{: #change-management}

<!-- Use this section description exactly as worded. -->
<!-- If there is a task that is the customer's responsibility and you have associated docs for how a customer completes that task, link to it from the Your responsibilities column. -->

Change management includes tasks such as deployment, configuration, upgrades, patching, configuration changes, and deletion.

|  | {{site.data.keyword.IBM_notm}} Responsibilities | Your Responsibilities |
|----------|-----------------------|--------|
|Scaling| {{site.data.keyword.IBM_notm}} is responsible for scaling infrastructure to meet client requests.  | The Client is responsible for configuring the application and ensuring the configuration is properly set up. |
|Feature deployment and installation| {{site.data.keyword.IBM_notm}} is responsible for deploying new features into the customer environment.  | The Client is responsible for configuring and setting up the newly added features as desired to use. What’s new can be found in the Verify documentation. |
{: row-headers}
{: caption="Table 2. Responsibilites for change management" caption-side="bottom"}
{: summary="The rows are read from left to right. The first column describes the task that the customer or IBM might be responsibility for. The second column describes {{site.data.keyword.IBM_notm}} responsibilities for that task. The third column describes your responsibilities as the customer for that task."}


## Identity and access management
{: #iam-responsibilities}

<!-- Use this section description exactly as worded. -->
<!-- If there is a task that is the customer's responsibility and you have associated docs for how a customer completes that task, link to it from the Your responsibilities column. -->

Identity and access management includes tasks such as authentication, authorization, access control policies, and approving, granting, and revoking access.

|  | {{site.data.keyword.IBM_notm}} Responsibilities | Your Responsibilities |
|----------|-----------------------|--------|
|Task 1| {{site.data.keyword.IBM_notm}} responsibility description  | Customer responsibility description |
|Task 2| {{site.data.keyword.IBM_notm}} responsibility description  | Customer responsibility description |
|Task 3| {{site.data.keyword.IBM_notm}} responsibility description  | Customer responsibility description |
{: row-headers}
{: caption="Table 3. Responsibilites for identity and access management" caption-side="bottom"}
{: summary="The rows are read from left to right. The first column describes the task that the customer or IBM might be responsibility for. The second column describes {{site.data.keyword.IBM_notm}} responsibilities for that task. The third column describes your responsibilities as the customer for that task."}

## Security and regulation compliance
{: #security-compliance}

<!-- Use this section description exactly as worded. -->
<!-- If there is a task that is the customer's responsibility and you have associated docs for how a customer completes that task, link to it from the Your responsibilities column. -->

Security and regulation compliance includes tasks such as security controls implementation and compliance certification.

|  | {{site.data.keyword.IBM_notm}} Responsibilities | Your Responsibilities |
|----------|-----------------------|--------|
N/A |
|Security| {{site.data.keyword.IBM_notm}}  is responsible for ensuring the security of data and operations. This can be seen in the IBM Security Verify data sheet.  | The Client is responsible for managing the account profiles, applications, and other aspects when configuring the service. |
|Compliance| {{site.data.keyword.IBM_notm}}  is responsible for ensuring adherence, auditing, and certification of compliances listed in the IBM Security Verify data sheet.  | The Client is responsible as the Data Controller. |
{: row-headers}
{: caption="Table 4. Responsibilites for security and regulation compliance" caption-side="bottom"}
{: summary="The rows are read from left to right. The first column describes the task that the customer or IBM might be responsibility for. The second column describes {{site.data.keyword.IBM_notm}} responsibilities for that task. The third column describes your responsibilities as the customer for that task."}

## Disaster recovery
{: #disaster-recovery}

<!-- Use this section description exactly as worded. -->
<!-- If there is a task that is the customer's responsibility and you have associated docs for how a customer completes that task, link to it from the Your responsibilities column. -->

Disaster recovery includes tasks such as providing dependencies on disaster recovery sites, provision disaster recovery environments, data and configuration backup, replicating data and configuration to the disaster recovery environment, and failover on disaster events.

|  | {{site.data.keyword.IBM_notm}} Responsibilities | Your Responsibilities |
|----------|-----------------------|--------|
|Backups and restore| {{site.data.keyword.IBM_notm}} is responsible for automatic daily backups, as well as monitoring the state of client backups. This can be seen in the IBM Security Verify data sheet.  | N/A |

{: row-headers}
{: caption="Table 5. Responsibilites for disaster recovery" caption-side="bottom"}
{: summary="The rows are read from left to right. The first column describes the task that the customer or IBM might be responsibility for. The second column describes {{site.data.keyword.IBM_notm}} responsibilities for that task. The third column describes your responsibilities as the customer for that task."}
