# Personal Project: Azure Cloud Environment Setup and Security Implementation

## Project Overview
This project demonstrates my ability to design, implement, and secure a cloud environment using Microsoft Azure. It showcases skills in Azure fundamentals, resource management, and security best practices, aligning with my AZ-900 and SC-900 certifications.

## Objectives
- Deploy and configure an Azure cloud environment.
- Implement basic cloud services such as virtual machines, storage, and networking.
- Apply security measures to protect the cloud environment.
- Document the process for learning and presentation purposes.

## Prerequisites
- Azure free-tier account.
- Basic understanding of Azure services (certified with AZ-900 and SC-900).
- Access to Azure Portal and CLI.

---

## Project Plan

### Step 1: Environment Setup
1. **Create a Resource Group:**
   - Use Azure Portal or CLI to create a new resource group (e.g., `RG-CloudProject`).
   ```bash
   az group create --name RG-CloudProject --location eastus
   ```

2. **Deploy a Virtual Network (VNet):**
   - Create a VNet with subnets for secure communication between resources.
   ```bash
   az network vnet create \
       --resource-group RG-CloudProject \
       --name VNet-CloudProject \
       --address-prefix 10.0.0.0/16 \
       --subnet-name Subnet1 \
       --subnet-prefix 10.0.1.0/24
   ```

3. **Provision a Virtual Machine (VM):**
   - Deploy a Linux-based VM for hosting applications or workloads.
   ```bash
   az vm create \
       --resource-group RG-CloudProject \
       --name VM-CloudProject \
       --image UbuntuLTS \
       --admin-username azureuser \
       --generate-ssh-keys
   ```

4. **Set Up Azure Storage:**
   - Create a storage account for data storage and backups.
   ```bash
   az storage account create \
       --name storagecloudproj \
       --resource-group RG-CloudProject \
       --location eastus \
       --sku Standard_LRS
   ```

---

### Step 2: Security Implementation
1. **Enable Network Security Groups (NSGs):**
   - Attach NSGs to subnets and VMs to control inbound and outbound traffic.
   ```bash
   az network nsg create \
       --resource-group RG-CloudProject \
       --name NSG-CloudProject
   ```

2. **Configure Role-Based Access Control (RBAC):**
   - Assign least-privilege roles to users.
   ```bash
   az role assignment create \
       --assignee user@example.com \
       --role Contributor \
       --scope /subscriptions/{subscriptionId}/resourceGroups/RG-CloudProject
   ```

3. **Enable Azure Security Center:**
   - Activate Security Center for continuous security assessment.
   ```bash
   az security pricing create \
       --resource-group RG-CloudProject \
       --tier Standard
   ```

4. **Implement Azure Defender:**
   - Enable Defender for Servers to protect the VM.
   ```bash
   az security auto-provisioning-setting update \
       --auto-provision All
   ```

---

### Step 3: Monitoring and Logging
1. **Enable Azure Monitor:**
   - Configure monitoring for the VM and storage account.
   ```bash
   az monitor log-analytics workspace create \
       --resource-group RG-CloudProject \
       --workspace-name LogAnalyticsWorkspace
   ```

2. **Set Up Alerts:**
   - Create alerts for unusual activity or resource utilization thresholds.

3. **Integrate with Azure Sentinel:**
   - Connect the environment to Azure Sentinel for advanced threat detection.

---

### Step 4: Documentation and Presentation
1. **Document the Project:**
   - Create detailed steps, screenshots, and configurations in a report.

2. **Publish the Project:**
   - Upload configurations and documentation to GitHub or a personal portfolio.

3. **Create a Presentation:**
   - Prepare slides to present the project to potential employers.

---

## Outcomes
- A functional and secure Azure cloud environment.
- Improved understanding of Azure services and security.
- Demonstrated ability to implement and document a technical project.

---

## Future Improvements
- Add automation using Azure Resource Manager (ARM) templates or Terraform.
- Expand the project to include additional services like Azure Functions or Kubernetes.
- Integrate with third-party security tools for enhanced protection.

---

## Resources
- [Microsoft Learn](https://learn.microsoft.com/)
- [Azure CLI Documentation](https://learn.microsoft.com/en-us/cli/azure/)
- [Azure Security Best Practices](https://learn.microsoft.com/en-us/azure/security/fundamentals/best-practices)
