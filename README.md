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


