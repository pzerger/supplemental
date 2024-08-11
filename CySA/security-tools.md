# Security Tools

Security tools mentioned in the CompTIA CySA+ (CS0-003) exam syllabus or Sybex official study guide.

## Table of Contents
- [Forensics](#forensics)
- [Logging and Monitoring](#logging-and-monitoring)
- [Network](#network)
- [Cloud](#cloud)
- [Vulnerability Management](#vulnerability-management)
- [Threat Intelligence](#threat-intelligence)

## Forensics

| Tool | Description | Where to Find/Download |
|------|-------------|------------------------|
| **AccessChk** | A Windows command-line tool for viewing the security descriptors of files, registry keys, services, processes, and other objects. | [Microsoft Sysinternals](https://docs.microsoft.com/en-us/sysinternals/downloads/accesschk) |
| **Autopsy** | An open-source digital forensics platform for analyzing hard drives and smart phones. | [Autopsy Website](https://www.autopsy.com/download/) |
| **CAINE** | Computer Aided INvestigative Environment, a Linux distro created for digital forensics. | [CAINE Official Website](https://www.caine-live.net/) |
| **dd utility** | A command-line utility for Unix and Unix-like operating systems, used for low-level copying and conversion of raw data. | Pre-installed on most Unix-like systems |
| **DumpIt** | A Windows memory acquisition tool that generates a physical memory dump of a Windows machine. | [Comae Technologies](https://www.comae.com/) |
| **EnCase** | A suite of digital forensics tools used to gather and analyze digital evidence. | [OpenText EnCase](https://security.opentext.com/encase-forensic) |
| **fmem** | A Linux kernel module that creates a device to capture volatile memory. | [GitHub - fmem](https://github.com/NateBrune/fmem) |
| **forensic drive duplicators** | Hardware devices designed to create exact bit-for-bit copies of storage media for forensic analysis. | Various vendors (e.g., Logicube, Tableau) |
| **SIFT** | SANS Investigative Forensic Toolkit, a collection of free and open-source incident response and forensic tools. | [SANS SIFT Workstation](https://www.sans.org/tools/sift-workstation/) |
| **USB Historian** | A tool for analyzing USB device usage on Windows systems. | [GitHub - USB Historian](https://github.com/woanware/usbhistorian) |
| **Volatility Framework** | An open-source memory forensics framework for incident response and malware analysis. | [Volatility Foundation](https://www.volatilityfoundation.org/releases) |

## Logging and Monitoring

| Tool | Description | Where to Find/Download |
|------|-------------|------------------------|
| **Elasticsearch, Logstash, and Kibana (ELK)** | A set of open-source tools for searching, analyzing, and visualizing log data in real time. | [Elastic Stack](https://www.elastic.co/elastic-stack/) |
| **Log analysis tools** | Software designed to collect, parse, and analyze log files from various sources to identify patterns, anomalies, or security incidents. | Various vendors (e.g., Splunk, LogRhythm) |
| **Performance Monitor (perfmon)** | A Windows administrative tool that provides detailed information about the performance of various system components. | Pre-installed on Windows systems |
| **PostgreSQL Workload Analyzer (PoWA)** | An open-source PostgreSQL workload analyzer that collects and stores performance data. | [PoWA GitHub](https://github.com/powa-team/powa) |
| **Splunk** | A software platform for searching, monitoring, and analyzing machine-generated big data via a web-style interface. | [Splunk Website](https://www.splunk.com/) |
| **Sysinternals suite** | A set of Windows system utilities and technical information to manage, diagnose, troubleshoot, and monitor a Windows environment. | [Microsoft Sysinternals](https://docs.microsoft.com/en-us/sysinternals/) |
| **Log analysis/correlation** | Various software solutions designed to collect, aggregate, and analyze log data from multiple sources to identify patterns and anomalies. | Various vendors (e.g., LogRhythm, AlienVault) |
| **Tripwire** | A security and data integrity tool used for monitoring and alerting on file changes. | [Tripwire Website](https://www.tripwire.com/) |

## Network

| Tool | Description | Where to Find/Download |
|------|-------------|------------------------|
| **Angry IP Scanner** | A fast and feature-rich IP address and port scanner. | [Angry IP Scanner Website](https://angryip.org/) |
| **Bash** | A Unix shell and command language used for various network-related tasks and scripting. | Pre-installed on most Unix-like systems |
| **Burp Proxy** | A web proxy tool used for security testing of web applications. | [PortSwigger Burp Suite](https://portswigger.net/burp) |
| **grep command** | A command-line utility for searching plain-text data sets for lines that match a regular expression. | Pre-installed on most Unix-like systems |
| **iPerf** | A tool for active measurements of the maximum achievable bandwidth on IP networks. | [iPerf Website](https://iperf.fr/) |
| **J-Flow** | A network protocol for collecting IP traffic information and monitoring network usage. | Implemented in Juniper Networks devices |
| **netcat** | A versatile networking utility for reading from and writing to network connections using TCP or UDP. | Pre-installed on most Unix-like systems |
| **netstat** | A command-line network utility that displays network connections, routing tables, and network interface statistics. | Pre-installed on most operating systems |
| **nmap** | A free, open-source tool used to discover hosts, services, and vulnerabilities on a network. | [Nmap Website](https://nmap.org/) |
| **packet sniffer** | Software or hardware that can intercept and log traffic passing over a network. | Various tools (e.g., Wireshark, tcpdump) |
| **Tcpdump** | A powerful command-line packet analyzer. | Pre-installed on most Unix-like systems |
| **Network scanning and mapping** | Various software solutions used to discover and map out network topology, devices, and services. | Various vendors (e.g., SolarWinds, Spiceworks) |
| **Wireshark** | A widely-used network protocol analyzer for network troubleshooting and analysis. | [Wireshark Website](https://www.wireshark.org/) |
| **Zenmap** | The official graphical user interface for the Nmap Security Scanner. | [Nmap Website](https://nmap.org/) |

## Cloud

| Tool | Description | Where to Find/Download |
|------|-------------|------------------------|
| **Microsoft Endpoint Manager (Intune)** | A cloud-based service that focuses on mobile device management (MDM) and mobile application management (MAM). | [Microsoft Endpoint Manager](https://www.microsoft.com/en-us/microsoft-365/microsoft-endpoint-manager) |
| **Pacu** | An open-source AWS exploitation framework, designed for testing the security of Amazon Web Services environments. | [Pacu GitHub](https://github.com/RhinoSecurityLabs/pacu) |
| **Prowler** | An open-source security tool to perform AWS security best practices assessments, audits, incident response, continuous monitoring, hardening, and forensics readiness. | [Prowler GitHub](https://github.com/prowler-cloud/prowler) |
| **Scout Suite** | An open-source multi-cloud security-auditing tool, which enables security posture assessment of cloud environments. | [Scout Suite GitHub](https://github.com/nccgroup/ScoutSuite) |
| **Cloud infrastructure assessment tools** | Various software solutions designed to evaluate and report on the security posture of cloud-based infrastructure. | Various vendors (e.g., Qualys, Tenable) |

## Vulnerability Management

| Tool | Description | Where to Find/Download |
|------|-------------|------------------------|
| **antimalware tools** | Software designed to detect, prevent, and remove malicious software. | Various vendors (e.g., McAfee, Symantec) |
| **Arachni** | An open-source web application security scanner framework. | [Arachni GitHub](https://github.com/Arachni/arachni) |
| **Burp Suite** | An integrated platform for performing security testing of web applications. | [PortSwigger Burp Suite](https://portswigger.net/burp) |
| **Cuckoo Sandbox** | An open-source automated malware analysis system. | [Cuckoo Sandbox](https://cuckoosandbox.org/) |
| **cryptography tools** | Software used for encrypting and decrypting data, as well as for cryptanalysis. | Various tools (e.g., OpenSSL, GnuPG) |
| **Debuggers** | Tools used to test and debug other programs. | Various tools (e.g., GDB, WinDbg) |
| **GNU debugger (GDB)** | A portable debugger that runs on many Unix-like systems and works for many programming languages. | [GDB Website](https://www.gnu.org/software/gdb/) |
| **Internal scanning** | The process of examining an organization's internal network for vulnerabilities and misconfigurations. | Various tools (e.g., Nessus, OpenVAS) |
| **Joe Sandbox** | A deep malware analysis platform for analyzing files, URLs, IP addresses, domains, and more. | [Joe Sandbox Website](https://www.joesecurity.org/) |
| **Metasploit** | An open-source penetration testing framework. | [Metasploit Website](https://www.metasploit.com/) |
| **Metasploit Framework (MSF)** | A tool for developing and executing exploit code against remote target machines. | [Metasploit Framework](https://github.com/rapid7/metasploit-framework) |
| **Nessus** | A proprietary vulnerability scanner developed by Tenable, Inc. | [Tenable Nessus](https://www.tenable.com/products/nessus) |
| **Nikto** | An open-source web server scanner that performs comprehensive tests against web servers for multiple items. | [Nikto GitHub](https://github.com/sullo/nikto) |
| **OpenVAS** | Open Vulnerability Assessment System, a full-featured vulnerability scanner. | [OpenVAS Website](https://www.openvas.org/) |
| **password crackers** | Software designed to recover passwords from data that has been stored or transmitted by a computer system. | Various tools (e.g., John the Ripper, Hashcat) |
| **PortSwigger** | The company behind Burp Suite, offering various web security testing tools. | [PortSwigger Website](https://portswigger.net/) |
| **Qualys** | A cloud-based IT, security, and compliance solution provider. | [Qualys Website](https://www.qualys.com/) |
| **Rapid7** | A company offering various security tools, including InsightVM for vulnerability management. | [Rapid7 Website](https://www.rapid7.com/) |
| **Debuggers** | Various software tools used for debugging programs and identifying issues in code execution. | Various tools (e.g., Visual Studio Debugger, PyCharm Debugger) |
| **Endpoint security** | Software solutions designed to secure end-user devices such as desktops, laptops, and mobile devices. | Various vendors (e.g., Symantec, McAfee) |
| **File analysis** | Software used to examine files for malicious content or anomalies. | Various tools (e.g., VirusTotal, Hybrid Analysis) |
| **Multipurpose** | Various tools that serve multiple functions in security testing and analysis. | Various tools (e.g., Kali Linux, Parrot OS) |
| **Web application scanners** | Software designed to test web applications for security vulnerabilities. | Various tools (e.g., OWASP ZAP, Acunetix) |

## Threat Intelligence

| Tool | Description | Where to Find/Download |
|------|-------------|------------------------|
| **AbuseIPDB** | A database of reported IP addresses involved in malicious activity. | [AbuseIPDB Website](https://www.abuseipdb.com/) |
| **AlienVault's Open Threat Exchange (OTX)** | An open threat intelligence community that allows participants to share threat data. | [AlienVault OTX](https://otx.alienvault.com/) |
| **Recon-ng** | A full-featured web reconnaissance framework written in Python. | [Recon-ng GitHub](https://github.com/lanmaster53/recon-ng) |
| **Domain name service (DNS) and Internet Protocol (IP) reputation** | Services that provide information about the reputation of domains and IP addresses. | Various providers (e.g., Cisco Talos, IBM X-Force) |