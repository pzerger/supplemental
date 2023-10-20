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

- **Buffer Overflow** - Attempts to overflow a buffer in an application, which can cause unintentional behavior such as remote code execution.
- **SQL injection attacks** - Attempts to inject SQL commands into application queries to manipulate the database. 
- **Back Door** - A hidden method for bypassing normal authentication in an application.
- **Cross-site scripting** - Injects malicious client-side code into web pages.
- **Cross-Site Request Forgery** - Tricks users into making unwanted actions on a web application they're authenticated to.

[Return to ToC](#cyber-attacks)

## Access Attacks

- **Brute force** - Repeatedly try different passwords or passphrases to gain unauthorized access.
- **Dictionary attacks** - Uses a prepared list of likely passwords to attempt to gain unauthorized access. 
- **Password Crackers** - Software tools used to discover passwords by brute force or dictionary attacks.
- **Meet-in-the-middle attack** - Attempts to obtain login credentials by capturing encrypted network traffic and comparing with dictionaries of common passwords.

[Return to ToC](#cyber-attacks)

## Escalation of Privilege Attacks  

- **Rootkit** - Malware that obtains administrator-level access on a system and masks its presence.
- **Time of check time of use (TOCTOU) Attacks** - Exploits the difference in time between when a system checks access permissions and when those permissions are used.

[Return to ToC](#cyber-attacks)

## Aggregation Attacks

- **Inference** - Putting together various pieces of non-sensitive information to deduce sensitive information.
- **Access aggregation attack** - Combining granted non-sensitive accesses to deduce unauthorized access to sensitive information.

[Return to ToC](#cyber-attacks)  

## Authentication Attacks

- **Masquerading** - Pretending to be an authorized user to gain access.  
- **Replay attack** - Capturing valid authentication credentials and reusing them to gain unauthorized access.
- **Spoofed logon screens** - Fake login pages to capture user credentials. 
- **Phishing** - Social engineering attacks that use fake emails or websites to trick users into revealing credentials.

[Return to ToC](#cyber-attacks)

## Availability Attacks

- **Bluebugging** - Gains control over a Bluetooth device via its communications protocol.
- **Bluejacking** - Sends unsolicited messages to Bluetooth devices.  
- **Bluesnarfing** - Access data on a Bluetooth device without pairing.
- **Denial of Service** - Floods a system with traffic to prevent legitimate access.
- **Distributed Denial of Service** - Coordinated denial of service attack from multiple sources.  
- **Fraggle Attack** - Amplified UDP attack from many spoofed source IP addresses.
- **Land Attack** - Sends a TCP packet with source and destination IP/port set to match the target system.
- **Ping of Death** - Sends an invalid, oversized ping packet to crash the target system.
- **Smurf attack** - Spoofs victim's IP address in ping requests sent to broadcast addresses.
- **SYN Flood** - Sends TCP SYN requests faster than the system can process them. 
- **Teardrop Attack** - Sends mangled IP fragments to crash vulnerable systems.

[Return to ToC](#cyber-attacks)

## Reconnaissance Attacks  

- **Sniffer Attacks** - Captures private network traffic for malicious purposes.  
- **Social Engineering** - Manipulates people into providing confidential information.
- **Spoofing Attacks** - Conceals the true source of malicious network traffic.

[Return to ToC](#cyber-attacks)

## Cryptographic Attacks

- **Birthday attack** - Exploits the math behind cryptographic hashing to find collisions.  
- **Brute force** - Tries all possible combinations to break encryption keys.

[Return to ToC](#cyber-attacks)

## Malware

- **Remote Access Trojan** - Malware that allows remote control over a system.
- **Rootkit** - Malware that obscures its presence and gains root access.
- **Macro Infection** - Malware infects documents with malicious macros.

[Return to ToC](#cyber-attacks) 

## Operating System Attacks

- **Privilege Escalation** - Exploits a bug or misconfiguration to gain elevated access.
- **Kernel Exploits** - Leverages flaws in the OS kernel to gain control.

[Return to ToC](#cyber-attacks)

## Misconfiguration Attacks

- **Default Credentials** - Logs in with vendor default usernames and passwords.
- **Unpatched Systems** - Exploits publicly known vulnerabilities.
- **Insecure Settings** - Compromises systems due to insecure configurations.

[Return to ToC](#cyber-attacks)

## Other Attack Types

- **Man-In-The-Middle** - Inserts between two communicating hosts to intercept and alter traffic. 
- **Remotely Triggered Black Hole** - Causes routers to drop traffic based on source/destination.
- **Spam over Instant Messaging** - Sends unsolicited instant messages in bulk.  
- **Time of Check to Time of Use** - Exploits the timing difference between checking access and using access.
- **Tactics, Techniques, and Procedures** - Methods for exploiting systems and networks.

[Return to ToC](#cyber-attacks)