# Step 6: Secure Administrative Access with Azure Bastion

## Overview:
Utilized Azure Bastion to securely access virtual machines without exposing public IPs or using external RDP/SSH connections.

### Steps:
1. **Deploy Azure Bastion**:
   - In the Azure portal, I navigated to `Create a Resource` > `Networking` > `Azure Bastion`.
2. **Connect to VMs**:
   - I used Bastion to connect to VMs in the WebApp, Database, and Admin subnets securely.
