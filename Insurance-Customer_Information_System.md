# Insurance Company's Implementation of EXPRESSCLUSTER on Azure: A Case Study

## Customer Challenge

A consulting firm was tasked with migrating an insurance company's customer information system to Azure. The project required ensuring the same level of availability on Azure as the existing system operating in an on-premises environment.

## Solution

The challenge in achieving the desired uptime and disk replication without data loss on Azure was that configurations such as WSFC shared disk cluster configuration and Azure Site Recovery could not be adopted.

After attending a product seminar and learning basic operations, the project team conducted tests in a real environment using the evaluation version and chose 'EXPRESSCLUSTER'.

In this project, the advantage was that they could verify with the evaluation version of 'EXPRESSCLUSTER' and utilize Azure's [storage](https://learn.microsoft.com/ja-jp/azure/virtual-machines/disks-types) that flexibly responds to performance requirements.

## Result

With EXPRESSCLUSTER, they achieved the same availability as on-premises. In addition, while achieving cost reduction through migration to Azure, a 24/7 support system was established, and stable operation continues. As a result, the customer was able to successfully migrate their mission-critical customer information system to the cloud.

The customer has expressed satisfaction, stating, "We are very pleased that we were able to reduce costs while maintaining the same performance and uptime as on-premises."
