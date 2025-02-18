THIS PROJECT IS MADE USING THE CISCO PACKET TRACER

SCENARIO:

SSG company has its office in a 3-level building and has 3 departments at each level level 1: GA, PA, Production level 2: HR, Finance, Marketing level 3: Executive, legal, IT (each department will have its own VLAN and will accommodate 50 hosts)

Besides PCs, SSG company also has printers, servers, and access points, each of which will be separated into different VLANs. every department will have 1 printer and an access point will be placed on each level the servers that SSG company has will be used as a web server, DNS server, DHCP server, and Email server

NOTE: 
YOU CAN DETERMINE YOUR IP ADDRESS 
ALL END DEVICES WILL GET THEIR IP ADDRESS BY USING DHCP EXCEPT PRINTERS
THE ROUTING PROTOCOL THAT IS USED IN THIS PROJECT IS OSPF

DEVICES USED IN THIS PROJECT
- 12 L2 switches
- 2 Multilayer/L3 switches
- 4 routers
- 3 access point
- 4 servers
- 9 printers

FRAMEWORK
- add initial configuration to switch and router (hostname, password, banner, etc)
- trunk configuration on the interface that connects to another switch
- VLAN configuration on the L2 switch
- subnetting and IP addressing
- assign static IP to the L3 switch interface to the core router interface and vice-versa (v)
- OSPF configuration on L3 switch and router
- assign static IP to servers
- DHCP configuration on the DHCP server
- configure inter-vlan on L3 Switch and address helper
- configure DHCP IP on the end device
- configure nat and access list
- configure Cisco Wireless LAN Controller and APs
