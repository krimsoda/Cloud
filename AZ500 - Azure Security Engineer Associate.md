# Study Guide for Exam AZ-500: Microsoft Azure Security Technologies

## Skills Measured as of October 30, 2024

## Audience Profile

As the Azure security engineer, you implement, manage, and monitor security for resources in Azure, multi-cloud, and hybrid environments as part of an end-to-end infrastructure. You recommend security components and configurations to protect the following:

- **Identity and access**
- **Data**
- **Applications**
- **Networks**

### Responsibilities:
Your responsibilities as an Azure security engineer include:

- Managing the security posture.
- Identifying and remediating vulnerabilities.
- Performing threat modelling.
- Implementing threat protection.

You may also participate in responding to security incidents. As an Azure security engineer, you work with architects, administrators, and developers to plan and implement solutions that meet security and compliance requirements.

### You Should Have:

- Practical experience in administration of Microsoft Azure and hybrid environments.
- Strong familiarity with compute, network, and storage in Azure and Microsoft Entra ID.

---

## Skills at a Glance

- **Manage identity and access** (25–30%)
- **Secure networking** (20–25%)
- **Secure compute, storage, and databases** (20–25%)
- **Manage security operations** (25–30%)

 ---
# Manage Identity and Access (25–30%)

## [Manage Microsoft Entra Identities](https://learn.microsoft.com/en-us/training/modules/manage-identities-microsoft-entra-id/)
- Secure Microsoft Entra users
- Secure Microsoft Entra groups
- Recommend when to use external identities
- Secure external identities
- Implement Microsoft Entra ID Protection

## [Manage Microsoft Entra Authentication](https://learn.microsoft.com/en-us/training/modules/manage-authentication-microsoft-entra-id/)
- Implement multi-factor authentication (MFA)
- Configure Microsoft Entra Verified ID
- Implement passwordless authentication
- Implement password protection
- Implement single sign-on (SSO)
- Integrate single sign-on (SSO) and identity providers
- Recommend and enforce modern authentication methods

## [Manage Microsoft Entra Authorization](https://learn.microsoft.com/en-us/training/modules/manage-authorization-microsoft-entra-id/)
- Configure Azure role permissions for management groups, subscriptions, resource groups, and resources  
- Assign Microsoft Entra built-in roles
- Assign Azure built-in roles
- Create and assign custom roles, including Azure roles and Microsoft Entra roles
- Implement and manage Microsoft Entra Permissions Management
- Configure Microsoft Entra Privileged Identity Management
- Configure role management and access reviews in Microsoft Entra
- Implement Conditional Access policies

## [Manage Microsoft Entra Application Access](https://learn.microsoft.com/en-us/training/modules/manage-application-access-microsoft-entra-id/)
- Manage access to enterprise applications in Microsoft Entra ID, including OAuth permission grants  
- Manage Microsoft Entra app registrations
- Configure app registration permission scopes
- Manage app registration permission consent
- Manage and use service principals
- Manage managed identities for Azure resources
- Recommend when to use and configure a Microsoft Entra Application Proxy, including authentication  

---

# Secure Networking (20–25%)

## [Plan and Implement Security for Virtual Networks](https://learn.microsoft.com/en-us/training/modules/security-virtual-networks/)
- Plan and implement Network Security Groups (NSGs) and Application Security Groups (ASGs)  
- Plan and implement user-defined routes (UDRs)
- Plan and implement Virtual Network peering or VPN gateway
- Plan and implement Virtual WAN, including secured virtual hub
- Secure VPN connectivity, including point-to-site and site-to-site
- Implement encryption over ExpressRoute
- Configure firewall settings on PaaS resources
- Monitor network security by using Network Watcher, including NSG flow logging

## [Plan and Implement Security for Private Access to Azure Resources](https://learn.microsoft.com/en-us/training/modules/security-private-access-azure-resources/)
- Plan and implement virtual network Service Endpoints
- Plan and implement Private Endpoints
- Plan and implement Private Link services
- Plan and implement network integration for Azure App Service and Azure Functions  
- Plan and implement network security configurations for an App Service Environment (ASE)  
- Plan and implement network security configurations for an Azure SQL Managed Instance  

## [Plan and Implement Security for Public Access to Azure Resources](https://learn.microsoft.com/en-us/training/modules/security-public-access-azure-resources/)
- Plan and implement Transport Layer Security (TLS) to applications, including Azure App Service and API Management  
- Plan, implement, and manage an Azure Firewall, including Azure Firewall Manager and firewall policies  
- Plan and implement an Azure Application Gateway
- Plan and implement an Azure Front Door, including Content Delivery Network (CDN)  
- Plan and implement a Web Application Firewall (WAF)
- Recommend when to use Azure DDoS Protection Standard

