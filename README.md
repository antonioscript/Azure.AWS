# Azure.AWS
Azure.AWS is a comparative guide that highlights the key differences and similarities between Microsoft Azure and Amazon Web Services (AWS)

# Compare AWS and Azure accounts

## Managing account hierarchy

A typical AWS environment uses an organizational structure like the one in the following diagram. There's an **organization** root and optionally a dedicated AWS **management account**. Below the root are **organizational units** that can be used to apply different policies to different accounts. AWS resources often use an AWS account as a logical and billing boundary.

- **Organization**
- **Organization Units**
- **AWS accounts**
- **Resources**

![image](https://github.com/user-attachments/assets/7a634a7c-2fda-45b6-96ca-4f29321e9ee1)

---
An Azure structure looks similar, but, rather than a dedicated management account, it provides administrative permissions on the **tenant**. This design eliminates the need for an entire account just for management. Unlike AWS, Azure uses **resource groups** as a fundamental unit. Resources must be assigned to resource groups, and permissions can be applied at the resource-group level.

- **Tenant**
- **Management Groups**
- **Subscriptions**
- **Resources**

## AWS management account vs. Azure tenant

In Azure, when you create an Azure account, a **Microsoft Entra tenant** is created. You can manage your users, groups, and applications in this **tenant**. Azure subscriptions are created under the tenant. A Microsoft Entra tenant provides identity and access management. It helps ensure that authenticated and authorized users can access only the resources for which they have permissions. 



![image](https://github.com/user-attachments/assets/cbc68fc1-8f34-43ff-b699-1dd7d4def892)


https://learn.microsoft.com/en-us/azure/architecture/aws-professional/accounts

---

# Regions and zones on Azure



https://learn.microsoft.com/en-us/azure/architecture/aws-professional/regions-zones

-------

# Compare AWS and Azure networking options

## Azure virtual networks and AWS VPCs




https://learn.microsoft.com/en-us/azure/architecture/aws-professional/networking

----

# References

https://learn.microsoft.com/en-us/azure/architecture/aws-professional/

https://learn.microsoft.com/en-us/azure/architecture/aws-professional/accounts

https://learn.microsoft.com/en-us/azure/architecture/aws-professional/regions-zones

https://learn.microsoft.com/en-us/azure/architecture/aws-professional/networking
