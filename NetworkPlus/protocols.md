# Protocols for CompTIA Network+ Exam

# Table of Contents
- [Authentication](#authentication)
- [Network Addressing (DHCP)](#network-addressing-dhcp)
- [Name Resolution (DNS)](#name-resolution-dns)


## Authentication
Authentication is the process of verifying the identity of a user, device, or system before granting access to network resources. Various authentication methods are used to ensure secure access control.

### Authentication Methods: 802.1X
802.1X is an IEEE standard for port-based network access control. It provides authentication and authorization for devices connecting to a network switch port, ensuring that only authenticated devices can access the network.

### Authentication Methods: EAP
Extensible Authentication Protocol (EAP) is a framework for authentication that supports multiple authentication methods. It is commonly used in wireless networks and point-to-point connections.

### Authentication Methods: Kerberos
Kerberos is a network authentication protocol that uses tickets and symmetric-key cryptography to provide secure authentication for client/server applications.

### Authentication Methods: LDAP
Lightweight Directory Access Protocol (LDAP) is a protocol for accessing and maintaining distributed directory information services. It is often used for authentication and authorization purposes.

### Authentication Methods: Local
Local authentication refers to the use of locally stored credentials, such as username and password, to authenticate users or devices.

### Authentication Methods: Multifactor
Multifactor authentication (MFA) involves using two or more authentication factors, such as something you know (password), something you have (token), or something you are (biometrics), to verify identity.

### Authentication Methods: RADIUS
Remote Authentication Dial-In User Service (RADIUS) is a client/server protocol that provides centralized authentication, authorization, and accounting (AAA) management for users connecting to a network service.

### Authentication Methods: SSO
Single Sign-On (SSO) is an authentication method that allows users to access multiple applications or services with a single set of credentials, eliminating the need to log in separately for each resource.

### Authentication Methods: TACACS+
Terminal Access Controller Access-Control System Plus (TACACS+) is a protocol that provides centralized authentication, authorization, and accounting (AAA) services for network devices.

[Back to ToC](#table-of-contents)

## Network Addressing (DHCP)
Dynamic Host Configuration Protocol (DHCP) is a network management protocol used to dynamically assign IP addresses and other network configuration parameters to devices on a network.

### DCHP Concepts: DHCP relay
A DHCP relay, also known as a DHCP helper, is a network device or service that forwards DHCP requests from clients to a DHCP server located on a different subnet.

### DCHP Concepts: Dynamic assignment
Dynamic assignment refers to the automatic allocation of IP addresses to devices by a DHCP server from a predefined pool of addresses.

### DCHP Concepts: Exclusion ranges
Exclusion ranges are a set of IP addresses within a DHCP scope that are excluded from being assigned to clients. These addresses are typically reserved for static assignment or other purposes.

### DCHP Concepts: IP helper/UDP forwarding
IP helper, also known as UDP forwarding, is a feature that allows a router to forward DHCP requests and other broadcast traffic across different subnets to a specific destination, such as a DHCP server.

### DCHP Concepts: Lease time
Lease time is the duration for which an IP address is assigned to a client by a DHCP server. After the lease time expires, the client must renew the lease or obtain a new IP address.

### DCHP Concepts: Reservation
DHCP reservation is a feature that allows a DHCP server to assign a specific IP address to a particular device based on its MAC address, ensuring that the device always receives the same IP address.

### DCHP Concepts: Scope
A DHCP scope is a range of IP addresses that a DHCP server can assign to clients within a specific network segment.

### DCHP Concepts: Scope options
Scope options are additional configuration parameters, such as default gateway, DNS server, and subnet mask, that a DHCP server can assign to clients along with an IP address.

### DCHP Concepts: Static assignment
Static assignment refers to the manual configuration of IP addresses on devices, rather than using DHCP for dynamic assignment. Static assignment is typically used for devices that require a consistent IP address, such as servers or network printers.

[Back to ToC](#table-of-contents)

## Name Resolution (DNS)
Domain Name System (DNS) is a hierarchical and decentralized naming system that translates human-readable domain names into IP addresses, enabling devices to locate and communicate with each other on the internet or private networks.

### DNS
DNS is a protocol that associates various information with domain names assigned to each of the participating entities. It serves as a phone book for the internet, allowing users to access websites using easy-to-remember domain names instead of IP addresses.

### DNS Concepts: A Record
An A (Address) record is a DNS resource record that maps a domain name to an IPv4 address.
> Example: `www.example.com. IN A 192.0.2.1`

### DNS Concepts: AAAA Record
An AAAA (Quad-A) record is a DNS resource record that maps a domain name to an IPv6 address.
> Example: `www.example.com. IN AAAA 2001:db8::1`

### DNS Concepts: Authoritative Name Servers
An authoritative name server is a DNS server that holds the definitive information about a specific domain and is responsible for providing answers to queries about that domain.

Primary DNS Server: The primary DNS server is the authoritative server that holds the master copy of the zone file for a domain. It is responsible for updating the zone file and propagating changes to secondary DNS servers.

Secondary DNS Server: A secondary DNS server is a backup authoritative server that receives a copy of the zone file from the primary DNS server. It helps distribute the load and ensures redundancy in case the primary server fails.

### DNS Concepts: Caching
DNS caching is the process of storing DNS query results in a temporary database on a DNS server or client machine to improve performance and reduce network traffic.

### DNS Concepts: CNAME Record
A CNAME (Canonical Name) record is a DNS resource record that maps an alias name to a canonical (true) domain name.
> Example: `alias.example.com. IN CNAME www.example.com.`

### DNS Concepts: Local Caching Resolver
A local caching resolver is a DNS server that stores DNS query results in its cache and responds to client queries from the cache, reducing the need to query other DNS servers.

### DNS Concepts: MX Record
An MX (Mail Exchange) record is a DNS resource record that specifies the mail server responsible for accepting email messages on behalf of a domain.
> Example: `example.com. IN MX 10 mail.example.com.`

### DNS Concepts: Name resolution
Name resolution is the process of translating a domain name into an IP address or vice versa.

### DNS Concepts: NS Record
An NS (Name Server) record is a DNS resource record that specifies the authoritative name servers for a domain.
> Example: `example.com. IN NS ns1.example.com.`

### DNS Concepts: PTR Record
A PTR (Pointer) record is a DNS resource record used in reverse DNS lookups to map an IP address to a domain name.
> Example: `1.2.0.192.in-addr.arpa. IN PTR www.example.com.`

### DNS Concepts: Record types
DNS record types are different types of resource records in the DNS database, such as A, AAAA, CNAME, MX, NS, PTR, SOA, SRV, and TXT records, each serving a specific purpose.

### DNS Concepts: Recursive vs iterative queries
In a recursive DNS query, a DNS client requires the DNS server to respond with either the requested resource record or an error message. In an iterative query, the DNS server returns the best answer it has, which may be a referral to another DNS server.

### DNS Concepts: Root DNS Servers
Root DNS servers are the top-level DNS servers in the hierarchical DNS system. They are responsible for directing queries to the appropriate Top-Level Domain (TLD) servers.

### DNS Concepts: SOA Record
An SOA (Start of Authority) record is a DNS resource record that provides essential information about a DNS zone, such as the primary name server, the email address of the domain administrator, and timers relating to the zone.
> Example: `example.com. IN SOA ns1.example.com. admin.example.com. 2023040700 3600 900 604800 86400`

### DNS Concepts: SRV Record
An SRV (Service) record is a DNS resource record that specifies the location of services for a domain, such as servers for specific protocols like SIP or XMPP.
> Example: `_sip._tcp.example.com. IN SRV 10 60 5060 sip.example.com.`

### DNS Concepts: TLD Servers
Top-Level Domain (TLD) servers are responsible for handling queries for specific top-level domains, such as .com, .org, or .net.

### DNS Concepts: TTL
Time to Live (TTL) is a value in a DNS record that specifies how long a DNS response should be cached by a DNS resolver before it expires and a new query is needed.

### DNS Concepts: TXT Record
A TXT (Text) record is a DNS resource record that allows domain administrators to add arbitrary text to the DNS database, often used for email authentication protocols like SPF or DKIM.
> Example: `example.com. IN TXT "v=spf1 ip4:192.0.2.0/24 -all"`

### DNS Concepts: Zone transfers
A zone transfer is the process of copying the contents of a DNS zone from a primary DNS server to a secondary DNS server to ensure redundancy and load balancing.

### DNS Concepts: Zones
A DNS zone is a portion of the DNS namespace that is managed by a specific organization or administrator. It includes resource records for all the domain names within that zone.

[Back to ToC](#table-of-contents)