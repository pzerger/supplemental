Here is the document with a table of contents added:

# Table of Contents
- [Categories](#categories)
  - [Hardware Firewall](#hardware-firewall)
  - [Software Firewall](#software-firewall)
  - [Host-based Firewall](#host-based-firewall) 
  - [Virtual Firewall](#virtual-firewall)
  - [Open Source Firewall](#open-source-firewall)
  - [Proprietary Firewall](#proprietary-firewall)
- [Functionality](#functionality)
  - [Stateless Firewall](#stateless-firewall)
  - [Stateful Firewall](#stateful-firewall)
  - [Stateful Inspection Firewall](#stateful-inspection-firewall)
  - [Static Packet-Filtering Firewall](#static-packet-filtering-firewall)
  - [Deep Packet Inspection Firewall](#deep-packet-inspection-firewall)  
- [Types](#types)
  - [Unified Endpoint Management (UEM)](#unified-endpoint-management-uem)
  - [Unified Threat Management (UTM)](#unified-threat-management-utm)
  - [Network Function Virtualization (NFV)](#network-function-virtualization-nfv)
  - [Next Generation Firewall (NGFW)](#next-generation-firewall-ngfw)
  - [Web Application Firewall (WAF)](#web-application-firewall-waf)
  - [Application Firewall](#application-firewall)
  - [Application-Level Firewall](#application-level-firewall)
  - [Circuit-Level Firewall](#circuit-level-firewall)
  - [Content/URL Filter](#contenturl-filter)

# Firewall Concepts and Types

Firewalls serve as a critical security component for protecting networks and systems from unauthorized and potentially malicious access. They work by defining, enforcing, and auditing network communication rules based on various criteria like source and destination IP addresses, ports, protocols, and other packet attributes.

## Categories

### Hardware Firewall
- **Definition**: A physical device dedicated to filtering network traffic.
- **Features**:
  - Standalone appliance, often rack-mounted.
  - High performance, reliability, and scalability.
  - Typically protects the network's perimeter.

### Software Firewall
- **Definition**: Software installed on a system to filter its network traffic.
- **Features**:
  - Installed on an existing OS (e.g., Windows, Linux).
  - Common on end-user devices for personal protection.
  - Offers granularity in configuration per device.
  - Easier for attackers to disable, often simply disabling a service.

### Host-based Firewall
- **Definition**: Firewall software installed on a single host or device.
- **Features**:
  - Protects only that specific host.
  - Often used in conjunction with other security measures.
  - Examples include Windows Firewall, iptables.

### Virtual Firewall
- **Definition**: A firewall instance that operates within virtualized environments.
- **Features**:
  - Designed for cloud and virtualized data centers.
  - Isolates and protects virtual network resources.
  - Can be hardware-assisted or purely software-based.

### Open Source Firewall
- **Definition**: Firewall software whose source code is publicly available.
- **Features**:
  - Allows users to review, modify, and distribute the code.
  - Examples include pfSense, iptables, and OpenWrt.

### Proprietary Firewall
- **Definition**: Firewall software or hardware owned by an entity and not publicly available.
- **Features**:
  - Source code is closed and proprietary.
  - Often comes with vendor support.
  - Examples include Cisco ASA, Palo Alto Networks Firewall.

  [Back to ToC](#cyber-attacks)

## Functionality

### Stateless Firewall
- **Definition**: Filters packets without maintaining context about active connections. 
- **Features**:
  - Uses static rules based on source and destination attributes.
  - Does not keep track of the state of network connections.
  - Faster but less secure.

### Stateful Firewall  
- **Definition**: Filters packets based on state and context of active connections.
- **Features**:
  - Remembers previous decisions for current ongoing connections.
  - Only allows inbound traffic if it matches an active session.
  
### Stateful Inspection Firewall
- **Definition**: Inspects the state and attributes of traffic to make filtering decisions.
- **Features**: 
  - A combination of stateless and stateful firewalls.
  - Evaluates packet contents as well as their state.
  - Can make more intelligent decisions based on traffic patterns.
  
### Static Packet-Filtering Firewall
- **Definition**: Uses pre-defined rules to allow or deny packets.
- **Features**:
  - Operates mostly at the network layer.
  - Does not keep track of connections. 
  - Less complex but can be vulnerable to certain attacks.
  
### Deep Packet Inspection Firewall
- **Definition**: Examines the data part of a packet deeply to make filtering decisions.  
- **Features**:
  - Can identify and block specific content, applications, or protocols.
  - Works at the application layer and can understand application protocols.
  - Used for intrusion prevention and application filtering.

  [Back to ToC](#cyber-attacks)

## Types  

### Unified Endpoint Management (UEM)
- **Definition**: Manages and secures endpoints like smartphones, laptops, and tablets from a single console.  
- **Relation to Firewalls**: Not a firewall type per se, but UEM often includes firewall features for endpoint protection.

### Unified Threat Management (UTM)  
- **Definition**: A single solution that combines multiple security features, including firewall, anti-virus, and intrusion prevention.
- **Features**:
  - Simplified security infrastructure.
  - Firewall is one component among others.
  
### Network Function Virtualization (NFV)
- **Definition**: Virtualizes network services traditionally run on proprietary hardware. 
- **Relation to Firewalls**: Virtual firewalls can be a part of NFV, offering firewall services in a virtualized infrastructure.

### Next Generation Firewall (NGFW)
- **Definition**: Combines traditional firewall capabilities with modern features like application awareness and deep packet inspection.
- **Features**:
  - Understands and can filter based on application usage.
  - Often includes intrusion prevention systems (IPS).
  - Ingests external threat intelligence to identify and counteract novel threats.
  
### Web Application Firewall (WAF)
- **Definition**: Protects web applications by monitoring and filtering HTTP traffic.
- **Features**:
  - Targets threats specific to web applications, like SQL injection or cross-site scripting (XSS).
  - Can be hardware-based, software-based, or cloud-based.
  - Often uses OWASP core rulesets to detect and defend against common web vulnerabilities.
  
### Application Firewall  
- **Definition**: Filters traffic based on specific applications rather than ports or protocols.
- **Features**:
  - Understands specific application protocols.
  - Can allow or block specific application features.
  
### Application-Level Firewall
- **Definition**: Operates at the application layer of the OSI model to filter incoming traffic.
- **Features**:
  - Makes decisions based on the content of the data.
  - Can understand specific application protocols and behaviors.
  
### Circuit-Level Firewall
- **Definition**: Operates at the session layer of the OSI model.  
- **Features**:
  - Decides on allowing or blocking a session based on the handshake between packets.
  - Often used in conjunction with other firewall types.
  
### Content/URL Filter 
- **Definition**: Filters web content based on URLs or content criteria.
- **Features**:
  - Often used to block access to specific websites or categories.
  - Can be integrated into other firewalls or be standalone.

  [Back to ToC](#cyber-attacks)