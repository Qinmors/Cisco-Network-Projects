# Cisco Network Projects
Compilation of personal experimentation and checkpoint projects.

---

## Configure a Wireless Router and Client (.pka)
This project is one of the Cisco Self-Checkpoints from the Networking Basics Modules. The overall objective of the project is to set up a home router.

### Key Skills Required:
*   **Physical Connectivity:** Understanding the appropriate cables to connect to the appropriate ports, emphasizing the use of Ethernet LAN cables for specific ports (i.e., Internet Ports and Ethernet Ports) as well as Coaxial cables.
*   **Router Configuration:** Understanding the configuration of the Wireless Router using a connected device (the Work PC) to perform changes via the Default Gateway address. Utilizing this address, configuration of the router is accessible through a web browser page interface.
*   **Wireless & DHCP Setup:** Allowing the connection of end-devices via wireless connections and utilizing DHCP IP address assignment. Configurations include modifying the number of allowed end-devices, changing the wireless router name (SSID), setting up a public password for end-devices, and configuring a specific admin password.

---

## Subnetting Project
This project is a personal, practical, hands-on lab derived from the theoretical framework of subnetting, focusing on diagnosing and understanding the common failures that led to the initial errors in the project.

### Core Concepts Covered:
*   Understanding the basic concept of subnetting using a router.
*   Understanding how routing works and how messages are forwarded at the OSI Reference Model Layer 3 (Network Layer).
*   Understanding the encapsulation of Layer 2 MAC addresses for local networks.
*   Understanding the basic concept of ARP (Address Resolution Protocol) for IPv4 addresses.

### Obstacles Encountered:
*   **Dividing a Local Network into Two Separate Subnets:** 
    The common problem faced beforehand was the concept of dividing the network. At first, I thought I would need two separate routers to isolate them, but it turns out I do not. This was a minor design setback in the initial phase.
*   **ARP Table Formation:** 
    This was the major difficulty faced while building the local network. Initially, routing and forwarding packets from one local network to another failed. While I first assumed it was a configuration error, the issue was entirely due to the lack of an established ARP table.

### Lessons Learned:
*   **Subnetting:** Mastered static network configuration—ensuring that the default gateway, IPv4 address, and subnet mask are configured correctly so that both Layer 2 and Layer 3 message forwarding work accordingly.
*   **ARP Table Formation:** Gained an understanding of how remote devices connect to one another. I learned how to build the pathway; therefore, before any routing, I ensure that every host sends an initial packet to the router to guarantee the construction of the path for later routing.
*   **Troubleshooting:** Developed the skills to troubleshoot Layer 2 and Layer 3 of the OSI Reference Model. I learned that even when everything provides positive feedback at Layer 1 and Layer 2, an established ARP pathway is still necessary. This led to the troubleshooting technique of prompting hosts to send packets to the router to successfully build the network tables.


---

## LAN Services Project

### Version 1.0 (19th of July, 2026)
#### Things added to the project:
- **End Devices** : Adding servers, PCs, and printers in different subnets
- **Routers** : Critical for routing which allows devices to communicate and access services from server in different subnet.
- **Switches** : Connecting the routers to the end devices.

### Core Concepts:
- Understanding the configuration of HTTP service from a server
- Understanding the configuration of DNS service from servers to allow connection to an HTTP service provided by a server through a domain name.
- Understanding the configuration of DHCP service from servers to allow DHCP automatic IPv4 address assignment
- Understanding routing and concepts critical for it, which are, subnetting, default gateway and IPv4 address assignment

### Obstacles faced during the project and Lessons Learnt:
- **Routing & DHCP Configuration** : The problem I had encountered during the project was the DHCP configuration. Usually, I would use the wirless router that provide simplicity for DHCP service. However, in this project, I decided to use DHCP service through the use of a server. Interestingly, from this experience alone, I had learnt to troubleshoot my routing problem which lies on the default gateway configuration on the servers. I also added DNS service to the server to ensure a successful HTTP connection through domain name system (DNS).
- **DNS Configuration** : DNS is essential for this project. I aimed for every devices in the subnet to be able  to receive HTTP from the web browser using domain name system, rather than typing IP address of the server that provides HTTP services. In which, this project has taught me the idea of how a network device would receive an HTTP service by using domain name system service from a server.
- **HTTP Service Configuration** : HTTP configuration here is quite peculiar I would say. In a way. to set it up, it is not a hard task, in which, the problem would be to configure the index.html file. For this problem, I utilize the usage of Artifical Intelligence to build me a chess game, aim to test whether the system packet tracer could run a simple HTML chess game.

### List of Files Attachment:
<img width="1125" height="629" alt="image" src="https://github.com/user-attachments/assets/a4028549-1db5-4620-881d-fc4ef669315d" />
Description: This is the overall look of the LAN network system, where subnets divide the network into three departments, which are network, IT, and Servers.

---

https://github.com/user-attachments/assets/1c5c14c9-4141-4b40-82cd-285d985664ec

Description: This video documents the utilities of the DNS service, DHCP service, HTTP service, routing and across network communication. 
