You are hired as a network engineer for Firewall Solutions, a 
mid-sized enterprise with a 5-floor office building. Each floor is equipped with 
a different number of computers, like floor 1 has 3984, floor 2 has 16999, 
floor 3 has 267, floor 4 has 213, and floor 5 has 20. Configure the DHCP 
server on floor 1, the HTTP server should be connected on floor 3, the DNS 
server should be connected on floor 2, and the Email and FTP servers of the 
company are on floor 5. The organization requires a well-structured network to 
ensure efficient communication and scalability. 
Network Design Requirements: 
1. Topology Selection: Design a Mesh topology for the first 2 floors and a Star 
topology for the remaining floors, considering performance and fault tolerance. 
(Just connect 7 computers on each floor instead of the given requirement, as we 
are not able to do this in Cisco Packet Tracer.)  
2. IP Addressing Scheme: The company has decided to use Class A public 
IPv4 addresses for the first 3 floors and Class B public for the remaining 
floors, following a classless addressing scheme that is VLSM. Allocate IP 
addresses properly for each floor, ensuring uniqueness. 
3.  Routing Strategy for Inter-Floor Communication & Connectivity: 
Recommend a routing approach that is Static for inter-floor communication. 
 Design how the floors will be connected for seamless interdepartment 
communication. 
 Suggest the appropriate network devices (e.g., switches, routers, access 
points) and their placement. 
 If using dynamic routing, use RIP routing protocol. 
 If using static routing, define the static routes for efficient data flow. 
 The minimum number of routers to be used should be 4 and the 
maximum 5. 
 Specify the number of default gateways along with IP addresses. 
 Specify each SUBENTWORK with proper Subnetwork address, host IP 
range, and broadcast address. 
