🏥 Hospital Management Network Design
Tool: Cisco Packet Tracer | Topology: Hierarchical Hub-and-Spoke

📌 Project Overview
This project involved designing and implementing a robust network infrastructure for a multi-department hospital. The goal was to ensure secure, high-speed communication between medical staff, administration, and patient monitoring systems (IoMT) while maintaining data privacy.

🛠️ Key Technical Features
Multi-Router Architecture: Implemented an 8-router backbone to handle inter-departmental routing and redundancy.

Network Segmentation (VLANs): Created dedicated VLANs for different hospital wings (Admin, Emergency, Pharmacy, Wards, and Labs) to limit broadcast domains and increase security.

Routing Protocols: * OSPF: Configured for dynamic and efficient internal routing.

Static Routing: Used for specific gateway paths.

Security & Address Management:

NAT (Network Address Translation): Configured to allow private hospital IPs to access external resources securely.

DHCP: Automated IP assignment for medical tablets and workstations.

IoMT Integration: Connected IoT-enabled patient monitors and sensors to a central server for real-time health tracking.

📂 File Structure
Hospital_Network_Final.pkt: The source Packet Tracer file.

Topology_Diagram.png: High-resolution export of the network layout.

IP_Addressing_Scheme.pdf: Documentation of the subnets used (192.168.x.x).

🚀 How to Run
Download and install Cisco Packet Tracer.

Clone this repository: git clone https://github.com/[Your-Username]/Hospital-Network-Design.

Open the .pkt file and enter Simulation Mode to track packet flow across routers.
Download and install Cisco Packet Tracer.

Clone this repository: git clone https://github.com/[Your-Username]/Hospital-Network-Design.
