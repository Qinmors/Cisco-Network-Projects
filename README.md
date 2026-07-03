# Cisco-Network-Projects
Compilation of personal experimentation and checkpoint projects

## Configure a Wireless Router and Client.pka
This projects is one of the Cisco Self-Checkpoints on the Networking Basics Modules. The project overall objective is to set up a home router.

### The specific skills required:
- Understanding the appropriate cables to connect to appropriate port. Emphasizing in the usage of Ethernet LAN Cables to appropriate ports (i.e. Internet Ports, and Ethernet Ports), as well Coaxical Cables.
- Understanding the Configuration of the Wireless Router using one of the devices connected, in this case, the Work PC, which perform changes on the routers using the Default Gateway address. Utilizing the address, configuration to the router is possible through Webpage, by inputting the address into the web address.
- Performing objectives above allow the connection of end-devices that utilizes wireless connection, and utilize DHCP IP address assignment. Configurations allow changes to number of allowed end-devices connected, configuring the wireless router name, and password. As well, configuring the Public Password for end-devices, and specific configuration for the admin password.



## Subentting Project
This project is my own personal practical hands-on derived from the theoritical framework of Subnetting, and understanding the common failure that led to the initial error of the project.

### From this specific program, it required:
- Understanding the basic concept of subnetting using router
- Understanding how routing works and forwarding messages of the OSI Reference Layer 3 (Network)
- Understanding the Encapsulation of Layer 2 MAC Address, for local network
- Understanding the bsaic concept of ARP (Address Resolution Protocol) for IPv4 address.

### Obstacles that I have encountered on the way:
- Concept of dividing a local network into two seperate subnet through the use of router and subnetting
  The common problem I face in this project beforehand was the concept of dividing the network. At first, I thought I would need two routers to separate it, but turns out I don't. This was the obstacle I had experienced, a minor setback in the design of the network.
- Concept of ARP Table Formation
  This is the major difficulty that I had faced all this time in building the local network. Beforehand, I wasn't successful in routing and forwarding packages from one local network to another. I initially thought that the problem was the configuration, turns out it was not other than the formation of the ARP table.

### What I have learnt from the project:
- Subnetting
  From subnetting alone, I have learnt the static configuration of the network, ensuring that default gateway, IPv4 address, as well as the subnet mask is configured correctly to ensure that both message forwarding for Layer 2 and Layer 3 works accordingly.
- ARP (Address Resolution Protocol) Table Formation
  From this project alone, I have to understand how remote devices connected to one another. I have to build the pathway, therefore, before any routing, I ensure that every host sends their packet to the router. this is to ensure the construction of the path for later routing.
- Troubleshooting
  From this project alone, I have learnt how to troubleshoot correctly for the layer 2 and layer 3 of OSI Reference Model. From here, I learn that even when everything has a positive feedback from layer 1 and layer 2. I develop the skill to understand that, the ARP pathway is necessary, therefore, I brute force to every hosts to send their packet to the router.
