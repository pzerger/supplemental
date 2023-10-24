# Protocols, Functions, and Ports

**Address Resolution Protocol (ARP)**
- **Function**: Resolves IP addresses to MAC addresses.
- **Ports**: Not applicable as it operates at the data link layer.

**Authentication Header (AH)**
- **Function**: Provides connectionless data integrity and data origin authentication for IP datagrams.
- **Ports**: Not applicable, part of the IPSec suite.

**Border Gateway Protocol (BGP)**
- **Function**: A core routing protocol that makes routing decisions based on paths, network policies, or rule-sets.
- **Ports**: Standard: TCP 179.

**Challenge-Handshake Authentication Protocol (CHAP)**
- **Function**: Authenticates a user or network host to an authenticating entity.
- **Ports**: Used in PPP which operates over serial connection, hence no specific ports.

**Counter-Mode (CTR)**
- **Function**: A block cipher mode of operation where each block of plaintext is XORed with an encrypted counter.
- **Ports**: Not applicable, encryption method.

**Counter-Mode/CBC-MAC Protocol (CCMP)**
- **Function**: An encryption protocol designed for Wireless LAN products that implement the standards of the IEEE 802.11i amendment to the original IEEE 802.11.
- **Ports**: Not applicable, encryption method.

**Datagram Delivery Protocol (DDP)**
- **Function**: A member of the AppleTalk suite, providing connectionless data delivery service.
- **Ports**: Not applicable, layer 2 service.

**Distributed Network Protocol (DNP3)**
- **Function**: A set of communications protocols used between components in process automation systems.
- **Ports**: Not commonly assigned a standard port.

**Domain Keys Identified Mail (DKIM)**
- **Function**: Email authentication method designed to detect forged sender addresses in emails.
- **Ports**: Not applicable, SMTP-based service.

**Domain Name System Security Extensions (DNSSEC)**
- **Function**: Adds cryptographic signatures to existing DNS data to ensure its authenticity.
- **Ports**: Not specifically for DNSSEC but DNS primarily uses UDP 53.

**Dynamic Host Configuration Protocol (DHCP)**
- **Function**: Assigns IP addresses dynamically to devices on a network.
- **Ports**: UDP 67 (server), UDP 68 (client).

**Extensible Authentication Protocol (EAP)**
- **Function**: An authentication framework frequently used in wireless networks and point-to-point connections.
- **Ports**: Operates over the Data Link Layer, so no specific ports.

**Exterior Gateway Protocol (EGP)**  
- **Function**: A deprecated routing protocol for determining routes between hosts.
- **Ports**: UDP 8.

**Fibre Channel over IP (FCIP)**
- **Function**: Maps Fibre Channel over TCP/IP networks.
- **Ports**: TCP 3225.

**File Transfer Protocol (FTP)**
- **Function**: Used for transferring files between a client and server.
- **Ports**: Standard: TCP 20 (data), TCP 21 (control).

**Generic Routing Encapsulation (GRE)**
- **Function**: Tunnels packets from one protocol inside packets of another protocol.
- **Ports**: Protocol number 47 (no specific port number).

**High-Level Data Link Control (HDLC)**
- **Function**: Provides synchronous data link layer communication.
- **Ports**: Not applicable, data link layer protocol.

**Hypertext Transfer Protocol Secure (HTTPS)**
- **Function**: Secure version of HTTP using encryption.
- **Ports**: Standard: TCP 443.

**Internet Control Message Protocol (ICMP)** 
- **Function**: Used by network devices to send error messages and operational information.
- **Ports**: Not applicable, part of the Internet Protocol Suite.

**Internet Engineering Task Force (IETF)**
- **Function**: Not a protocol. It's an organization that develops and promotes Internet standards.
- **Ports**: Not applicable.

**Internet Key Exchange (IKE)**
- **Function**: Sets up a security association in the IPsec protocol suite.
- **Ports**: UDP 500.

**Internet Message Access Protocol v4 (IMAP4)**
- **Function**: Protocol for retrieving email messages.
- **Ports**: Standard: TCP 143. Secure (over SSL): TCP 993.

**Internet Protocol (IP)**
- **Function**: Primary protocol in the Internet layer of the Internet Protocol Suite for relaying datagrams across network boundaries. 
- **Ports**: Not applicable, operates at the network layer.

