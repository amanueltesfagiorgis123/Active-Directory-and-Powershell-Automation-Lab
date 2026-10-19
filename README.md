# 💻 Active-Directory-and-Powershell-Automation-Lab 💻
# Overview 
## Discover a production-ready lab configuration  demonstrating the deployment and configuration of core enterprise IT infrastructure. This documentation walks through building a Windows Server 2022 AD DC, setting up DHCP and NAT-based Remote Access, bulk-managing users with PowerShell scripts, and successfully joining a Windows 11 client to the domain, with a strong emphasis on security and operational efficiency.
# Network Topology 
```mermaid
graph TD
    A[Internet] --> B[Windows Server 2022 - NAT]
    B --> C[Windows Server 2022 - AD DC]
    C --> D[Windows 10 Client]
