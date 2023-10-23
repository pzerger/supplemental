# Networking

## Table of Contents

- [Authentication/Encryption Protocols](#authenticationencryption-protocols)
- [Routing Protocols](#routing-protocols)
- [IP Networking](#ip-networking)
- [Tunneling Protocols](#tunneling-protocols)
- [Network Access Control](#network-access-control)  
- [LAN Protocols](#lan-protocols)
- [WAN Protocols](#wan-protocols)
- [Network Monitoring and Management](#network-monitoring-and-management)
- [Network Security](#network-security)
- [Network Storage](#network-storage)
- [VoIP/Video Conferencing](#voipvideo-conferencing)
- [Network Devices](#network-devices)
- [Network Attacks](#network-attacks)
- [Wireless](#wireless)
- [Virtual Networks](#virtual-networks)
- [Other Common Networking Terms](#other-common-networking-terms)

## Authentication/Encryption Protocols

**Captive Portals** - Web pages used to authenticate users and authorize access to a wireless network. Operate at application layer (Layer 7). Allow guest access while maintaining control.

**Extensible Authentication Protocol (EAP)** - An authentication framework that supports multiple authentication methods like tokens, smart cards, certificates etc. Operates at the data link layer (Layer 2). 

**Lightweight Extensible Authentication Protocol (LEAP)** - A simplified version of EAP used in wireless networks and Point-to-Point connections. Operates at data link layer (Layer 2).

**Over-the-Air (OTA)** - Protocols for wireless transmission of data, configuration settings, and firmware. Operates at physical layer (Layer 1). Convenient but less secure.  

**Protected Extensible Authentication Protocol (PEAP)** - An extension of EAP that provides mutual authentication and key derivation. Operates at data link layer (Layer 2).

**Simultaneous Authentication of Equals (SAE)** - A key establishment protocol for WPA3 authentication. Operates at data link layer (Layer 2). Resists password attacks. 

**Temporal Key Integrity Protocol (TKIP)** - A protocol that provides per-packet key generation for WPA encryption. Operates at data link layer (Layer 2).

**Wi-Fi Protected Access (WPA)** - An encryption and authentication standard used to secure WiFi networks. Operates at data link layer (Layer 2). More secure than WEP.

**WiFi Protected Setup (WPS)** - A standard for easy and secure establishment of a wireless home network. Operates at data link layer (Layer 2). Convenience over security.

[Return to ToC](#table-of-contents)

## Routing Protocols

**Border Gateway Protocol (BGP)** - The core Internet routing protocol that maintains routing tables between autonomous systems. Operates at network layer (Layer 3).

**Exterior Gateway Protocol (EGP)** - A deprecated routing protocol that was used for exchanging routing information between autonomous systems. Operates at network layer (Layer 3).

**Open Shortest Path First (OSPF)** - A link state routing protocol used within an autonomous system to determine best path based on topology. Operates at network layer (Layer 3).

**Routing Information Protocol (RIP)** - A distance vector routing protocol that uses hop count as routing metric. Operates at network layer (Layer 3).

[Return to ToC](#table-of-contents)

## IP Networking

**Address Resolution Protocol (ARP)** - A protocol used to map IP addresses to MAC addresses in IPv4 networks. Operates at network and data link layers (Layers 2-3). 

**Content Delivery Network (CDN)** - A distributed network of servers that delivers web content faster by caching resources closer to users. Operates at application layer (Layer 7).

**Carrier Sense Multiple Access (CSMA)** - A media access method where nodes listen for traffic before transmitting on a shared medium. Operates at data link layer (Layer 2).  

**Carrier Sense Multiple Access/Collision Detection (CSMA/CD)** - An extension to CSMA where nodes also listen during transmission to detect collisions on shared media. Operates at data link layer (Layer 2).

**Duplicate Address Detection (DAD)** - A method used by IPv6 hosts to verify uniqueness of their IP addresses on a network. Operates at network layer (Layer 3).

**Dynamic Host Configuration Protocol (DHCP)** - A protocol used by hosts to automatically obtain IP addresses and other parameters from a DHCP server. Operates at application and network layers (Layers 3,7).

**Domain Name System (DNS)** - A hierarchical naming system that translates domain names to IP addresses. Operates at application layer (Layer 7).

**Domain Name System Security Extensions (DNSSEC)** - Extensions to DNS that provide authentication and integrity verification using digital signatures. Operates at application layer (Layer 7). 

**Internet Control Message Protocol (ICMP)** - A protocol used for diagnostic purposes and error reporting in IP networks. Operates at network layer (Layer 3).

**Internet Protocol (IP)** - The principal protocol used for relaying packets across interconnected networks. Operates at network layer (Layer 3). 

**Network Address Translation (NAT)** - A method of mapping multiple private IP addresses to public IP addresses via a NAT device. Operates at network layer (Layer 3).

[Return to ToC](#table-of-contents)

## Tunneling Protocols

**Generic Routing Encapsulation (GRE)** - A tunneling protocol used to encapsulate different network layer protocols inside virtual point-to-point connections. Operates at network layer (Layer 3).

**Layer 2 Tunneling Protocol (L2TP)** - A tunneling protocol used for tunneling PPP sessions and Ethernet frames. Operates at data link layer (Layer 2).

**Point-to-Point Tunneling Protocol (PPTP)** - A tunneling protocol used for establishing VPNs over IP networks. Operates at data link layer (Layer 2). 

## Network Access Control

**Extensible Authentication Protocol (EAP)** - An authentication framework supporting multiple methods like tokens, certificates, etc. Operates at data link layer (Layer 2). 

**Remote Authentication Dial-In User Service (RADIUS)** - A protocol used for remote client authentication to network access servers. Operates at application layer (Layer 7).

[Return to ToC](#table-of-contents)

## LAN Protocols

**Asynchronous Transfer Mode (ATM)** - A WAN protocol that organizes data into fixed size cells and transmits them over virtual circuits. Operates at physical and data link layers (Layers 1-2).

**Fiber Distributed Data Interface (FDDI)** - A high-speed LAN standard using fiber optic cabling. Operates at physical and data link layers (Layers 1-2).

**Frame Relay** - A WAN protocol that uses virtual circuits and variable length frames. Operates at physical and data link layers (Layers 1-2). 

**Integrated Services Digital Network (ISDN)** - A set of communication standards for simultaneous digital transmission of voice, video, and data. Operates at physical, data link and network layers (Layers 1-3).

**Logical Link Control (LLC)** - A data link layer protocol responsible for flow and error control in data link connections. Operates at data link layer (Layer 2). 

**Media Access Control (MAC)** - A sublayer of data link layer responsible for media access control mechanisms. Operates at data link layer (Layer 2).

**Metropolitan Area Network (MAN)** - A high-speed network spanning a metropolitan area up to a few hundred km. Operates at physical and data link layers (Layers 1-2). 

**Multiprotocol Label Switching (MPLS)** - A data-carrying mechanism using label switching in Layer 2 WAN networks. Operates at data link layer (Layer 2).

**Spanning Tree Protocol (STP)** - A protocol that prevents bridging loops in LANs by selectively disabling redundant paths. Operates at data link layer (Layer 2). 

**Synchronous Data Link Control (SDLC)** - A bit-oriented data link layer protocol providing duplex communication over point-to-point links. Operates at data link layer (Layer 2).

[Return to ToC](#table-of-contents)

## WAN Protocols

**Asymmetric Digital Subscriber Line (ADSL)** - A DSL broadband standard with higher download than upload speeds. Operates at physical layer (Layer 1).

**Carrier Sense Multiple Access (CSMA)** - A media access method where nodes listen for traffic before transmitting on a shared medium. Operates at data link layer (Layer 2). 

**Data Communications Equipment (DCE)** - Devices like modems used for establishing data transmission over communication channels. Operates at physical layer (Layer 1).

**Data Terminal Equipment (DTE)** - Devices like computers used for processing and displaying data. Operates at higher layers. 

**Data Service Unit/Channel Service Unit (DSU/CSU)** - A digital-interface device used to connect data terminal equipment to data transmission circuits. Operates at physical layer (Layer 1). 

**Frame Relay** - A WAN protocol that uses virtual circuits and variable length frames. Operates at physical and data link layers (Layers 1-2).

**Synchronous Digital Subscriber Line (SDSL)** - A DSL standard supporting synchronous transmission of voice and data. Operates at physical layer (Layer 1). 

**Very-high-bit-rate Digital Subscriber Line (VDSL)** - A DSL standard providing high bandwidth symmetric transmission. Operates at physical layer (Layer 1).

[Return to ToC](#table-of-contents)

## Network Monitoring and Management

**Cisco NetFlow** - A network protocol used to collect IP traffic flow data for monitoring network usage. Operates at network layer (Layer 3). 

**Network Time Protocol (NTP)** - A protocol used to synchronize clocks on computers over packet-switched networks. Operates at application layer (Layer 7).

**Simple Network Management Protocol (SNMP)** - A network management protocol used to monitor network devices from a management system. Operates at application layer (Layer 7).

[Return to ToC](#table-of-contents) 

## Network Security

**Bastion Host** - A system placed on the public perimeter of a private network to serve as the point of contact for external users. Runs at all layers.

**Content Filter** - A program used to analyze network traffic and block restricted content based on rules. Operates at application layer (Layer 7).

**Deep Packet Inspection (DPI)** - A form of packet filtering that examines data portions of packets for security and management purposes. Operates at application layer (Layer 7). 

**Demilitarized Zone (DMZ)** - A network segment that provides access to public services while protecting the private network. Operates at all layers.

**Encapsulating Security Payload (ESP)** - An IPsec protocol providing encryption and optional authentication at the IP packet level. Operates at network layer (Layer 3). 

**Host-based Intrusion Detection System (HIDS)** - Software installed on a host for identifying intrusion attempts based on system and application logs. Operates at higher layers. 

**Host-based Intrusion Prevention System (HIPS)** - Software installed on a host for detecting and preventing intrusions in real-time. Operates at higher layers.

**Intrusion Detection System (IDS)** - A network security device for identifying malicious activities through network traffic analysis. Operates at application layer (Layer 7). 

**Intrusion Prevention System (IPS)** - A network security device for real-time identification and prevention of malicious activities. Operates at application layer (Layer 7).

**MAC Filtering** - A security method that uses device MAC addresses to enforce network access control. Operates at data link layer (Layer 2). Simple to implement but easily defeated.

**Network Address Translation (NAT)** - A method of mapping multiple private IP addresses to public IP addresses via a NAT device. Operates at network layer (Layer 3). 

**Network-based Intrusion Prevention System (NIPS)** - A dedicated network appliance that analyzes traffic for threats and takes action to block detected attacks. Operates at application layer (Layer 7).

**Network Intrusion Detection System (NIDS)** - A dedicated network appliance that monitors network traffic and analyzes it for signs of intrusion attempts. Operates at application layer (Layer 7). 

**Screened Host** - A host protected from untrusted networks by an intervening screening router. Operates at network layer (Layer 3).

**Screened Subnet** - A subnet protected from external untrusted networks by an intervening screening router. Operates at network layer (Layer 3).

[Return to ToC](#table-of-contents)

## Network Storage

**Fibre Channel over IP (FCIP)** - A storage network technology that encapsulates Fibre Channel traffic over IP networks. Operates at higher layers. 

**Network Attached Storage (NAS)** - File-level storage servers connected directly to a network. Operates at higher layers.

**Storage Area Network (SAN)** - A dedicated high-speed network for connecting servers to storage devices. Operates at data link and physical layers (Layers 1-2). 

[Return to ToC](#table-of-contents)

## VoIP/Video Conferencing

**H.323** - A protocol suite providing audio-visual communication over packet-switched networks. Operates at application layer (Layer 7).

**Session Initiation Protocol (SIP)** - A signaling protocol used for initiating sessions in voice and video applications. Operates at application layer (Layer 7).

**Voice over IP (VoIP)** - Technologies for delivering voice communications over IP networks. Operates at application layer (Layer 7). 

[Return to ToC](#table-of-contents)

## Network Devices

**Bridges** - Operate at data link layer (Layer 2) to connect LAN segments.

**Gateways** - Operate at higher layers to connect dissimilar networks. 

**Hub** - Operates at physical layer (Layer 1) to connect network segments. 

**LAN Extender** - Operates at physical layer (Layer 1) to extend the reach of a LAN.

**Repeaters** - Operate at physical layer (Layer 1) to regenerate and retransmit signals over long distances.

**Routers** - Operate at network layer (Layer 3) to route packets between networks. 

**Switches** - Operate at data link layer (Layer 2) to connect devices within a LAN.

**Wireless Access Point (WAP)** - A device that allows wireless devices to connect to a wired network. Operates at physical and data link layers (Layers 1-2). Extends wireless coverage.

[Return to ToC](#table-of-contents)

## Network Attacks

**Bluebugging** - Gaining unauthorized control of a Bluetooth device. Operates at higher layers. 

**Bluejacking** - Sending unsolicited messages to Bluetooth devices. Operates at higher layers.

**Bluesnarfing** - Unauthorized access to information on a Bluetooth device. Operates at higher layers. 

**Fraggle Attack** - An attack that overloads a system by sending spoofed UDP packets to broadcasting addresses. Operates at higher layers.

**Land Attack** - Sending a packet with source and destination IP set to victim's IP, crashing the victim system. Operates at network layer (Layer 3). 

**Ping of Death** - Sending malformed ping packets that exceed maximum allowed packet size, disrupting target system. Operates at network layer (Layer 3).

**SYN Flood** - Sending a flood of TCP SYN packets to a target, exhausting connection resources and denying legitimate connections. Operates at transport layer (Layer 4).

**Teardrop Attack** - Sending mangled IP fragments to crash vulnerable systems due to a bug in fragment reassembly code. Operates at network layer (Layer 3).

[Return to ToC](#table-of-contents)

## Wireless

**Basic Service Set Identifier (BSSID)** - The MAC address of an access point in a wireless network. Uniquely identifies each BSS.

**Bluetooth** - Wireless standard for short-range communication using short-wavelength radio transmissions. Operates at physical layer (Layer 1). Provides convenience but susceptible to interference.

**Cellular Network** - Wireless network distributed over land areas called cells, each served by a fixed transmitter/receiver. Operates at physical layer (Layer 1). Provides mobility but limited capacity.

**Extended Service Set Identifier (ESSID)** - The SSID used by all access points in an extended service set.

**LiFi** - Wireless standard that uses light to transmit data over short distances. Operates at physical layer (Layer 1). Offers security but requires line of sight. 

**Near Field Communication (NFC)** - A wireless standard for close proximity communication using electromagnetic radio fields. Operates at physical layer (Layer 1). Has very short range but provides security.

**Service Set Identifier (SSID)** - The name that identifies a wireless network. Operates at data link layer (Layer 2). Should not be broadcast for security. 

**Site Survey** - Process of measuring signal coverage to determine optimal AP placement. Important for quality and security.

**SSID Broadcast** - Transmission of wireless network name for easy discovery. Convenient but a security risk. Should be disabled.

**Wi-Fi** - Wireless network technology based on the IEEE 802.11 standards. Operates at physical and data link layers (Layers 1-2). Offers flexibility but susceptible to interference.

**Wi-Fi Protected Access (WPA)** - An encryption and authentication standard used to secure WiFi networks. Operates at data link layer (Layer 2). More secure than WEP. 

**Wi-Fi Protected Access 2 (WPA2)** - A wireless security standard using AES encryption. Operates at data link layer (Layer 2). More secure than WPA.

**Wi-Fi Protected Access 3 (WPA3)** - A wireless security standard using SAE for authentication. More resilient to password attacks. Operates at data link layer (Layer 2). 

**WiMAX** - A wireless broadband standard based on IEEE 802.16. Provides network access over long distances. Operates at physical and data link layers (Layers 1-2). Offers range but requires fixed infrastructure.

**Wired Equivalent Privacy (WEP)** - A deprecated wireless security protocol that uses RC4 encryption. Operates at data link layer (Layer 2).

**Wireless Access Point (WAP)** - A device that allows wireless devices to connect to a wired network. Operates at physical and data link layers (Layers 1-2). Extends wireless coverage.

[Return to ToC](#table-of-contents)

## Virtual Networks

**Network Function Virtualization (NFV)** - Virtualization of network functions previously carried out by proprietary hardware devices. Operates at multiple layers.

**Software Defined Network (SDN)** - An approach to computer networking that allows dynamic network configuration using software. Operates at multiple layers. 

**VLAN (Virtual LAN)** - Logical grouping and isolation of network nodes even if physically connected to the same network. Operates at data link layer (Layer 2).

**VXLAN (Virtual eXtensible LAN)** -  network virtualization technology that attempts to address the scalability problems associated with large cloud computing deployments. It uses a VLAN-like encapsulation technique to encapsulate OSI layer 2 Ethernet frames within layer 4 UDP datagrams, using 4789 as the default IANA-assigned destination UDP port number.

Compared to VLAN, which provides limited number of layer-2 VLANs (typically using 12-bit VLAN ID), VXLAN increases scalability up to 16 million logical networks (with 24-bit VNID) and allows for layer-2 adjacency across IP networks.

**VPN (Virtual Private Network)** - Extends a private network across public networks to provide secure remote access. Operates at higher layers.

[Return to ToC](#table-of-contents)

## Other Common Networking Terms

**Analog** - Data represented in continuous form using waves. Used in legacy telephone systems.

**Asynchronous** - Transmission without precise clocking between sender and receiver. 

**Broadcast** - Transmission from one sender to all receivers on a subnet. Operates at data link layer (Layer 2).

**Circuit-switched** - Network that establishes a dedicated circuit for each communication session. 

**Datagram** - Protocol data unit includes the Source IP and the Destination IP(Server) and a TTL value. Associated with UDP.

**Digital** - Data represented in discrete binary form. Used in modern networks.  

**Extranet** - A controlled private network that allows access to external parties.

**Intranet** - A private network accessible only to an organization's staff. 

**Multicast** - Transmission from one sender to selected group of receivers. Operates at network layer (Layer 3). 

**Packet** - Protocol data unit that contains information about the source and destination addresses and other control information needed to transport the packet over a network. Occurs at the network layer (layer 3)

**Packet-switched** - Network that breaks data into packets sent independently over shared channels. 

**Polling** - Nodes query each other for data, rather than transmitting spontaneously.

**Segment** - Protocol data unit used in TCP connections. Occurs at the transport layer (layer 4). 

**Synchronous** - Transmission with precise clocking between sender and receiver.

**Token Passing** - Method where possession of a token grants the right to transmit over a shared channel. Operates at data link layer (Layer 2).

**Unicast** - Transmission from one sender to one receiver.

[Return to ToC](#table-of-contents)