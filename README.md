# Networking
- A computer network is a collection of various computing devices, The purpose of a computer network is so that the device can shared data.

## Types of Computer Network
1. PAN - (Personal Area N/W) 1-100 meter.
2. LAN - (Local Area N/W) Connects devices within a small area (home, office, school), Up to 2km.
3. CAN - (Campus Area N/W) 1-5Km.
4. MAN - (MetroPolitan Area N/W)  Covers a city or large campus, 5-50km.
5. WAN - (Wide Area N/W) - Connects devices over large distances (e.g., the Internet) Above 50Km.

# TCP/IP and OSI Model Protocols
- Developed By ARPANET
- Support Client to Server and Peer-to-Peer
<img src="https://cdn.bunny.pictures/images/What-is-the-OSI-model-and-encapsulation-vs-TCP-IP.png" alt="OSI Model" width="700">

# Network Topology
- Network topology refers to the physical or logical arrangement of devices in a network. How devices is connected to each other.
1. Bus Topology - All devices are connected to a single central cable (backbone).
2. Star Topology -  All devices are connected to a central hub or switch.
3. Ring Topology - Each device is connected to two other devices, forming a closed loop.
4. Mesh Topology - Every device is connected to every other device (full mesh) or selectively connected.
5. Tree Topology - A hybrid of star and bus topology where multiple star networks are connected to a backbone cable.
6. Hybrid Topology - A combination of two or more different topologies.

# Various Device in Computer Networking
- Cabel + Repeaters + hub (hardware)
- Bridges + Switches + Router (hardware/software)
- Gateway + firewall + IDs (Security purpose use) + Modem

## Cabel  ( 10 base = 10 mbps, T = 100 meter)
- A cable in networking is a physical medium used to transmit data between devices.
1. Twisted Pair Cable (Ethernet Cable - LAN Cable) - 10 Base T, 100 Base T
2. Coaxial Cable - 10 Base 2 , 10 Base 5
3. Fiber Optic Cable - 100 Base fx
4. USB Cable - Used to connect computers to peripherals 
5. HDMI Cable - Used for transmitting audio and video signals

## Repeater
- Work on Physical layer ( work on hardware)
- 10 Base 2
- 2 port devices
- No filtering
- Regenrate the strength ( based on original energy)

## Hub
- A hub is a basic networking device that connects multiple computers or devices in a local area network (LAN) and allows data to be transmitted between them.
- Work on Physical layer.
- Multiport Repeater ( 4ports, 8, 16, 32 etc)
- No filtering
- Collision Domain

## Bridges
- layer2 - Data link layer
- Connect 2 difference LANs
- Filtering
- Collision Domain
- Bridge can check mac address ( to check source to destination mac address)
- Two Types: Static and Dynamic Bridges

## Switch
- Layer2 (data link layer, physical layer) device
- Multiport Bridges ( connect multiple devices in LAN)
- Full Duplex Link (both side can send data same time)
- Traffic is minimal
- Collision Domain is 0

## Router
- Layer 3 (Network layer, data link layer, physical layer)
- Use to connect 2 different n/w.
- Internet (WAN)  - collection of different n/w.
- Router use routing table (maintain  packet connected how many network)
- Multiple network can connect
- Filtering, forwording
- Collision Domain 0 ( Store and forward method follow)

## Gateway
- A gateway is a networking device that connects two different networks using different communication protocols.
- Network Layer (Layer 3)
- Firewall & Security
  
#### Types of Gateways:
1. Network Gateway – Connects different IP networks (e.g., Internet to a private network).
2. VoIP Gateway – Converts voice signals (analog ↔ digital) for phone systems.
3. Cloud Gateway – Connects on-premise networks to cloud services.
4. Email Gateway – Filters and scans emails for security threats.
   
## Firewall
- A firewall is a network security device or software that monitors and controls incoming and outgoing network traffic based on predefined security rules

# IP Address
- An IP Address (Internet Protocol Address) is a unique identifier assigned to devices connected to a network, allowing them to communicate with each other.
1. IPv4 (Internet Protocol Version 4)
2. -   Format: 192.168.1.1 (4 sets of numbers, 0-255)
   -   32-bit address, supports ~4.3 billion devices
3. IPv6 (Internet Protocol Version 6)
4. - Format: 2001:0db8:85a3:0000:0000:8a2e:0370:7334
   - 128-bit address, supports a massive number of devices

## Classess Addressing
1. Class A (Large Networks)
2. Class B (Medium Networks)
3. Class C (Small Networks)
4. Class D (Multicasting)
5. Class E (Experimental)

## DNS (Domain Name System)
- DNS converts domain names (e.g., google.com) into IP addresses (142.250.183.206). Without DNS, we would need to remember IP addresses instead of domain names!
- Easy to search because IP address is dynamic and domain name is same every time.
- .com, .in. .org, .edu, .mil etc.
- There are 13 root servers worldwide, (Root servers are the top-level servers in the DNS hierarchy that help resolve domain names to IP addresses).

## 📌 Difference Between TCP and UDP
- TCP (Transmission Control Protocol) and UDP (User Datagram Protocol) are both transport layer protocols used for sending data over networks, but they differ in reliability, speed, and use cases.

## Application Protocol - DNS, HTTP, SMPT, FTP, POP

#### HTTP
1. Port No 80
2. Inband Protocol
3. Stateless
4. HTTP 1.0 Not Persistent ( payment section, otp section)
5. HTTP 1.1 Persistent (gmail etc)
6. Commands ( get, put, post, patch, delete, connect)

## FTP
1. Port No 20 (Data) and 21 (Control)
2. Data connection is non-persistent
3. Control connection is persistent
4. Not Inband
5. Reliable
6. Stateful

## SMTP && POP
1. FTP is synchronous but SMTP & POP both are synchronous and asynchronous.
2. SMTP Port no 25 pushing the mail.
3. By default, the POP3 Protocol works on 2 ports-
   -  PORT 110 (this is default), POP3 non-encrypted port.
   -  PORT 995 - this is the port you need to use if you want to connect using POP3 securely.
5. MIME(Multipurpose Internet Mail Extension).