---

# Secure Compute, Storage, and Databases (20–25%)

## [Plan and Implement Advanced Security for Compute](https://learn.microsoft.com/en-us/training/modules/advanced-security-compute/)
- Plan and implement remote access to public endpoints, including Azure Bastion and just-in-time (JIT) virtual machine (VM) access  
- Configure network isolation for Azure Kubernetes Service (AKS)
- Secure and monitor AKS
- Configure authentication for AKS
- Configure security monitoring for Azure Container Instances (ACIs)
- Configure security monitoring for Azure Container Apps (ACAs)
- Manage access to Azure Container Registry (ACR)
- Configure disk encryption, including Azure Disk Encryption (ADE), encryption at host, and confidential disk encryption  
- Recommend security configurations for Azure API Management

## [Plan and Implement Security for Storage](https://learn.microsoft.com/en-us/training/modules/security-storage/)
- Configure access control for storage accounts
- Manage life cycle for storage account access keys
- Select and configure an appropriate method for access to Azure Files
- Select and configure an appropriate method for access to Azure Blob Storage
- Select and configure an appropriate method for access to Azure Tables
- Select and configure an appropriate method for access to Azure Queues
- Select and configure appropriate methods for protecting against data security threats, including soft delete, backups, versioning, and immutable storage  
- Configure Bring Your Own Key (BYOK)
- Enable double encryption at the Azure Storage infrastructure level

## [Plan and Implement Security for Azure SQL Database and Azure SQL Managed Instance](https://learn.microsoft.com/en-us/training/modules/security-azure-sql-database-azure-sql-managed-instance/)
- Enable Microsoft Entra database authentication
- Enable database auditing
- Identify use cases for the Microsoft Purview governance portal
- Implement data classification of sensitive information by using the Microsoft Purview governance portal  
- Plan and implement dynamic masking
- Implement Transparent Data Encryption (TDE)
- Recommend when to use Azure SQL Database Always Encrypted

---

# Manage Security Operations (25–30%)

## [Plan, Implement, and Manage Governance for Security](https://learn.microsoft.com/en-us/training/modules/governance-security/)
- Create, assign, and interpret security policies and initiatives in Azure Policy
- Configure security settings by using Azure Blueprints
- Deploy secure infrastructures by using a landing zone
- Create and configure an Azure Key Vault
- Recommend when to use a dedicated Hardware Security Module (HSM)
- Configure access to Key Vault, including vault access policies and Azure Role-Based Access Control  
- Manage certificates, secrets, and keys
- Configure key rotation
- Configure backup and recovery of certificates, secrets, and keys

## [Manage Security Posture by Using Microsoft Defender for Cloud](https://learn.microsoft.com/en-us/training/modules/microsoft-defender-cloud-security-posture/)
- Identify and remediate security risks by using the Microsoft Defender for Cloud Secure Score and Inventory  
- Assess compliance against security frameworks by using Microsoft Defender for Cloud  
- Add industry and regulatory standards to Microsoft Defender for Cloud
- Add custom initiatives to Microsoft Defender for Cloud
- Connect hybrid cloud and multi-cloud environments to Microsoft Defender for Cloud
- Identify and monitor external assets by using Microsoft Defender External Attack Surface Management  

## [Configure and Manage Threat Protection by Using Microsoft Defender for Cloud](https://learn.microsoft.com/en-us/training/modules/microsoft-defender-cloud-threat-protection/)
- Enable workload protection services in Microsoft Defender for Cloud, including Microsoft Defender for Storage, Databases, Containers, App Service, Key Vault, and Resource Manager  
- Configure Microsoft Defender for Servers
- Configure Microsoft Defender for Azure SQL Database
- Manage and respond to security alerts in Microsoft Defender for Cloud
- Configure workflow automation by using Microsoft Defender for Cloud
- Evaluate vulnerability scans from Microsoft Defender for Server

## [Configure and Manage Security Monitoring and Automation Solutions](https://learn.microsoft.com/en-us/training/modules/security-monitoring-automation-solutions/)
- Monitor security events by using Azure Monitor
- Configure data connectors in Microsoft Sentinel
- Create and customize analytics rules in Microsoft Sentinel
- Evaluate alerts and incidents in Microsoft Sentinel
- Configure automation in Microsoft Sentinel
