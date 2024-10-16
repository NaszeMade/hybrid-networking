# Step 2: On-Premises Network Simulation

## Overview:
To simulate an on-premises environment, I created a separate Azure Virtual Network (VNet) that acts as the "on-premises" network.

### Steps:
1. **Navigate to Azure Portal**:
   - Go to `Create a Resource` > `Networking` > `Virtual Network`.
2. **Choose a Different Region or Same Region**:
   - I chose to simulate the on-premises environment in the same region for simplicity. However, this could be deployed in another region to simulate real-world scenarios.
3. **Configure Subnets**:
   - Created subnets to represent internal services on-prem.
4. **Review & Create**:
   - Created the "on-premises" network.

### Screenshot:
![On-Prem Network](../images/onprem-network.png)
