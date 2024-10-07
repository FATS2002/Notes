 >  Notes  30-09

---
##### go to Root user
```
sudo -i  or sudo su
```
#####  Make a directory 
```
mkdir notes
```
#####  go to 'notes'  directory
```
cd notes
```
##### change NAT TO BRIDGE in vmware settings
```
Nat to bridge
```


##### what is kali linux

```
it is debain operating system that is used for advanced penetration and security auditing  
```

```

q. The IP address 127.0. 0.1 is called a loopback address. Packets sent to this address never reach the network
but are looped through  the network interface card only.This can be used for diagnostic purposes to verify that
the internal path through the TCP/IP protocols is working.
q. Types of security and what is cybersecurity
q. what is applicationSecurity .what is InformationSecurity
q. what is dissolve DNS. nslookup command
q. what are protocols and Ports
q. typesof security. & classification

```

##### Elements of information security?
```
- confidentiality
- Intergrity
- availablibity
- authenticity
- Non-repudiation
```


#### classificaiton of Attacks:-
```
passive and active attacks
passiveExamples:- sniffing, vishing </br>
activeExamples:- MITM -Man in the Middle
              :-close-in Attacks-These attacks are performed in the proximity level.

```
 ##### CEH Hacking Methodology
```
1. Foot printing-technique or process where we can collecting Footprinting is an ethical hacking technique used to gather as much data as possible about a
specific targeted computer system, an infrastructure and networks to identify opportunities to penetrate them. It is one of the best methods of finding
vulnerabilities.
2. scanning
3. enumeration
4. vulnerabily analysis
```

```
Listing in linux-  ls -a
```
![image](https://github.com/user-attachments/assets/2bfdf185-4315-48c3-b46c-8532ff0dbf1c)


![image](https://github.com/user-attachments/assets/94d9addb-c054-4059-bfc7-1dad04204390)

7-10-24

ping in Linux
```
ping google.com 

```
To stop ping
```
control + c  
```

```
TTL Values ; Linux/MAC OS – 64 
Windows – 128 ; Cisco Routers – 255 
DNS – depends on the DNS resolver (can range from 128 to 86400).
```
```
Link: https://www.cloudflare.com/learning/ddos/glossary/internet-control-message-protocol-icmp/
Link: nmap.org
 defintion: closed ports, openports, 
```
#### scan through whole internet network
```
arp.scan - to find IP address 
```

```
192.168.01  apart fromt this all other IP 
we'll do ARP scan and find IP address of kali Linux
subnetting class
1ST   N.H.H.H
2ND   N.N.H.H
3RD   N.N.N.H
``

Steps:

```
1. ificonfig  what ever ip address you get put in arp
2.arp.scan  "arp-scan 172.20.10.2/24"
3. fping  fping -q    /grep "is alive"
4. nmap -network mapper
5. check which host is up and which is down
6. nmap[Target IP]
7,
```

