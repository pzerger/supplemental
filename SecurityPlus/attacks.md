
# Cyber Attacks

- [Application-Level Attacks](#application-level-attacks)
- [Access Attacks](#access-attacks)
- [Escalation of Privilege Attacks](#escalation-of-privilege-attacks) 
- [Aggregation Attacks](#aggregation-attacks)
- [Authentication Attacks](#authentication-attacks)
- [Availability Attacks](#availability-attacks)
- [Reconnaissance Attacks](#reconnaissance-attacks)  
- [Cryptographic Attacks](#cryptographic-attacks)
- [Malware](#malware)
- [Operating System Attacks](#operating-system-attacks)
- [Misconfiguration Attacks](#misconfiguration-attacks)
- [Other Attack Types](#other-attack-types)

## Application-Level Attacks

These target specific applications with various methods, such as injecting malicious code or exploiting software vulnerabilities to compromise or steal data.

- **Buffer Overflow** - Attempts to overflow a buffer in an application, which can cause unintentional behavior such as remote code execution. Use bounds checking and input validation to prevent buffer overflows.
- **SQL injection attacks** - Attempts to inject SQL commands into application queries to manipulate the database. Use parameterized queries and input validation to prevent SQL injection.
- **Back Door** - A hidden method for bypassing normal authentication in an application. Perform code reviews to identify backdoors.
- **Cross-site scripting** - Injects malicious client-side code into web pages. Validate and encode any dynamic output in web applications.
- **Cross-Site Request Forgery** - Tricks users into making unwanted actions on a web application they're authenticated to. Require CSRF tokens to prevent forged requests.

[Back to ToC](#cyber-attacks)

## Access Attacks

These aim to gain unauthorized access to systems or data, typically by bypassing authentication mechanisms or exploiting permissions.

- **Brute force** - Repeatedly try different passwords or passphrases to gain unauthorized access. Implement account lockouts after failed login attempts. 
- **Dictionary attacks** - Uses a prepared list of likely passwords to attempt to gain unauthorized access. Enforce strong password policies.
- **Meet-in-the-middle attack** - Attempts to obtain login credentials by capturing encrypted network traffic and comparing with dictionaries of common passwords. Use encryption protocols like TLS to protect network traffic.
- **Password Crackers** - Software tools used to discover passwords by brute force or dictionary attacks. Utilize multi-factor authentication.
- ***Password spraying*** - Sprays a single, common or default password (or a small list of passwords) against many usernames across a system. Often automated, targeting large numbers of usernames with a limited set of frequently used passwords.


[Back to ToC](#cyber-attacks)

## Escalation of Privilege Attacks  

In these attacks, an attacker exploits a flaw to gain higher access levels than originally authorized, often leading to administrative access.

- **Rootkit** - Malware that obtains administrator-level access on a system and masks its presence. Use anti-virus tools and access control lists to limit privilege escalation.
- **Time of check time of use (TOCTOU) Attacks** - Exploits the difference in time between when a system checks access permissions and when those permissions are used. Reduce time windows between checks and uses.

[Back to ToC](#cyber-attacks)

## Aggregation Attacks

These involve the collection of small pieces of non-sensitive information which, when combined, reveal sensitive information.

- **Inference** - Putting together various pieces of non-sensitive information to deduce sensitive information. Limit data sharing and anonymize data where possible.
- **Access aggregation attack** - Combining granted non-sensitive accesses to deduce unauthorized access to sensitive information. Implement separation of duties and least privilege access. 

[Back to ToC](#cyber-attacks)  

## Authentication Attacks

These are focused on breaking into a system by circumventing or breaking the authentication processes, like password cracking or session hijacking.

- **Masquerading** - Pretending to be an authorized user to gain access. Use multi-factor authentication to verify identities.
- **Replay attack** - Capturing valid authentication credentials and reusing them to gain unauthorized access. Utilize single-use authentication tokens.
- **Spoofed logon screens** - Fake login pages to capture user credentials. Educate users on identifying phishing pages.
- **Phishing** - Social engineering attacks that use fake emails or websites to trick users into revealing credentials. Train employees to identify and report phishing attempts.

[Back to ToC](#cyber-attacks)

## Availability Attacks

Aimed at disrupting the availability of services, these attacks, such as DDoS (Distributed Denial of Service), overload resources to cause a shutdown.

- **Bluebugging** - Gains control over a Bluetooth device via its communications protocol. Disable Bluetooth when not needed.  
- **Bluejacking** - Sends unsolicited messages to Bluetooth devices. Make Bluetooth non-discoverable.
- **Bluesnarfing** - Access data on a Bluetooth device without pairing. Encrypt Bluetooth connections.
- **Denial of Service** - Floods a system with traffic to prevent legitimate access. Use firewall rules to block malicious traffic.
- **Distributed Denial of Service** - Coordinated denial of service attack from multiple sources. Employ DDoS mitigation services.
- **Fraggle Attack** - Amplified UDP attack from many spoofed source IP addresses. Block outbound UDP traffic where not needed.
- **Land Attack** - Sends a TCP packet with source and destination IP/port set to match the target system. Disable IP source routing.
- **Ping of Death** - Sends an invalid, oversized ping packet to crash the target system. Block ICMP packets over a certain size.  
- **Smurf attack** - Spoofs victim's IP address in ping requests sent to broadcast addresses. Disable directed broadcast packets.
- **SYN Flood** - Sends TCP SYN requests faster than the system can process them. Use SYN cookies or reduce SYN-RECEIVED timer.
- **Teardrop Attack** - Sends mangled IP fragments to crash vulnerable systems. Filter malformed IP fragments in firewalls.

[Back to ToC](#cyber-attacks)

## Reconnaissance Attacks   

These are preliminary attacks where the attacker gathers information about the target system or network to plan future attacks.

- **Sniffer Attacks** - Captures private network traffic for malicious purposes. Encrypt network traffic and monitor for signs of sniffing.
- **Social Engineering** - Manipulates people into providing confidential information. Educate employees on social engineering risks.  
- **Spoofing Attacks** - Conceals the true source of malicious network traffic. Authenticate traffic sources and discard spoofed packets. 

[Back to ToC](#cyber-attacks)

## Cryptographic Attacks

These attacks attempt to break cryptographic algorithms to decrypt sensitive data without authorization, often by finding vulnerabilities in the encryption.

- **Birthday attack** - Exploits the math behind cryptographic hashing to find collisions. Use cryptographic hashes with large output spaces.
- **Brute force** - Tries all possible combinations to break encryption keys. Utilize encryption with large key spaces.

[Back to ToC](#cyber-attacks)

## Malware

This category includes software designed to harm or exploit any programmable device, service, or network, ranging from viruses to ransomware.

- **Remote Access Trojan** - Malware that allows remote control over a system. Use anti-virus tools and monitor for suspicious activities.
- **Rootkit** - Malware that obscures its presence and gains root access. Perform regular system scans to identify rootkits.
- **Macro Infection** - Malware infects documents with malicious macros. Disable macros in office documents from untrusted sources.

[Back to ToC](#cyber-attacks)

## Operating System Attacks  

Targeting the vulnerabilities in operating systems, these attacks aim to take control of systems for malicious intent.

- **Privilege Escalation** - Exploits a bug or misconfiguration to gain elevated access. Patch systems regularly and monitor user privileges.
- **Kernel Exploits** - Leverages flaws in the OS kernel to gain control. Harden systems and restrict kernel access.

[Back to ToC](#cyber-attacks)

## Misconfiguration Attacks

These exploit security gaps resulting from incorrect system or application configurations, often leading to unauthorized access or data exposure.

- **Default Credentials** - Logs in with vendor default usernames and passwords. Change all default credentials.
- **Unpatched Systems** - Exploits publicly known vulnerabilities. Apply patches promptly.
- **Insecure Settings** - Compromises systems due to insecure configurations. Review configurations and disable unnecessary services.

[Back to ToC](#cyber-attacks)

## Other Attack Types

A catch-all category for attacks that don't fit neatly into the other categories, potentially including novel or hybrid forms of cyber threats.

- **On-path (formerly Man-In-The-Middle)** - Inserts between two communicating hosts to intercept and alter traffic. Use encryption to secure connections.
- **Remotely Triggered Black Hole** - Causes routers to drop traffic based on source/destination. Monitor network traffic flows.
- **Spam over Instant Messaging** - Sends unsolicited instant messages in bulk. Use spam filters for instant messaging.
- **Time of Check to Time of Use** - Exploits the timing difference between checking access and using access. Reduce windows between access checks and usage.
- **Tactics, Techniques, and Procedures** - Methods for exploiting systems and networks. Keep informed on latest attack methods and adjust defenses accordingly.

- **Watering hole attack** - An attack that targets a specific organization, in which malware is installed on a website or websites regularly visited by the organization's members in order to infect computers used within the organization itself.

[Back to ToC](#cyber-attacks)