**Internet Protocol Security (IPSec)**
- **Function**: Provides authentication, integrity, and confidentiality to IP packets.
- **Ports**: Protocol numbers: AH (51), ESP (50).

**Layer 2 Tunneling Protocol (L2TP)**
- **Function**: A tunneling protocol used to support VPNs.
- **Ports**: UDP 1701.

**Lightweight Directory Access Protocol (LDAP)**
- **Function**: Protocol for accessing and maintaining directory services.
- **Ports**: Standard: TCP/UDP 389. Secure (over SSL): TCP 636.

**Lightweight Extensible Authentication Protocol (LEAP)**
- **Function**: A proprietary wireless LAN authentication method.
- **Ports**: Not applicable, authentication method for WLAN.

**Microsoft Challenge-Handshake Authentication Protocol (MS-CHAP)**
- **Function**: Microsoft's version of the CHAP authentication method.
- **Ports**: Used in PPP, hence no specific ports.

**Multipurpose Internet Mail Extensions (MIME)**
- **Function**: Specifies a method for constructing multipart message bodies in emails.
- **Ports**: Not applicable, extension to the SMTP protocol.

**Near Field Communication (NFC)**
- **Function**: A set of communication protocols for communication between two electronic devices over a distance of 4 cm or less.
- **Ports**: Not applicable, wireless communication standard.

**Network Time Protocol (NTP)**
- **Function**: Synchronizes the clocks of computer systems over packet-switched, variable-latency data networks.
- **Ports**: UDP 123.

**Open Shortest Path First (OSPF)**
- **Function**: A routing protocol for IP networks.
- **Ports**: IP protocol number 89.  

**Packet-switched network protocols**
- **Function**: A type of communication in which packets are routed based on destination address.
- **Ports**: Various depending on specific protocols.

**Password Authentication Protocol (PAP)**
- **Function**: A simple, plaintext authentication scheme.  
- **Ports**: Used in PPP, so no specific ports.

**Point-to-Point Protocol (PPP)**
- **Function**: Provides communication over direct connection.
- **Ports**: Operates over serial connection, hence no specific ports.

**Point-to-Point Tunneling Protocol (PPTP)**
- **Function**: Encapsulates PPP frames into IP datagrams for transmission over a network.
- **Ports**: TCP 1723.

**Post Office Protocol (POP)**
- **Function**: An Internet standard protocol used by email clients to retrieve email from a server.
- **Ports**: Standard: TCP 110. Secure (over SSL): TCP 995.

**Protected Extensible Authentication Protocol (PEAP)**
- **Function**: A method for transmitting authentication data, including passwords, over wireless LAN networks.
- **Ports**: Not applicable, authentication method for WLAN.

**Real Time Control Protocol (RTCP)**
- **Function**: Provides feedback on the quality of service being provided by RTP.
- **Ports**: Typically an odd-numbered port one higher than the associated RTP port.

**Real Time Protocol (RTP)**
- **Function**: Used for delivering audio and video over IP networks.
- **Ports**: UDP. Range typically between 16384–32767.

**Remote Access Server (RAS)**
- **Function**: A server that provides remote access connectivity.
- **Ports**: Varies depending on the service.

**Remote Authentication Dial-In User Service (RADIUS)**
- **Function**: Provides centralized Authentication, Authorization, and Accounting management for users who connect to a network.
- **Ports**: UDP 1812 (authentication), UDP 1813 (accounting).

**Remote Desktop Protocol (RDP)**
- **Function**: Allows users to remotely connect to another computer. 
- **Ports**: TCP/UDP 3389.

**Remote Procedure Call (RPC)**
- **Function**: Allows execution of code on a remote server.
- **Ports**: TCP 135.

**Reverse Address Resolution Protocol (RARP)**
- **Function**: Determines an IP address from a given hardware address.
- **Ports**: Not applicable, part of the data link layer.

**Routing Information Protocol (RIP)**
- **Function**: Used by routers to exchange routing information.  
- **Ports**: UDP 520.

**Secure Hypertext Transfer Protocol (S-HTTP)**
- **Function**: An alternative to HTTPS for encrypting web communications.
- **Ports**: Standard: TCP 80. Secure: Typically TCP 443.

