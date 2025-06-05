#Microsoft Azure SOC and HoneyNet



Summary
For this project, I designed and deployed a HoneyNet and Security Operations Center (SOC) in Microsoft Azure. To achieve this, I provisioned all essential cloud infrastructure components, including virtual machines, flow logs for each VM, a log analytics workspace to collect and analyze log data, a key vault, a storage account, virtual networks (VNETs), network security groups, and a security information and event management (SIEM) system—Azure Sentinel.

Once the environment was set up, I initially left the resources exposed to the internet for 24 hours to gather attack data. After this observation period, the infrastructure was hardened and monitored for an additional 24 hours. Finally, I collected and analyzed log data, compiling the results into a spreadsheet to illustrate the change in traffic patterns following the hardening process.
