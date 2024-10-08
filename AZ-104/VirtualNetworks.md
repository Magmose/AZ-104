# Network Abbreviations
- @ : Root Domain
- A : IPv4 Address Record
- AAAA : IPv6 Address Record
- AGW : Application Gateway
- ALB : Application Load Balancer
- ARM : Azure Resource Manager
- ASN : Autonomous System Number
- ASG : Application Security Groups 
- Bastion : Azure Bastion for secure RDP/SSH
- BGP : Border Gateway Protocol
- CAA : Certificate Authority Authorization
- CNAME : Canonical Name Record
- CIDR : Classless Inter-Domain Routing
- DNAME : Delegation Name
- DMZ : Demilitarized Zones
- DNS : Domain Name System - Port 53
- DNSKEY : DNS Public Key
- DNS Zone : DNS management within Azure
- DS : Delegation Signer
- ExpressRoute : Dedicated, private connection from on-premises networks to Azure
- FQDNs : Fully Qualified Domain Names
- FTP : File Transfer Protocol - Port 21
- HINFO : Host Information
- HTTP : Hypertext Transfer Protocol - Port 80
- HTTPS : Hypertext Transfer Protocol Secure - Port 443
- ILB : Internal Load Balancer
- IMAP : Internet Message Access Protocol - Port 143 (IMAP) / Port 993 (IMAP over SSL)
- ISP : Internet Service Provider
- LAN : Local-Area Network
- LDAP : Lightweight Directory Access Protocol - Port 389 (LDAP) / Port 636 (LDAP over SSL)
- LB : Load Balancer
- LOC : Location Information
- MX : Mail Exchange Record
- NAPTR : Naming Authority Pointer
- NAT : Network Address Translation
- NIC : Network Interface
- NLB : Network Load Balancer
- NS : Name Server
- NSG : Network Security Group
- NTP : Network Time Protocol - Port 123
- NVA : Network Virtual Appliance
- P2S : Point-To-Site
- Peering : VNET Peering, connecting virtual networks
- PIP : Public IP
- POP3 : Post Office Protocol 3 - Port 110 (POP3) / Port 995 (POP3 over SSL)
- PTR : Pointer Record
- RDP : Remote Desktop Protocol - Port 3389
- RP : Responsible Person
- S2S : Site-To-Site
- SFTP : Secure File Transfer Protocol - Port 22 (Same as SSH)
- SLB : Standard Load Balancer
- SMTP : Simple Mail Transfer Protocol - Port 25 (SMTP) / Port 587 (SMTP over TLS)
- SNMP : Simple Network Management Protocol - Port 161/162
- SOA : Start Of Authority
- SPF : Sender Policy Framework
- SRV : Service Locator
- SSH : Secure Shell Protocol - Port 22
- SSHFP : SSH Public Key Fingerprint
- Telnet : Port 23 (Not recommended due to lack of security)
- TFTP : Trivial File Transfer Protocol - Port 69
- TXT : Text Record
- UDR : User Defined Route
- VLAN : Virtual Local Area Network
- VNET : Virtual Network
- VNG : Virtual Network Gateway
- VPN : Virtual Private Network
- WAN : Wide-Area Network
- WAF : Web Application Firewall (usually associated with Application Gateway)
- WLAN : Wireless Local Area Network

# Network Explanations
- [ASG](https://learn.microsoft.com/en-us/azure/virtual-network/network-security-groups-overview) : Application security groups enable you to configure network security as a natural extension of an application's structure, allowing you to group virtual machines and define network security policies based on those groups. You can reuse your security policy at scale without manual maintenance of explicit IP addresses.
- [DMZ](https://learn.microsoft.com/en-us/azure/security/fundamentals/network-best-practices) : A perimeter network (also known as a DMZ) is a physical or logical network segment that provides an extra layer of security between your assets and the internet. Specialized network access control devices on the edge of a perimeter network allow only desired traffic into your virtual network.
- [ExpressRoute](https://learn.microsoft.com/en-us/azure/architecture/reference-architectures/hybrid-networking/expressroute) : ExpressRoute lets you extend your on-premises networks into the Microsoft cloud over a private connection with the help of a connectivity provider.
- [Hub](https://learn.microsoft.com/en-us/azure/architecture/networking/architecture/hub-spoke-vwan-architecture) : The hub is a virtual network in Azure that acts as a central point of connectivity to your on-premises network.
- [Hub-Spoke](https://learn.microsoft.com/en-us/azure/architecture/networking/architecture/hub-spoke-vwan-architecture) : Traffic flows between the on-premises data center(s) and the hub through an ExpressRoute or VPN gateway connection.
- [IPsec](https://learn.microsoft.com/en-us/windows/win32/fwp/ipsec-configuration#what-is-ipsec) : Internet Protocol Security (IPsec) is a set of security protocols used to transfer IP packets confidentially across the Internet. IPsec was formerly mandatory for all IPv6 implementations (but see IPv6 Node Requirements; and optional for IPv4.
- [IPv4](https://www.geeksforgeeks.org/differences-between-ipv4-and-ipv6/) : IPv4 addresses are 32-bit integers that have to be expressed in Decimal Notation. It is represented by 4 numbers separated by dots in the range of 0-255, which have to be converted to 0 and 1, to be understood by Computers. For Example, An IPv4 Address can be written as 189.123.123.90.
- [IPv6](https://www.geeksforgeeks.org/differences-between-ipv4-and-ipv6/) : IP version 6 is the new version of Internet Protocol, which is way better than IP version 4 in terms of complexity and efficiency. IPv6 is written as a group of 8 hexadecimal numbers separated by colon (:). It can be written as 128 bits of 0s and 1s.
- [NVA](https://learn.microsoft.com/en-us/azure/well-architected/service-guides/network-virtual-appliances/reliability) : Network virtual appliances (NVAs) are virtual machines that control the flow of network traffic by controlling routing. You'll typically use them to manage traffic flowing from a perimeter-network environment to other networks or subnets.
- [Point-to-Site](https://learn.microsoft.com/en-us/azure/vpn-gateway/vpn-gateway-howto-point-to-site-classic-azure-portal) : You use a Point-to-Site (P2S) VPN gateway to create a secure connection to your virtual network from an individual client computer.
- [Site-to-Site](https://learn.microsoft.com/en-us/azure/vpn-gateway/vpn-gateway-howto-site-to-site-classic-portal) : A Site-to-Site VPN gateway connection is used to connect your on-premises network to an Azure virtual network over an IPsec/IKE (IKEv1 or IKEv2) VPN tunnel.
- [Spokes](https://learn.microsoft.com/en-us/azure/architecture/networking/architecture/hub-spoke-vwan-architecture) : The spokes are virtual networks that peer with the hub and can be used to isolate workloads.
- [VNet-to-VNet](https://learn.microsoft.com/en-us/azure/vpn-gateway/vpn-gateway-howto-vnet-vnet-portal-classic) : Connecting a virtual network to another virtual network (VNet-to-VNet) in the classic deployment model using a VPN gateway is similar to connecting a virtual network to an on-premises site location.
- [Azure Bastion](https://learn.microsoft.com/en-us/azure/bastion/bastion-overview): Azure Bastion is a fully managed PaaS service that you provision to securely connect to virtual machines via private IP address. It provides secure and seamless RDP/SSH connectivity to your virtual machines directly over TLS from the Azure portal, or via the native SSH or RDP client already installed on your local computer.
