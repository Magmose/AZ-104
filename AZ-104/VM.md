# VM Abbreviations
- VM : Virtual Machine
- FD : Fault Domain
- UD : Update Domain

# VM Explanations
- [Azure Bastion](https://learn.microsoft.com/en-us/azure/bastion/bastion-overview) : Azure Bastion is a fully platform-managed PaaS service provisioned inside a virtual network. Azure Bastion provides secure and seamless RDP and SSH connectivity to virtual machines. The access uses the Azure portal and SSL.
- [FD](https://learn.microsoft.com/en-us/azure/virtual-machines/availability-set-overview) : Fault domains define the group of virtual machines that share a common power source and network switch. By default, the virtual machines configured within your availability set are separated across up to three fault domains.
- [UD](https://learn.microsoft.com/en-us/azure/virtual-machines/availability-set-overview) : Each virtual machine in your availability set is assigned an update domain and a fault domain by the underlying Azure platform. Each availability set can be configured with up to 3 fault domains and 20 update domains.
- [Availability Zones](https://learn.microsoft.com/en-us/azure/reliability/availability-zones-overview?tabs=azure-cli) : Many Azure regions provide availability zones, which are separated groups of datacenters within a region. Availability zones are close enough to have low-latency connections to other availability zones. 
- [Availability sets](https://learn.microsoft.com/en-us/azure/virtual-machines/availability-set-overview) : Azure Bastion is a fully managed PaaS service that you provision to securely connect to virtual machines via private IP address. It provides secure and seamless RDP/SSH connectivity to your virtual machines directly over TLS from the Azure portal, or via the native SSH or RDP client already installed on your local computer.
- [Azure App Service plan](https://learn.microsoft.com/en-us/azure/app-service/overview-hosting-plans) : An App Service plan defines a set of compute resources for a web app to run. When you create an App Service plan in a certain region (for example, West Europe), a set of compute resources is created for that plan in that region.