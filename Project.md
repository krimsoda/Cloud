
# Microsoft Entra ID Notes

## Overview
- **Microsoft Entra ID** is not a cloud version of Windows Server Active Directory (AD) nor a complete replacement for on-premises AD.
- It can extend an on-premises AD into Azure, allowing users to use the same credentials for local and cloud resources.
- Smaller companies can use it independently as their sole directory service for applications and SaaS products like Microsoft 365, Salesforce, and Dropbox.
- Local Windows machines authenticate using local credentials, but Microsoft Entra ID can centralize authentication for apps.

## Key Features
### Integration with Other Services
- Used to identify users and control access to:
  - Microsoft Azure
  - Microsoft 365
  - Microsoft Intune
  - Microsoft Dynamics 365

### Directories and Tenants
- When a company signs up for a Microsoft service, they're assigned a **default directory**, an instance of Microsoft Entra ID.
- This directory (tenant) holds users and groups with access to purchased services.
- A **tenant** represents an organization and its default directory.

### Subscriptions
- A subscription in Azure acts as both a billing entity and a security boundary.
- Resources (e.g., VMs, databases) are associated with a single subscription.
- A subscription:
  - Is associated with one Microsoft Entra directory.
  - Can have multiple subscriptions trusting the same directory.
  - Allows users and groups to access resources in multiple subscriptions.

### Managing Multiple Directories
- Users can switch between directories in the Azure portal using the **Directory + Subscription** button.
- Default filters and directories can be configured for easier navigation.

## Creating a New Directory
### Requirements
- Owners of Azure accounts can create new directories.
- Azure Sandbox doesn't allow creating new directories.

### Steps
1. **Sign in** to the Azure portal.
2. On the home page, under **Azure services**, select **Create a resource**.
3. In the left menu, select **Identity** and search for **Microsoft Entra ID**.
4. Select **Create**.
5. Configure settings:
   - **Organization Name**: Distinct name for the directory.
   - **Initial Domain Name**: Domain with the suffix `.onmicrosoft.com`. Custom domains can be added later.
   - **Country/Region**: Select where the directory will reside. Cannot be changed later.
6. Select **Create** to finalize.
7. Access the new directory from the **Overview dashboard**.

### Free Tier Directory
- After creation, users can:
  - Add users and roles.
  - Register apps and devices.
  - Manage licenses.

---
### Primary Elements: Users
- Microsoft Entra ID provides comprehensive tools to manage user authentication and access control.
