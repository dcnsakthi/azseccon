# Azure Secure Connectivity
Azure Secure Connectivity - VPN/ExpressRoute and Networking

- [ExpressRoute (ER)](https://github.com/dcnsakthi/azsecureconnectivity/tree/main/README.md#expressroute-er)
- [Virtual Private Network (VPN)](https://github.com/dcnsakthi/azsecureconnectivity/tree/main/README.md#virtual-private-network-vpn)
    - [Site-to-Site (S2S)](https://github.com/dcnsakthi/azsecureconnectivity/tree/main/README.md#site-to-site-s2s)
    - [Point-to-Site (P2S)](https://github.com/dcnsakthi/azsecureconnectivity/tree/main/README.md#point-to-site-p2s)
    - [VNet-to-VNet (V2V)](https://github.com/dcnsakthi/azsecureconnectivity/tree/main/README.md#vnet-to-vnet-v2v)

#### ExpressRoute (ER)
ExpressRoute (ER) in Azure is a networking service that provides a dedicated and private connection between your on-premises network and Microsoft Azure. It offers a reliable, low-latency, and high-bandwidth connection that bypasses the public internet, ensuring a secure and consistent data transfer experience.

![image](https://github.com/dcnsakthi/azsecureconnectivity/assets/17950332/01360005-67fd-42bb-b86c-c19d64f8ade0)

[ExpressRoute Reference](https://learn.microsoft.com/en-us/azure/expressroute/expressroute-howto-circuit-portal-resource-manager)

#### Virtual Private Network (VPN)
A Virtual Private Network (VPN) in Azure is a secure and encrypted connection that allows you to establish a private network connection between your on-premises infrastructure and your Azure resources. It enables secure communication and data transfer between your local network and Azure, extending your on-premises network into the cloud.

With Azure VPN, you can connect your virtual networks in Azure (VNet-to-VNet), connect your on-premises network to Azure (Site-to-Site), or enable remote access for individual users (Point-to-Site).

![image](https://github.com/dcnsakthi/azsecureconnectivity/assets/17950332/ec272931-ed02-4443-96e8-52da0620a0ca)

##### Site-to-Site (S2S)
Site-to-Site (S2S) connectivity in Azure is a networking configuration that allows you to establish a secure and encrypted connection between your on-premises network and Azure virtual networks. It enables seamless integration and communication between your local network and resources deployed in Azure.

![image](https://github.com/dcnsakthi/azsecureconnectivity/assets/17950332/3aecb286-fc78-458e-828a-afe2656dbea9)


##### Point-to-Site (P2S)
Point-to-Site (P2S) connectivity in Azure is a networking configuration that allows individual remote users to securely access Azure resources from remote locations. It enables users to connect to Azure virtual networks over the internet without requiring a site-to-site VPN connection.

![image](https://github.com/dcnsakthi/azsecureconnectivity/assets/17950332/87232dca-4b23-4535-af6e-a73589938de3)

##### VNet-to-VNet (V2V)
VNet-to-VNet (V2V) connectivity in Azure is a networking configuration that allows you to establish a secure and private connection between two Azure virtual networks. It enables seamless communication and resource access between the virtual networks, providing a distributed and interconnected network infrastructure within Azure.

![image](https://github.com/dcnsakthi/azsecureconnectivity/assets/17950332/5de7c732-a2d5-4908-8a6d-0469b5f98993)


In many cases, these connectivity options, such as ExpressRoute and VPN (S2S and P2S), coexist to fulfill different networking and connectivity needs of customers.

![image](https://github.com/dcnsakthi/azsecureconnectivity/assets/17950332/719523ac-372e-4d76-b16e-e859cf2dd438)
