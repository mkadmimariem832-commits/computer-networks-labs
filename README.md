Computer Networks Labs --- Packet Tracer
A collection of networking labs completed as part of my studies in
Réseaux et Services Informatiques (RSI) at ISET Nabeul, Tunisia.
This repository brings together practical work on Cisco switching,
VLANs, inter-VLAN routing, link aggregation, switch security, and
dynamic routing using Cisco Packet Tracer.
Projects
  Lab               Project              Main topics       Packet Tracer file
  TP 07             Layer 3 Switching    Multilayer        TP07_Layer3_Switching_InterVLAN_Routing.pkt
                    and Inter-VLAN       switching, VLANs,
                    Routing              SVIs, routed
                                         ports, default
                                         routes, IP
                                         routing,
                                         connectivity
                                         testing           
  
 
  TP 10             Switch Security and  SSH               TP10_Switch_Security_and_SSH.pkt
                    Secure Remote Access configuration,
                                         local user
                                         authentication,
                                         RSA keys, port
                                         security, MAC
                                         address
                                         restrictions,
                                         disabling unused
                                         ports             
  Practical Exam    VLANs, VTP,          VLAN 10/20/30/99, EXAM_VLAN_VTP_RouterOnAStick_EtherChannel.pkt
                    Router-on-a-Stick,   VTP
                    and EtherChannel     server/client,
                                         802.1Q trunks,
                                         native VLAN 99,
                                         inter-VLAN
                                         routing, PAgP and
                                         LACP              
       
Skills Practiced
Switching and VLANs
- Creating and assigning VLANs
- Configuring access ports and 802.1Q trunk links
- Configuring a native VLAN
- Managing VLANs with VTP
- Implementing inter-VLAN routing with a multilayer switch or
  Router-on-a-Stick
Link Aggregation
- Configuring EtherChannel using PAgP and LACP
- Verifying Port-Channel operation
- Improving link capacity and redundancy between switches
Network Security
- Enabling SSH for secure remote device administration
- Configuring local user authentication and RSA keys
- Restricting remote access to SSH
- Applying switch port security using MAC addresses
- Disabling unused switch ports and configuring a warning banner

Repository Structure
computer-networks-labs/
├── README.md
├── TP07_Layer3_Switching_InterVLAN_Routing.pkt
├── TP10_Switch_Security_and_SSH.pkt
├── EXAM_VLAN_VTP_RouterOnAStick_EtherChannel.pkt
How to Use
1. Install Cisco Packet Tracer.
2. Clone or download this repository.
3. Open the .pkt file for the lab you want to explore.
4. Inspect the topology and device configurations.
5. Use Simulation mode and connectivity tests to observe network
   behavior.
Notes
- The filenames listed above are proposed names for the corresponding
  Packet Tracer projects. Add the actual .pkt files to the
  repository after saving them with these names.
- The project summaries are based on the provided lab instructions.
  They describe the topics and objectives covered by each lab; they do
  not independently confirm that every configuration or test was
  completed successfully.
- The practical exam file is named by topic rather than by a numbered
  TP because the source document identifies it as an exam practical.
Author
Networking student --- Réseaux et Services Informatiques (RSI)
ISET Nabeul, Tunisia
