# Network-Lab
My small business network created in GNS3

## Network Topology

1. Establishing a WAN-CLOUD linked to a WAN-SWITCH allowing for centralized management and control of wide area network (WAN) connections, efficient routing, and traffic prioritization across geographically dispersed locations.

![image](https://github.com/T-AsiaFries/Network-Lab/assets/147548652/87d2ec95-5e1c-41cc-80e3-a47e4895191b)

2. Adding a FortiGate firewall and linked it to my WAN-SWITCH to act as the first line of defense to protect my computers, devices and data.
   
![Firewall drawio](https://github.com/T-AsiaFries/Network-Lab/assets/147548652/758a9f5c-fb83-4499-be1d-c800ae6e0162)

3. Linked my LAN and DMZ ports on the firewall to the corresponding switches I added to enable secure and segmented communication between different network zones while enforcing strict access controls and traffic policies.

![Switches drawio](https://github.com/T-AsiaFries/Network-Lab/assets/147548652/8e3cc968-f407-43ab-804b-3f98c86a79df)

4. Adding a Win10-1 workstation and linking it to the LAN-SWITCH to ensure the workstation can communicate effectively with other devices and applications within the LAN environment while maintaining security protocols and access permissions.

![Win10-1 drawio](https://github.com/T-AsiaFries/Network-Lab/assets/147548652/f52d967f-588a-408d-a6de-8246daa5f7b4)

5. Adding a Win2012r2-1 server to my network and linking it to my LAN-SWITCH to enable centralized services(Active Directory, DNS, DHCP, and file sharing) facilitating efficient management of network resources and user authentication.

![Win2012r2-1 drawio](https://github.com/T-AsiaFries/Network-Lab/assets/147548652/6d0ce846-cb19-4bbe-a74a-a64ac7ebb03d)

6. Adding a Win2012r2-2 server to my network and linking it to my LAN-SWITCH to expand the network's capacity while adding resilience and redundancy. This server's integration will facilitate load balancing, fault tolerance, and scalability, improving the performance overall and reliability of the network infrastructure.

![Win2012r2-2 drawio](https://github.com/T-AsiaFries/Network-Lab/assets/147548652/1cdae4be-19ad-4a8e-afe7-af05a619acb0)

7. Adding a Ubuntu-1 server to provide external-facing services, enhance network security and expand resource accessibility while maintaining network segmentation for enhanced security.

![Ubuntu-1 drawio](https://github.com/T-AsiaFries/Network-Lab/assets/147548652/e65cbdcf-20b4-4ead-ba07-deb56386d3fd)

8. Adding a Win2012r2-3 server to expand Active Directory services and facilitate secure access to external-facing resources.

![Win2012r2-3 drawio](https://github.com/T-AsiaFries/Network-Lab/assets/147548652/8f71206e-cd2e-4305-89a3-a15363f270e5)
