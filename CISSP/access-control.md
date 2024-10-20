# Access Control
Access control schemes and related concepts.

## Table of Contents

- [Access Control List (ACL)](#access-control-list-acl)
- [Mandatory Access Control](#mandatory-access-control)
- [Access aggregation attack](#access-aggregation-attack)
- [Access Control Matrix](#access-control-matrix)
- [Access control system](#access-control-system)
- [Access control tokens](#access-control-tokens)
- [Attribute-based access control (ABAC)](#attribute-based-access-control-abac)
- [Discretionary access control (DAC)](#discretionary-access-control-dac)
- [Logical access control system](#logical-access-control-system)
- [Mandatory access controls (MAC)](#mandatory-access-controls-mac)
- [Non-discretionary access control](#non-discretionary-access-control)
- [Physical access control system](#physical-access-control-system)
- [Role-based access control (RBAC)](#role-based-access-control-rbac)
- [Rule-based access control (RBAC)](#rule-based-access-control-rbac)
- [Social Engineering](#social-engineering)
- [Spoofed logon screens](#spoofed-logon-screens)
  
### Access Control List (ACL)
An ACL is a table that tells a computer operating system which access rights each user or system has to a particular system resource, such as a file directory or individual file. ACLs specify which users or system processes have permission to read, write, or execute specific resources.

[Back to ToC](#table-of-contents)

### Mandatory Access Control
A type of access control in which the operating system constrains the ability of a subject or initiator to access or generally perform some sort of operation on an object or target. Subjects and objects each have a set of security attributes which are used together with the rules in the ACL to determine if a given subject can access a given object. 

[Back to ToC](#table-of-contents)

### Access aggregation attack
An access aggregation attack utilizes incremental privileged access to gain greater access to systems or data. For example, an attacker with low-level access finds ways through social engineering or minor privilege escalation to gain slightly higher privileges, then leverages those to gain more access in an iterative fashion.

[Back to ToC](#table-of-contents)

### Access Control Matrix
An access control matrix is a table that shows the access rights of each subject (user or process) for every object (files, databases, devices) in a system. It details the specific access privileges (read, write, execute, etc.) that every user has for every resource.

[Back to ToC](#table-of-contents)

### Access control system
An access control system manages access to protected resources by allowing only authorized entities such as users, programs, processes, or systems to have access to objects like files, directories, devices, databases, etc. Access control systems can be physical (doors, locks) or logical (user authentication, permissions).

[Back to ToC](#table-of-contents)

### Access control tokens
Access control tokens are physical devices used to gain access to an access control system. Examples include keys, keycards, and proximity cards. To gain entry, the token must be authenticated usually by belonging to an authorized user.

[Back to ToC](#table-of-contents)

### Attribute-based access control (ABAC)
An access control method where subject requests to perform operations on objects are granted or denied based on assigned attributes of the subject, assigned attributes of the object, environment conditions, and a set of policies that are specified in terms of those attributes and conditions.

[Back to ToC](#table-of-contents)

### Discretionary access control (DAC)
An access control policy that allows owners of objects to control access to their own objects by assigning access permissions to subjects/users. The owner has full discretion over who can access the object and what privileges they have.

[Back to ToC](#table-of-contents)

### Logical access control system
Logical access control systems control access to digital resources and data through user authentication and authorization mechanisms. They may use usernames/passwords, smart cards, biometrics, or other credentials to control access.

[Back to ToC](#table-of-contents)

### Mandatory access controls (MAC)
A type of access control that uses system-enforced security policies rather than user discretion to control access. MAC policies use security labels such as Top Secret, Secret, etc. and enforce rules for information flow between security levels. 

[Back to ToC](#table-of-contents)

### Non-discretionary access control
Any access control scheme that restricts access to objects based on security rules outside the object owner's control. MAC and RBAC are examples. Contrast with DAC which allows object owners to control access.

[Back to ToC](#table-of-contents)

### Physical access control system
Systems that control and restrict physical access to facilities, buildings or rooms by validating a person's identity and confirming they can access the physical space. Examples: card readers, biometric scanners, guards.

[Back to ToC](#table-of-contents)

### Role-based access control (RBAC)
Access control based on a subject's job function or role within the system, rather than the subject's individual identity. Roles are assigned certain access privileges. RBAC simplifies access management.

[Back to ToC](#table-of-contents)

### Rule-based access control (RBAC)
Access control based on rules that specify which resources subjects can access under various conditions. Rules can combine attributes of subjects, objects, and the environment. Related to ABAC.

[Back to ToC](#table-of-contents)

### Social Engineering
Attacks based on manipulating human psychology rather than technical hacking. Social engineering tricks users into disclosing confidential info or performing actions that compromise security. Examples: phishing, pretexting.

[Back to ToC](#table-of-contents)

### Spoofed logon screens
An attack that presents a fake system/application logon screen to capture user credentials. The fake logon screen looks identical to the real one but sends credentials to the attacker rather than the real system.

[Back to ToC](#table-of-contents)
