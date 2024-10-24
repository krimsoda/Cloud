# Azure
Cloud Concepts
- Cloud Computing Benefits
- Cloud Models (Public, Private, Hybrid)
- Types of Cloud Services (IaaS, PaaS, SaaS)

Core Azure Services
- Azure Regions & Availability Zones
- Core Azure Services (Compute, Storage, Networking)
- Azure Management Tools (Azure Portal, CLI, PowerShell)

Azure Security, Privacy, Compliance, and Trust
- Azure Security Features
- Azure Identity Services (AAD, RBAC, MFA)
- Privacy & Compliance (Azure Trust Center, GDPR)

Azure Pricing and Support
- Azure Pricing Models
- Azure Cost Management
- Azure Support Plans
---
# 1. Cloud Concepts <a name="cloud-concepts"></a>
1.1 Cloud Computing Benefits
- High Availability: Services are available with minimal downtime.
- Scalability: Scale up or down based on demand.
    - Vertical Scaling: Adding more power to an existing machine.
    - Horizontal Scaling: Adding more instances to handle the load.
- Elasticity: Automatic scaling of resources.
- Agility: Quickly provision and deploy resources.
- Disaster Recovery: Automatic backup and failover options.
- Economies of Scale: Reduce costs as you scale.

1.2 Cloud Models
- Public Cloud: Resources are hosted by a third-party cloud provider (e.g., Azure) and shared among multiple organizations.
- Private Cloud: Dedicated cloud infrastructure for a single organization.
- Hybrid Cloud: Combines both public and private clouds, allowing data and applications to be shared between them.

1.3 Types of Cloud Services
- IaaS (Infrastructure as a Service):
    - Virtual machines, storage, networks, and OS.
    - e.g., Azure Virtual Machines, Azure Storage.
- PaaS (Platform as a Service):
    - Focus on app development. Provides platform and tools without managing the underlying infrastructure.
    - e.g., Azure App Services, Azure SQL Database.
- SaaS (Software as a Service):
    - Fully managed applications accessed via the internet.
    - e.g., Microsoft 365, Dynamics 365.
# 2. Core Azure Services <a name="core-azure-services"></a>
2.1 Azure Regions & Availability Zones
Regions: Geographical locations with multiple data centers. Azure has over 60 regions globally.
Availability Zones: Physically separate locations within a region, providing high availability.
Region Pairing: Every Azure region is paired with another region within the same geography.
2.2 Core Azure Services
Compute Services:

Azure Virtual Machines: IaaS service to create and run VMs.
Azure Kubernetes Service (AKS): Managed Kubernetes service.
Azure App Service: PaaS service to host web apps, APIs, and mobile backends.
Storage Services:

Azure Blob Storage: Object storage for unstructured data.
Azure File Storage: Managed file shares in the cloud.
Azure Disk Storage: High-performance disk storage for VMs.
Networking Services:

Virtual Network (VNet): Enables secure communication between Azure resources.
Azure Load Balancer: Distributes incoming traffic across multiple resources.
Azure Application Gateway: Application-level routing and load balancing.
2.3 Azure Management Tools
Azure Portal: Web-based interface for managing all Azure services.
Azure CLI: Command-line tool for managing Azure resources.
Azure PowerShell: Automation and scripting tool using PowerShell cmdlets.
Azure Cloud Shell: Browser-based command-line experience for managing Azure.
# 3. Azure Security, Privacy, Compliance, and Trust <a name="security-privacy-compliance-trust"></a>
3.1 Azure Security Features
Azure Security Center: Unified security management and threat protection.
Azure DDoS Protection: Protects against distributed denial-of-service attacks.
Azure Firewall: Managed cloud-based network security service.
3.2 Azure Identity Services
Azure Active Directory (AAD): Identity and access management service.
Single Sign-On (SSO): Allows users to log in once and access multiple applications.
Multi-Factor Authentication (MFA): Adds an additional layer of security.
Role-Based Access Control (RBAC): Manages access to Azure resources.
3.3 Privacy and Compliance
Azure Trust Center: Provides information about security, privacy, and compliance.
General Data Protection Regulation (GDPR): Compliance regulation in the EU.
Azure Policy: Enforces organizational standards and assesses compliance across resources.
# 4. Azure Pricing and Support <a name="pricing-and-support"></a>
4.1 Azure Pricing Models
Pay-As-You-Go: Pay for what you use with no upfront costs.
Reserved Instances: Pre-purchase resources for 1 or 3 years at a discounted rate.
Spot Pricing: Purchase unused capacity at a discounted rate.
4.2 Azure Cost Management
Azure Cost Management: Tool for monitoring, allocating, and optimizing cloud spend.
Azure Pricing Calculator: Estimate the cost of Azure services based on specific needs.
4.3 Azure Support Plans
Basic Support: Free with access to online documentation and forums.
Developer Support: Best for trial and non-production environments ($29/month).
Standard Support: Production workload support ($100/month).
Professional Direct: Fastest response times and high-level support ($1,000/month).
# Additional Resources
Microsoft Learn - AZ-900 Learning Path
Azure Pricing Calculator
Azure Architecture Center