**Secure Real-time Transport Protocol (SRTP)**
- **Function**: Provides encryption, message authentication, and replay protection to RTP.
- **Ports**: UDP. Typically in the range 16384–32767.

**Secure Shell (SSH)**
- **Function**: Protocol for operating network services securely over an unsecured network.
- **Ports**: TCP 22.

**Secure Sockets Layer (SSL)**
- **Function**: Provides cryptographic security for communications over networks.
- **Ports**: Not applicable directly, but typically associated with HTTPS on TCP 443.

**Secured File Transfer Protocol (SFTP)**
- **Function**: A secure version of FTP, encapsulated over SSH. 
- **Ports**: TCP 22.

**Serial Line Internet Protocol (SLIP)**
- **Function**: An older protocol used for point-to-point serial connections.
- **Ports**: Not applicable, data link layer protocol. 

**Server Message Block (SMB)**
- **Function**: Provides shared access to files, printers, and serial ports.
- **Ports**: TCP 445 (direct over IP), TCP 137-139 (over NetBIOS).

**Session Initiation Protocol (SIP)**
- **Function**: Signaling protocol used for initiating, maintaining, modifying and terminating real-time sessions.
- **Ports**: Standard: UDP/TCP 5060. Secure (over TLS): UDP/TCP 5061.

**Short Message Service (SMS)**
- **Function**: A text messaging service component.
- **Ports**: Not applicable, wireless communication standard.

**Simple Mail Transfer Protocol (SMTP)**
- **Function**: Protocol for email transmission.
- **Ports**: Standard: TCP 25. Secure (over TLS/SSL): TCP 465.

**Simple Network Management Protocol (SNMP)**
- **Function**: Used for managing devices on IP networks.
- **Ports**: Standard: UDP 161 (agent), UDP 162 (manager). 

**Simple Object Access Protocol (SOAP)**
- **Function**: Protocol specification for exchanging structured information in web services.
- **Ports**: Typically over HTTP (TCP 80) or HTTPS (TCP 443).

**Simultaneous Authentication of Equals (SAE)**
- **Function**: Authentication mechanism used in WPA3 Wi-Fi security.
- **Ports**: Not applicable, wireless security method.

**Spanning Tree Protocol (STP)**
- **Function**: Prevents loops in networks with redundant paths.  
- **Ports**: Not applicable, data link layer protocol.

**Synchronous Data Link Control (SDLC)**
- **Function**: IBM's layer 2 protocol for Systems Network Architecture.
- **Ports**: Not applicable, data link layer protocol. 

**Temporal Key Integrity Protocol (TKIP)**
- **Function**: An encryption protocol included as part of the IEEE 802.11i standard for WLANs.
- **Ports**: Not applicable, encryption method.

**Terminal Access Controller Access Control System (TACACS)**
- **Function**: Remote authentication protocol primarily used for network devices.  
- **Ports**: TCP/UDP 49.

**Transmission Control Protocol (TCP)**
- **Function**: One of the main transport layer protocols in the TCP/IP suite.
- **Ports**: Various depending on application layer protocol.

**Transmission Control Protocol/Internet Protocol (TCP/IP)**
- **Function**: The foundational suite of protocols for the Internet.
- **Ports**: Various depending on specific protocol within the suite.

**Transport Layer Security (TLS)**
- **Function**: Successor to SSL, provides cryptographic security for communications over networks.  
- **Ports**: Not applicable directly, but typically associated with HTTPS on TCP 443.

**Trivial File Transfer Protocol (TFTP)**
- **Function**: A simple file transfer protocol.
- **Ports**: UDP 69.

**Trusted Automated eXchange of Intelligence Information (TAXII)**
- **Function**: A protocol used for the exchange of cyber threat information.
- **Ports**: Typically over HTTP (TCP 80) or HTTPS (TCP 443).

**User Datagram Protocol (UDP)**
- **Function**: One of the main transport layer protocols in the TCP/IP suite, connectionless communication.
- **Ports**: Various depending on application layer protocol. 

**Wi-Fi Protected Access (WPA)**
- **Function**: A security protocol for wireless networks.
- **Ports**: Not applicable, wireless security method.

**Wired Equivalent Privacy (WEP)**  
- **Function**: An early security algorithm for WLANs.
- **Ports**: Not applicable, wireless security method.