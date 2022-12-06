# Vlan Implementation using Packet tracer

Use Case: 
We are using our University Network structure to show the use case of VLAN and how scenario works when VLAN implemented.

 Our University have the split of 4 VLAN'S consists of a Five locations,

1.H-1

2.H-2

3.AB(Old Academic Building)

4.NAB(New Academic Building)

5.IC(International Center)

4.Old Campus(STAFF)

5.Old Campus(STUDENT)

Basically, In our implementation we have implemented one server i.e, EMAIL server and a configured CLOUD router to it with cross-over cable to process complex tasks in network. 

Then the MAIN campus router is connected from the CLOUD router with Serial DCE connection by attaching HWIC-2T on both the routers. 

The MAIN Campus router is then configured with VLAN Trunking to logically segment the further VLAN connection from the connected 3650-24PS MAIN Campus L3 switch(Core switch).

At the end of 3650-24PS core switch ports are enabled for VLAN connection to the five locations i.e,H-1, H-2, AB(Old Academic Building), NAB(New Academic Building), IC(International Center).

Afterwards, A new 2911 router is connected to the old campus with separated L3 switch and distribution and access layer. 

Users of all regions will have access to the server and can communicate without creating congestion in the Network, as well with help of VLAN a region can be isolated from others.

Inter VLAN routing has been performed. 


{Vlan Ip :}
VLAN 10 (H-1) -- 192.168.1.0/24                          
VLAN 20 (H-2)-- 192.168.2.0/24  
VLAN 30 (Academic Building AB) -- 192.168.3.0/24                                     
VLAN 40 (NAB) - 192.168.4.0/24
VLAN 50 (International Center IC) -- 192.168.5.0/24

 And in Old Campus,
 VLAN 90 (STAFF) -- 192.168.9.0/24
 VLAN 100(STU-PORTAL) -- 192.168.10/24


## Appendix

VLAN Topology
Switched LAN technology enables you to organize systems on a local network into VLANs. Before you divide a local network into VLANs, you must obtain switches that support the VLAN technology. You can configure all ports on a switch to serve a single VLAN or multiple VLANs, depending on the VLAN topology. Each switch manufacturer has different procedures for configuring ports on a switch.
