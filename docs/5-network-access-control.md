# Step 5: Network Access Control with NSGs

## Overview:
Implemented Network Security Groups (NSGs) to control inbound and outbound traffic to the various subnets, ensuring only necessary traffic could reach specific resources.

### Steps:
1. **Create NSGs for Each Subnet**:
   - Created NSGs for the WebApp Subnet, Database Subnet, and Admin Subnet.
2. **Configure Inbound/Outbound Rules**:
   - Allowed only HTTP/HTTPS traffic to the WebApp Subnet.
   - Restricted the Database Subnet to only accept traffic from the WebApp Subnet.
   - Allowed RDP/SSH access to the Admin Subnet for administrative purposes.
