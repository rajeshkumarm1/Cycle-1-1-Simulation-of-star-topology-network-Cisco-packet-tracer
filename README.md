# Cycle-1-----1-Simulation-of-star-topology-network
# 🖧 Network Simulation using Cisco Packet Tracer

## 🎯 AIM
To simulate a network with topology using Cisco Packet Tracer and verify connectivity between computers using ICMP.

## 🛠️ EQUIPMENTS REQUIRED
- Desktop Computer  
- Cisco Packet Tracer 5.0 Software

## 📍 IP ASSIGNMENT

| NAME | IP ADDRESS     | SUBNET MASK     | NETWORK     | CLASS   |
|------|----------------|-----------------|-------------|---------|
| PC0  | 192.168.1.10   | 255.255.255.0   | 192.168.1.1 | Class C |
| PC1  | 192.168.1.30   | 255.255.255.0   | 192.168.1.1 | Class C |
| PC2  | 192.168.1.20   | 255.255.255.0   | 192.168.1.1 | Class C |
| PC3  | 192.168.2.20   | 255.255.255.0   | 192.168.1.2 | Class C |
| PC4  | 192.168.2.30   | 255.255.255.0   | 192.168.1.2 | Class C |
| PC5  | 192.168.2.10   | 255.255.255.0   | 192.168.1.2 | Class C |

## ⚙️ PROCEDURE

1. Open Cisco Packet Tracer software.  
2. Drag a 2950 Switch from the toolbar and drop it into the workspace.  
3. Drag a PC terminal from the toolbar and drop it into the workspace.  
4. Repeat Step 3 to add four more terminals.  
5. Select Copper Straight-Through cable and connect each PC to the 2950 switch using different ports.  
6. Click on each PC, select the Fast Ethernet interface, and assign the IP address and subnet mask.  
7. Repeat Step 6 for all PC terminals.  
8. Open the Terminal tab from the Desktop section of each PC and verify connectivity using the `ping` command.  
9. Use “Add Simple PDU” from the toolbar to test connectivity between source and destination PCs.

## 📊 IP CONNECTIVITY TABLE

## 🧾 IP Connectivity Table

| SENDER / RECEIVER | PC0 | PC1 | PC2 | PC3 | PC4 | PC5 |
|-------------------|-----|-----|-----|-----|-----|-----|
| **PC0**           | ✓   | ✓   | ✓   | ✓   | ✓   | ✓   |
| **PC1**           | ✓   | ✓   | ✓   | ✓   | ✓   | ✓   |
| **PC2**           | ✓   | ✓   | ✓   | ✓   | ✓   | ✓   |
| **PC3**           | ✓   | ✓   | ✓   | ✓   | ✓   | ✓   |
| **PC4**           | ✓   | ✓   | ✓   | ✓   | ✓   | ✓   |
| **PC5**           | ✓   | ✓   | ✓   | ✓   | ✓   | ✓   |


## 🗺️ NETWORK DIAGRAM
---
<img width="1024" height="326" alt="image" src="https://github.com/user-attachments/assets/b1678fb3-30c2-4351-9b61-ee7b524be458" />


## 🧾 BASIC NETWORKING COMMANDS

## IP Configuration
## IP Configuration Details: 
## (i)	ipconfig Command(windows OS) (or) ifconfig command(Linux OS) Syntax: C:\> ipconfig 
## (ii)	ipconfig/all Command:
## Syntax:
C:\> ipconfig /all 
## Testing Connectivity: 
## (i)	Self Ping Command:
## Syntax:
## c:\> ping <ipaddress> Example:
## C:\> ping 172.17.80.201
## C:\> ping 127.0.0.1 (ii) Ping to Destination Syntax:
## c:\> ping <destination-ipaddress> Example:
## C:\ping 172.17.80.1
## To Display IP to Physical address Translation Table and trace the route
## i) Arp Command Syntax:
 
## C:\arp –a
## (ii)	To trace the route Syntax:
## C:\tracert <ipaddress (or) specific address> Example: C:\tracert 172.17.80.1
## C:\tracert www.saveetha.ac.in

## OUTPUT
---
<img width="1088" height="796" alt="image" src="https://github.com/user-attachments/assets/39cc071d-feae-4f5e-b8a6-f2b7a155daf0" />

<img width="1920" height="1021" alt="cn1" src="https://github.com/user-attachments/assets/17ed9c2a-f9e3-4e3d-8f08-5e5d32fc1d68" />



## RESULT
Thus the computers in same network are able to communicate with each other and the communication between them were verified
