# Testing Report

### Security Tests:
1. **Firewall Tests:**
   - NSG rules were tested to ensure only HTTP/HTTPS traffic reaches the WebApp Subnet.
   - Unauthorized traffic attempts were blocked successfully.

2. **VPN Testing:**
   - Connection between simulated on-premises and Azure VNet was tested.
   - Traffic flow validated using ping tests and traceroute.

### Performance Tests:
1. **Load Balancing:**
   - Simulated heavy traffic to test load distribution across VMs in WebApp Subnet.
   - No significant latency or downtime observed.

2. **Private Link Access:**
   - Confirmed that all PaaS services (e.g., Azure SQL Database) are accessible through private endpoints, with no public internet traffic involved.

### Conclusion:
The project successfully simulates a hybrid cloud environment with secure access controls and efficient traffic management.
