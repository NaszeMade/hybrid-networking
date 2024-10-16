# Step 3: Secure Connectivity with Azure VPN Gateway

## Overview:
This step connects the simulated on-premises VNet to the Azure VNet using a Site-to-Site VPN, ensuring secure communication between the two networks.

### Steps:
1. **Create a VPN Gateway in Azure**:
   - Go to `Create a Resource` > `Networking` > `VPN Gateway`.
2. **Choose the VNet**:
   - I selected the main Azure VNet (the one where the web and database resources reside) to act as the gateway.
3. **Configure the VPN Connection**:
   - I set up a VPN connection between the simulated on-premises VNet and the Azure VNet.
   - **Connection Type**: Site-to-Site
4. **Configure Local Network Gateway**:
   - Created the local network gateway to represent the on-premises VNet.
5. **Establish the Connection**:
   - Configured the site-to-site VPN connection, ensuring that the two VNets can communicate securely.

### Verification:
- I verified the connection by pinging resources across VNets.
