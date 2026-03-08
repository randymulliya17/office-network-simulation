Office Network Infrastructure Simulation

Tools:
- Cisco Packet Tracer
- GitHub
- GitHub Pages

Topology:
1 Router
2 Switch
6 PC

Features:
- VLAN 10 (Admin)
- VLAN 20 (Staff)
- Trunk between switches
- Inter VLAN routing
- DHCP configuration

Skill Demonstrated
- VLAN Configuration
- Trunk Configuration
- Inter-Switch Communication
- IP Addressing
- Network Troubleshooting
- Cisco Packet Tracer Simulation

Testing:
All devices successfully communicate across VLANs.

1.Topologi Jaringan

<img width="923" height="645" alt="Topologi" src="https://github.com/user-attachments/assets/fb4dbd73-b390-4a99-b9f4-ed7ed8de743c" />


2.VLAN di Switch 1

<img width="713" height="749" alt="vlan1-config" src="https://github.com/user-attachments/assets/43a4e079-48ae-46c1-800b-6e98c2124eaf" />


3.VLAN di Switch 2

<img width="717" height="749" alt="vlan2-config" src="https://github.com/user-attachments/assets/0e8e644b-e54f-4350-b090-ed429e29182a" />

4.Trunk di Switch 1

<img width="698" height="746" alt="trunk-switch1-config" src="https://github.com/user-attachments/assets/1ffbaf5f-bb35-470c-9c1b-5dcdde369692" />


5.Trunk di Switch 2
   
<img width="711" height="750" alt="trunk-switch2-config" src="https://github.com/user-attachments/assets/f8ed1dc3-3cf2-43c6-a34d-83fc173b5bfe" />

6.Router DHCP Binding
   
<img width="718" height="746" alt="router-DHCP-binding" src="https://github.com/user-attachments/assets/225e47a8-4777-47bf-8f75-bb6fb7a37076" />


Connectivity Test
PC 1 Ke PC 2 Dan PC 3

<img width="707" height="755" alt="Test Ping PC 1 ke PC 2 dan 3" src="https://github.com/user-attachments/assets/4dc86809-9d81-44b8-b038-4c97ae00f8b4" />


PC 4 Ke PC 2 Dan PC 6


<img width="704" height="751" alt="Test Ping PC 4 Ke PC 2 dan 6" src="https://github.com/user-attachments/assets/55bf7d72-1a51-4e1d-a686-fa6276462a50" />


Troubleshooting

Problem:
PC tidak bisa ping antar VLAN

Solution:
Configure Router-on-a-Stick and trunk port on switch
