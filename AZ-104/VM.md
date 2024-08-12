# VM Abbreviations
- VM : Virtual Machine
- FD : Fault Domain
- UD : Update Domain

# VM Explanations
- [Azure Bastion](https://learn.microsoft.com/en-us/azure/bastion/bastion-overview) : Azure Bastion is a fully platform-managed PaaS service provisioned inside a virtual network. Azure Bastion provides secure and seamless RDP and SSH connectivity to virtual machines. The access uses the Azure portal and SSL.
- [FD](https://learn.microsoft.com/en-us/azure/virtual-machines/availability-set-overview) : Fault domains define the group of virtual machines that share a common power source and network switch. By default, the virtual machines configured within your availability set are separated across up to three fault domains.
- [UD](https://learn.microsoft.com/en-us/azure/virtual-machines/availability-set-overview) : Each virtual machine in your availability set is assigned an update domain and a fault domain by the underlying Azure platform. Each availability set can be configured with up to 3 fault domains and 20 update domains.
- [Availability Zones](https://learn.microsoft.com/en-us/azure/reliability/availability-zones-overview?tabs=azure-cli) : Many Azure regions provide availability zones, which are separated groups of datacenters within a region. Availability zones are close enough to have low-latency connections to other availability zones. 
- [Availability sets](https://learn.microsoft.com/en-us/azure/virtual-machines/availability-set-overview) : Availability sets are logical groupings of VMs that reduce the chance of correlated failures bringing down related VMs at the same time. Availability sets place VMs in different fault domains for better reliability, especially beneficial if a region doesn't support availability zones.
