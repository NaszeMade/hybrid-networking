# Step 1: Azure Virtual Network Setup

## Overview:
In this step, I provisioned an Azure Virtual Network (VNet) in my chosen region. The VNet forms the foundation of the network architecture, allowing different resources to communicate securely. 

### Subnets Created:
- **WebApp Subnet**: For deploying the web server.
- **Database Subnet**: For deploying the database server.
- **Admin Subnet**: For secure administrative access.

### Steps:
1. **Navigate to the Azure portal**: 
   - Go to `Create a Resource` > `Networking` > `Virtual Network`.
2. **Choose the Region**:
   - I selected a region close to my end-users for better performance.
3. **Configure Subnets**:
   - Created multiple subnets within the VNet to isolate resources. Each subnet is assigned a different address space (ex: 10.0.0.0/24 for the WebApp Subnet).
4. **Review & Create**: 
   - I reviewed the settings and created the VNet.
   
### Screenshot:
![VNet Setup](../images/vnet-setup.png)
