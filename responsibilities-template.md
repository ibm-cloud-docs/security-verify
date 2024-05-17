---

copyright:
  years: 2024
lastupdated: "2024-05-17"

subcollection: security-verify

keywords: 

---

{{site.data.keyword.attribute-definition-list}}

# Understanding your responsibilities when using {{site.data.keyword.verify_full_notm}}
{: #responsibilities}

Learn about the management responsibilities and terms and conditions that you have when you use {{site.data.keyword.verify_full}}. For a high-level view of the service types in {{site.data.keyword.cloud}} and the breakdown of responsibilities between the customer and {{site.data.keyword.verify_full_notm}} for each type, see [Shared responsibilities for {{site.data.keyword.cloud_notm}} offerings](/docs/overview?topic=overview-shared-responsibilities).
{: shortdesc}

Review the following sections for the specific responsibilities for you and for {{site.data.keyword.verify_full_notm}} when you use {{site.data.keyword.verify_full_notm}}. For the overall terms of use, see [{{site.data.keyword.cloud}} Terms and Notices](/docs/overview?topic=overview-terms){: external}.
  
## Incident and operations management
{: #incident-and-ops}

Incident and operations management includes tasks such as monitoring, event management, high availability, problem determination, recovery, and full state backup and recovery.

|  | {{site.data.keyword.verify_full_notm}} Responsibilities | Your Responsibilities |
|----------|-----------------------|--------|
|Monitoring| {{site.data.keyword.verify_full_notm}} is responsible for hosting monitoring and health services.  | The Client is responsible for visiting the [IBM Security status page](https://statuspage.ibmcloudsecurity.com/#){: external} to see where they may be affected. |
|High Availability| {{site.data.keyword.verify_full_notm}} is responsible for deploying the service across availability zones and multi data centers. {{site.data.keyword.verify_short}} provides replication, fail-over features, and infrastructure maintenance or updates. | The Client is responsible for designing application logic to connect to communicating with the service, for example, retry logins, create users, and more that may be caused by temporary failures. |
{: row-headers}
{: caption="Table 1. Responsibilities for incident and operations" caption-side="bottom"}
{: summary="The rows are read from left to right. The first column describes the task that the customer or IBM might be responsibility for. The second column describes {{site.data.keyword.verify_full_notm}} responsibilities for that task. The third column describes your responsibilities as the customer for that task."}


## Change management
{: #change-management}

Change management includes tasks such as deployment, configuration, upgrades, patching, configuration changes, and deletion.

|  | {{site.data.keyword.verify_full_notm}} Responsibilities | Your Responsibilities |
|----------|-----------------------|--------|
|Scaling| {{site.data.keyword.verify_full_notm}} is responsible for scaling infrastructure to meet client requests.  | The Client is responsible for properly configuring the application. |
|Feature deployment and installation| {{site.data.keyword.verify_full_notm}} is responsible for deploying new features into the customer environment.  | The Client is responsible for configuring and setting up the newly added features as desired to use. [What’s new](https://www.ibm.com/docs/en/security-verify?topic=overview-whats-new){: external} can be found in the {{site.data.keyword.verify_full_notm}} documentation. |
{: row-headers}
{: caption="Table 2. Responsibilities for change management" caption-side="bottom"}
{: summary="The rows are read from left to right. The first column describes the task that the customer or IBM might be responsibility for. The second column describes {{site.data.keyword.verify_full_notm}} responsibilities for that task. The third column describes your responsibilities as the customer for that task."}

## Security and regulation compliance
{: #security-compliance}

Security and regulation compliance includes tasks such as security controls implementation and compliance certification.

|  | {{site.data.keyword.verify_full_notm}} Responsibilities | Your Responsibilities |
|----------|-----------------------|--------|
|Encryption| {{site.data.keyword.verify_full_notm}} is responsible for the encryption of data in motion and rest. This is defined in the [{{site.data.keyword.verify_full_notm}} data sheet](https://www.ibm.com/software/reports/compatibility/clarity-reports/report/html/softwareReqsForProduct?deliverableId=735E5650E26711E69CCD7F0385C6524D){: external}.  | N/A |
|Security| {{site.data.keyword.verify_full_notm}}  is responsible for the security of data and operations. This can be seen in the [{{site.data.keyword.verify_full_notm}} data sheet](https://www.ibm.com/software/reports/compatibility/clarity-reports/report/html/softwareReqsForProduct?deliverableId=735E5650E26711E69CCD7F0385C6524D){: external}.  | The Client is responsible for managing the account profiles, applications, and other aspects when configuring the service. |
|Compliance| {{site.data.keyword.verify_full_notm}}  is responsible for ensuring adherence, auditing, and certification of compliance listed in the [{{site.data.keyword.verify_full_notm}} data sheet](https://www.ibm.com/software/reports/compatibility/clarity-reports/report/html/softwareReqsForProduct?deliverableId=735E5650E26711E69CCD7F0385C6524D){: external}.  | The Client is responsible as the Data Controller. |
{: row-headers}
{: caption="Table 4. Responsibilites for security and regulation compliance" caption-side="bottom"}
{: summary="The rows are read from left to right. The first column describes the task that the customer or IBM might be responsibility for. The second column describes {{site.data.keyword.verify_full_notm}} responsibilities for that task. The third column describes your responsibilities as the customer for that task."}

## Disaster recovery
{: #disaster-recovery}

Disaster recovery includes tasks such as providing dependencies on disaster recovery sites, provision disaster recovery environments, data and configuration backup, replicating data and configuration to the disaster recovery environment, and failover on disaster events.

|  | {{site.data.keyword.verify_full_notm}} Responsibilities | Your Responsibilities |
|----------|-----------------------|--------|
|Backups and restore| {{site.data.keyword.verify_full_notm}} is responsible for automatic daily backups, as well as monitoring the state of client backups. This can be seen in the [{{site.data.keyword.verify_full_notm}} data sheet](https://www.ibm.com/software/reports/compatibility/clarity-reports/report/html/softwareReqsForProduct?deliverableId=735E5650E26711E69CCD7F0385C6524D){: external}.  | N/A |
{: row-headers}
{: caption="Table 5. Responsibilites for disaster recovery" caption-side="bottom"}
{: summary="The rows are read from left to right. The first column describes the task that the customer or IBM might be responsibility for. The second column describes {{site.data.keyword.verify_full_notm}} responsibilities for that task. The third column describes your responsibilities as the customer for that task."}
