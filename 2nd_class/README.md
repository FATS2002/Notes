#### Notes  25-09

# Networking Concepts
## 1. What is TCP? TCP (Transmission Control Protocol) is a core protocol of the Internet Protocol Suite that ensures reliable, ordered, and error-checked delivery of data between applications. 
## 2. What is Protocol and Its Types? A protocol is a set of rules governing the exchange of data between devices. Types include Application Layer Protocols (e.g., HTTP, FTP), Transport Layer Protocols (e.g., TCP, UDP), Network Layer Protocols (e.g., IP), and Link Layer Protocols (e.g., Ethernet). 
## 3. TCP/IP Model and Header? The TCP/IP model consists of four layers: Application, Transport, Internet, and Network Access. The TCP segment structure includes Source Port, Destination Port, Sequence Number, Acknowledgment Number, Data Offset, Flags, Window Size, Checksum, Urgent Pointer, Options, and Data. 
## 4. Define TCP and UDP? TCP (Transmission Control Protocol) is a connection-oriented protocol that guarantees delivery and order. Example: Web browsing (HTTP). UDP (User Datagram Protocol) is a connectionless protocol that does not guarantee delivery. Example: Video streaming (real-time applications). Difference between TCP and UDP: TCP is connection-oriented; UDP is connectionless. TCP ensures delivery; UDP does not. Use Cases: TCP is used in web traffic; UDP is used in gaming or video streaming. 
## 5. Port Names and Port Numbers? Ports are numerical identifiers for processes. Examples include HTTP: Port 80, HTTPS: Port 443, FTP: Port 21. 
## 6. IP Classification? IP addresses are classified into Class A (1.0.0.0 to 126.255.255.255), Class B (128.0.0.0 to 191.255.255.255), Class C (192.0.0.0 to 223.255.255.255), Class D (224.0.0.0 to 239.255.255.255 for multicast), and Class E (240.0.0.0 to 255.255.255.255 for experimental). 
## 7. OSI Layers and Definitions? 1. Physical Layer: Transmits raw bit streams over a physical medium. 2. Data Link Layer: Provides node-to-node data transfer and error correction. 3. Network Layer: Handles routing of data packets between devices. 4. Transport Layer: Manages end-to-end communication and error recovery. 5. Session Layer: Controls the dialogues (sessions) between computers. 6. Presentation Layer: Translates data formats, encryption, and compression. 7. Application Layer: Interfaces directly with user applications. 
## 8. Transport Layer Ports? The Transport Layer uses ports to manage communication between applications on hosts. 
## 9. Which Ports Come Under Which Layer? Transport Layer: TCP and UDP ports (e.g., 80, 443). Network Layer: IP addresses. Router: Operates primarily at the Network Layer. 
## 10. Difference Between Routers and Switches? Router: Connects different networks, routes data packets using IP addresses. Switch: Connects devices within the same network, uses MAC addresses to forward data. 
## 11. What is MAC Address? A MAC address (Media Access Control) is a unique identifier assigned to network interfaces for communications at the data link layer. How to Get MAC Address? Use the command: Windows: `getmac` or `ipconfig /all`, Linux/Mac: `ifconfig` or `ip link`. 
## 12. What Presentation Layer and Session Layer Do? Presentation Layer: Translates data formats, manages encryption and compression. Session Layer: Manages sessions and maintains connections. 
## 13. What are Port Numbers? Port numbers are 16-bit integers used to identify specific processes or services on a device. 
## 14. Transport and Network Layer Importance? The Transport Layer provides end-to-end communication. The Network Layer handles packet forwarding, while the Data Link and Physical Layers do not have ports, as they manage lower-level communication between devices.



1. what is Tcp.
2. what is Protocol and Its Types
3.TCP/IP model and header [Tcp header]  -TCP segment structure
4. Define TCP and UDP.diff  btw TCP and UDP with ex for each.
5. portNames and portNo's.
6. IP classification
7. OSI Layer and definitions
8. Transport Layer Ports
9. Which ports ll come under which Layer -router ll come under which Layer
10. diff bw routers and switches.
11. what is mac address.How to get Mac address & which cmd is used to get Mac address.
12. what presentationLayer ll do and what session Layer ll do.
13. what are portNos
14. Transport and nw Layer Important -datalink and physical Layer dont have any ports


#### cmds
1. write cmds to operate Normal windows.
####  1. Windows Commands for Basic Operations
- **Open Command Prompt:** `cmd`
- **List Directory:** dir
- **Change Directory:** `cd [directory_name]`
- **Copy File:** `copy [source] [destination]`
- **Move File:** `move [source] [destination]`
- **Delete File:** `del [file_name]`

- **Get IP Address:** 
  ```bash
  ipconfig

2. 
3. -How to get IP address of windows- Ping cmds -nsLookup cmds
4. what is dns.
5. basic linuxCommands
6. what is linux and How many types of operatingsystem
7. what is virtualization

8. what is virtualMachine.why we use vm
A Virtual Machine  is a software emulation of a physical computer. It runs an operating system & apps just like a physical machine.

10. what is HTTP and HTTPS.
11. what is SSH and telnet.  
SSH (Secure Shell): A protocol for secure remote login and other secure network services over an insecure network. Port Number: 22.
Telnet: A protocol for remote login that is not secure. It sends data in plain text. Port Number: 23.

13. what is VLAN and VPN
14. fullform of SMTP & portNo
15. portNo of HTTP & DHCP
16. VNC &NTP portNo
17. FTP control portNo.
18. SMP portNo
19. NTPA. 389  .  **NTP (Network Time Protocol)**: Port 123 , **LDAP**: Port 389
20. what is protocol .How many protocols
    A protocol is a set of rules governing the exchange or transmission of data over a network. There are numerous protocols, each serving different purposes:
- HTTP/HTTPS: For web browsing.
- FTP/SFTP: For file transfers.
- SMTP/IMAP/POP3: For email.
- DNS: For domain name resolution.
- DHCP: For dynamic IP address assignment.
- SSH/Telnet: For remote access.
- NTP: For time synchronization.
- VPN: For secure remote access.
- VLAN: For network segmentation
- 
22. IMAP portNo   port -143
23. SMTP portNo.  port  -25
24. SMTPS portNo. port -465
25. FTP & FTPS-FTP secure or not


#### Links 
> https://github.com/microsoft/Security-101
