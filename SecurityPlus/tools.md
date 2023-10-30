# Tools

## Table of Contents
- [Network reconnaissance and discovery](#network-reconnaissance-and-discovery)
- [File manipulation](#file-manipulation)
- [Shell and script environments](#shell-and-script-environments)
- [Packet capture and replay](#packet-capture-and-replay)
- [Forensics](#forensics)
- [Exploitation frameworks](#exploitation-frameworks)

## Network reconnaissance and discovery

- **Tracert/Traceroute**: Shows the route taken from a computer to a remote host such as a website and response latency (in ms) at each hop.
- **Nslookup/Dig**: Diagnostic tools for verifying the IP address of a hostname in the DNS server database. 'set type=MX' scopes search to mail exchange records; Dig is the Unix/Linux equivalent.
- **Ipconfig/Ifconfig**: Commands that show the IP configuration. The Windows version is ipconfig, while Unix/Linux uses ifconfig.
- **Nmap**: A free and open-source network mapper used for inventorying devices on your network and banner grabbing.
- **Ping/Pathping**: Tools to test the reachability of a host on an IP network. Pathping also calculates packet loss at each router (hop) after the trace.
- **Hping**: An open-source packet generator and analyzer for the TCP/IP protocol, often used for auditing firewalls and networks.
- **Netstat**: Displays established connections, listening ports, and running services.
- **Netcat**: A utility for network connections, port scanning, and file transfer.
- **IP Scanners**: Scan addresses in a range and identify open ports. The Angry IP scanner is a popular tool that exports results in various formats.
- **Arp**: A protocol for mapping an IP address to a MAC address on a local area network. The 'arp -a' command shows the ARP cache.
- **Route**: Manages the routing table, including listing and adding routes.
- **Curl**: A command-line tool for data transfer using various protocols.
- **TheHarvester**: A passive tool that harvests the email addresses of an organization.
- **Sn1per**: A reconnaissance tool for automated vulnerability scanning and attack surface discovery.
- **Scanless**: A pen-testing tool for performing anonymous open port scans.
- **Dnsenum**: Identifies DNS records and attempts reverse DNS resolution.
- **Nessus**: A network vulnerability scanner that raises alerts for vulnerabilities that could be exploited.
- **Cuckoo**: Creates a sandbox for analyzing files for malware inspection.

## File manipulation

- **Concatenate (Cat)**: Creates, views, and concatenates files. Example: 
`cat file1.txt file2.txt file3.txt | sort > samplefile.txt`.

- **Head**: Views the top lines of a file, useful for checking system events like shutdowns and reboots. 
Example: `head /var/log/messages -n 10`.

- **Tail**: Views the last lines at the end of a file. 
Example: `tail /var/log/messages -n 10`.

- **Grep**: Searches text and log files for specific values. Example: `grep -r project` to search a directory for the word 'project'.

- **Chmod**: Changes the permission level of files. 
Example: `chmod 766` where the owner has rwx, the group has rw-, and others have rw-.

- **Logger**: Adds messages to the local system log file or a remote syslog server. Example: 
`logger -n 10.10.10.10 'hostname’ found a potential backdoor attack`.

## Shell and script environments

- **SSH**: A secure alternative to telnet for running commands remotely; encrypts traffic.
- **PowerShell**: Performs tasks in a Windows environment with cmdlets that can be saved to a script with a .ps1 extension.
- **Python**: A popular programming language used by developers and data scientists.
- **OpenSSL**: Manages TLS and SSL protocols, often used to generate private keys and install certificates.

## Packet capture and replay

- **Tcpreplay**: Analyzes .pcap files and replays traffic to the NIPS.
- **Tcpdump**: A network packet analyzer command-line tool on Linux/UNIX.
- **Wireshark**: A packet analyzer with both command-line and GUI versions for Windows and Linux.

## Forensics

- **dd**: Clones a disk or copies a folder in a Linux/Unix environment.
- **Memdump**: Captures system memory for analysis.
- **WinHex**: A hexadecimal editor for forensics teams to find and recover data.
- **FTK Imager**: Assesses electronic evidence for forensic analysis.
- **Autopsy**: Analyzes hard drives, smartphones, and media cards with built-in language translation.

## Exploitation frameworks

- **Password crackers**: Tools used to recover passwords through methods such as brute force, dictionary attacks, and rainbow tables.
- **Data sanitization**: Processes to remove sensitive information from storage devices to prevent unauthorized recovery and use.
