# Vulnerability Management

Vulnerability management is the systematic process of identifying, evaluating, treating, and reporting on security vulnerabilities in systems and the software that runs on them.

- **Vulnerability Analysis**: The process of defining, identifying, and classifying the security holes in information systems.
  
- **Assessments**: Evaluations of a system or application to identify the presence of vulnerabilities. This typically includes a combination of manual and automated techniques.

- **Management**: The oversight and control of the vulnerability management process, including prioritization and remediation strategies.

- **Scanners**: Tools that automatically search systems for known vulnerabilities. Common examples include Nessus and OpenVAS.

- **Scans**: The actual processes of using vulnerability scanners to detect weaknesses in systems.

**end of item**

# Public Key Infrastructure (PKI)

PKI is a set of roles, policies, and procedures needed to create, manage, distribute, use, store, and revoke digital certificates and manage public-key encryption.

- **Certificate Authority (CA)**: An entity that issues digital certificates. CAs act as a trusted third party.

- **Certificate**: A digital document that certifies the ownership of a public key by the named subject of the certificate.

- **Common Name**: An attribute within a certificate that provides an identifier for the subject of the certificate, often a hostname or organization name.

- **Certificate Revocation List (CRL)**: A list of certificates that have been revoked by the CA before their expiration date.

- **Certificate Signing Request (CSR)**: A message sent from an applicant to a CA to apply for a digital identity certificate.

- **Online Certificate Status Protocol (OCSP)**: A protocol used to obtain the revocation status of a digital certificate.

- **Certificate Stapling**: A method for a server to send its certificates and a valid OCSP response to a client, to prove its legitimacy.

- **Certificate Pinning**: A process where web applications instruct clients to expect a specific public key or set of keys, enhancing security.

- **Certificate Formats**: Different encodings and file types for certificates, such as PEM, DER, and PFX/P12.

**end of item**

# Asset Management

Asset management pertains to the governance and procedures for managing an organization's assets, including information assets.

- **Identification**: Recognizing and distinguishing assets based on unique characteristics.

- **Inventory**: Maintaining a list or database of assets, often with details about each asset.

- **Classification**: Assigning a level of sensitivity and criticality to assets, often for the purpose of determining security controls.

- **Valuation**: Assigning a monetary or strategic value to assets, which can aid in risk management decisions.

- **Ownership**: Determining and documenting the individual or group responsible for an asset.

- **Disposition**: The process of disposing of assets, which might include deletion, destruction, transfer, or archival.

**end of item**

# Business Continuity and Disaster Recovery (BCDR)

### Goals of BCDR
The primary goals of BCDR include:
- **Protection**: Safeguard critical business functions and assets from disruptions.
- **Recovery**: Restore critical functions and processes after a disruption.
- **Continuity**: Ensure continuous business operations, even during disruptions.

### Processes and Plans
1. **Business Impact Analysis (BIA)**: This identifies the impact of disruptions on business operations and establishes priorities for recovery.
2. **Business Continuity Plan (BCP)**: Provides a strategy to continue operations in the event of a disruption. It derives its details from the BIA.
3. **Disaster Recovery Plan (DRP)**: Focuses on restoring IT systems and data after a disaster. It's a subset of the BCP.
4. **Business Resumption Plan (BRP)**: A subset of the DRP, it details how to quickly resume business after a disruption.
5. **Service Level Agreement (SLA)**: A documented agreement between a service provider and a client about the level of service expected during and after a disruption.
6. **Mutual Assistance Agreements (MAAs)**: Agreements between entities to provide mutual aid in the event of a disaster. 

Relationship: BIA → BCP → DRP → BRP. SLAs and MAAs serve as supportive documents to ensure the effectiveness and cooperative nature of the plans.

### Metrics
- **Mean Time Between Failures (MTBF)**: Average time between system failures.
- **Mean Time To Detect (MTTD)**: Average time to detect a failure.
- **Mean Time to Failure (MTTF)**: Average time until a system or component fails.
- **Mean Time to Repair (MTTR)**: Average time to repair a system or component.
- **Recovery Point Objective (RPO)**: Maximum acceptable amount of data loss measured in time.
- **Recovery Time Objective (RTO)**: Maximum acceptable time to restore a function after a disruption.
- **Max Tolerable Downtime (MTD)**: Maximum period a service can be down without causing unacceptable damage.

### Types of Impacts
1. **Catastrophe (categories of disruption)**: Severe events causing significant disruption like nuclear incidents.
2. **Disaster (categories of disruption)**: Serious disruption events but not as severe as catastrophes like fires or floods.
3. **Man-made Disasters**: Events caused by human actions like terrorism or sabotage.
4. **Natural Disasters**: Events caused by natural phenomena like earthquakes or hurricanes.
5. **Non-Disaster (categories of disruption)**: Minor disruptions that don't significantly affect business like a short-term power outage.

### Testing
- **Full Interruption Test**: Live testing, fully interrupting and replacing the primary system.
- **Read-through Test**: Verbal exercise, reviewing the plan for accuracy and comprehension.
- **Parallel Test**: Live testing, running systems in parallel (backup and primary).
- **Simulation Test**: Live scenario without real interruption.
- **Structured Walk-through**: Verbal exercise, team members discuss and walk through scenarios.

### Types of Sites
- **Cold Site**: Minimal infrastructure, no immediate availability. Cost: Low, Recovery Effort: High.
- **Warm Site**: Partially equipped, moderate recovery time. Cost: Medium, Recovery Effort: Medium.
- **Hot Site**: Fully equipped, immediate availability. Cost: High, Recovery Effort: Low.
- **Mobile Site**: Portable, can be set up at or near a disaster site.
- **Service Bureau**: Outsourced site, often provided by a third-party vendor.

### Teams
- **Recovery Team**: Focuses on recovering operations after a disruption.
- **Salvage Team**: Focuses on saving and recovering assets from the disrupted site.

**end of item**

# Threat Modeling and its Importance in Improving Security

Threat modeling is a structured process used to identify potential security threats and vulnerabilities in a system or application. By proactively analyzing and understanding the threats, measures can be taken to mitigate or eliminate them, improving the overall security posture.

**Benefits of Threat Modeling:**
1. **Proactive Security:** Identify and address threats early in the design phase.
2. **Risk Management:** Helps in prioritizing threats based on their impact and likelihood.
3. **Informed Decisions:** Provides a clear view to stakeholders on security risks.
4. **Compliance:** Helps in meeting security standards and regulatory requirements.

## Role of Threat Modeling in the Systems Development Lifecycle (SDLC)

Threat modeling plays a pivotal role in the SDLC. Conducting it during the design phase ensures that security considerations are embedded from the beginning, reducing costly changes later on.

1. **Requirements Phase:** Define security objectives and requirements.
2. **Design Phase:** Create a model of the system, identify potential threats and evaluate their risk.
3. **Implementation Phase:** Use the identified threats to guide secure coding practices.
4. **Verification Phase:** Test the system against the identified threats.
5. **Maintenance Phase:** Continuously monitor and update the threat model as the system evolves.

## Description of Various Threat Models

### DREAD (Damage, Reproducibility, Exploitability, Affected Users, and Discoverability)

- **Focus:** Prioritizing threats based on their potential impact.
- **Usage:** Commonly used in software design and assessment.
- **Details:**
  - **Damage:** Potential harm caused by the threat.
  - **Reproducibility:** How easily the threat can be replicated.
  - **Exploitability:** Ease with which the vulnerability can be exploited.
  - **Affected Users:** Number of users impacted.
  - **Discoverability:** How easily the threat can be discovered.

### OCTAVE (Operationally Critical Threat, Asset, and Vulnerability Evaluation)

- **Focus:** Organization-wide risk assessment.
- **Usage:** Suitable for large organizations seeking to evaluate risks across different assets and operations.
- **Details:** Considers organizational structure, technology, and processes to identify critical assets, threats to those assets, and vulnerabilities.

### PASTA (Process for Attack Simulation and Threat Analysis)

- **Focus:** Attack simulation and threat analysis.
- **Usage:** System and application threat modeling to understand potential attack vectors and scenarios.
- **Details:** A seven-step process that starts with defining objectives and ends with vulnerability analysis and threat validation.

### STRIDE (Spoofing, Tampering, Repudiation, Information disclosure, Denial of service, Elevation of privilege)

- **Focus:** Classification of threats based on the type of threat action.
- **Usage:** Primarily used in the design phase of software and systems.
- **Details:** 
  - **Spoofing:** Unauthorized use of valid identification.
  - **Tampering:** Unauthorized modification of data.
  - **Repudiation:** Denial of performed actions.
  - **Information Disclosure:** Unauthorized access to information.
  - **Denial of Service:** Disruption of service availability.
  - **Elevation of Privilege:** Unapproved escalation of access rights.

### TRIKE (Threat and Risk Identification and Knowledge-based Engineering)

- **Focus:** Risk-based approach to security requirements.
- **Usage:** Helps in specifying security properties and understanding potential risks.
- **Details:** A methodology that uses a risk model to determine the requirements and ensure the system meets those requirements.

### VAST (Visual, Agile, and Simple Threat)

- **Focus:** Streamlining and simplifying the threat modeling process.
- **Usage:** Agile development environments where rapid iterations are required.
- **Details:** Emphasizes on visual representation, agility in addressing threats, and simplifying the modeling process for quicker turnarounds.

**end of item**

# Risk Management in Cybersecurity for CISSP Exam

## Definition of Risk & Risk Management
- **Risk**: A potential event that could result in harm or loss to an organization or system. It is usually expressed in terms of likelihood and potential impact.
- **Risk Management**: The process of identifying, assessing, and controlling risks to an organization's assets and earnings. This includes the implementation of measures to mitigate or reduce the impact and likelihood of a negative event.

## Goals of Risk Assessment
1. Identify vulnerabilities, threats, and potential impacts.
2. Evaluate the likelihood of occurrence.
3. Determine potential impact.
4. Prioritize risks for treatment or mitigation.
5. Inform decision-makers about the current risk environment.

## Quantitative vs. Qualitative Risk Analysis
- **Quantitative Risk Analysis**:
  - Uses numerical metrics.
  - Typically involves statistical, mathematical, or financial values.
  - More objective.
  - Examples: Monetary losses, number of affected records.
  - Commonly used when precise data is available and financial assessments are required.
- **Qualitative Risk Analysis**:
  - Based on judgment, intuition, and experience.
  - Uses categories or scales (e.g., Low, Medium, High).
  - Subjective.
  - Examples: Descriptive scenarios, expert opinions.
  - Commonly used in scenarios where data may be sparse or hard to quantify.

## Definitions of Risk Concepts
- **Risk Appetite**: The total amount of risk an organization is willing to accept or pursue to achieve its business objectives.
- **Risk Tolerance**: The level of risk an organization is willing to accept for a specific area or asset.
- **Acceptable Risk**: The amount of risk deemed tolerable after implementing risk treatments.
- **Residual Risk**: The remaining risk after controls or mitigations are applied.
- **Inherent Risk**: The risk level that exists in the absence of any controls or treatments.
- **Total Risk**: The combination of inherent and residual risk.

## Risk Formulas
- **Single Loss Expectancy (SLE)** = Asset Value (AV) x Exposure Factor (EF)
  - Example: An asset worth $100,000 with an EF of 20% has a SLE of $20,000.
- **Exposure Factor (EF)**: The percentage of asset value that is likely to be lost due to a particular threat.
- **Annualized Loss Expectancy (ALE)** = Single Loss Expectancy (SLE) x Annualized Rate of Occurrence (ARO)
  - Example: A SLE of $20,000 with an ARO of 5 results in an ALE of $100,000.
- **Annualized Rate of Occurrence (ARO)**: Expected frequency with which an event will occur within a year.

## Responses to Risk
- **Risk Acceptance**: Choosing to acknowledge the risk without taking specific steps to address its impact or likelihood.
- **Risk Avoidance**: Taking actions to eliminate the risk or its impact.
- **Risk Mitigation**: Implementing measures to reduce the risk's impact or likelihood.
- **Risk Transference**: Shifting the risk or its impact to a third party (e.g., insurance).
- **Risk Deterrence**: Taking steps to deter the threat (e.g., warning signs, legal consequences).
- **Risk Rejection**: Denying the existence or potential impact of a risk (not recommended).

## Relationship Between Asset Value and Cost of Remediation
- Effective risk management strategies balance the cost of remediation against the asset's value. It's crucial to ensure that the cost of implementing controls or mitigations does not exceed the value of the asset being protected. Analyzing this relationship helps organizations prioritize their investments in security and risk management.

**end of item**

Okay, here is the full document with all sections repeated verbatim:

# Incident management notes for CISSP

## Incident management steps

Here are the incident management steps from each of the frameworks:

### CISSP Incident Management Steps:
1. Detection
2. Response   
3. Mitigation
4. Reporting
5. Recovery
6. Remediation
7. Lessons Learned
SOURCE: OSG: pp 804-809 CBK: 502-511

### NIST Incident Management Steps:  
1. Preparation
2. Detection and Analysis
3. Containment, Eradication, and Recovery
4. Post-Incident Activity
SOURCE: NIST 800-61 rev 2 (Computer Security Incident Handling Guide)

### SANS Incident Management Steps:
1. Preparation
2. Identification
3. Containment
4. Eradication
5. Recovery
6. Lessons Learned
SOURCE: SANS Incident Handlers Handbook  

## Terminology

The key differences between these terms in an incident management context are:

- **Triage** - The initial assessment and prioritization of an incident. Determining the severity and scope of the incident.

- **Containment** - Attempts to limit and control the incident from spreading. For example, disconnecting infected hosts from the network.

- **Mitigation** - Steps taken to reduce the severity of the incident. Mitigation is the phase where the organization begins to implement actions necessary to fix the incident. For example, blocking malicious IP addresses with a firewall.

- **Remediation** - Removing the underlying causes of the incident to prevent reoccurrence. For example, patching vulnerable software. 

- **Eradication** - Removing artifacts of the incident like malware and backdoors. For example, completely wiping and reinstalling compromised systems.

- **Recovery** - Restoring affected systems and services back to normal operations. For example, restoring data from backups and bringing production systems back online.

The frameworks describe similar incident management processes, with some differences in categorization and naming of the steps.

- All include preparation, detection, containment/response, recovery, and lessons learned as core elements of the process.

- SANS also specifically calls out identification as a separate step.

- CISSP and SANS separate out eradication as its own step, while NIST rolls it into containment, eradication, and recovery.

In short: 

- **Triage** is the initial assessment.

- **Containment** and mitigation are about controlling the incident.

- **Remediation** and eradication are about removing the causes of the incident.

- **Recovery** is about restoring normal operations after the incident.

## Declaring an incident

At which step in each of these processes is an incident declared?

The step where an incident is declared in each framework is covered below. For the CISSP, we should examine both the CBK and the OSG for guidance.

### CISSP (OSG):

In the Detection step. The CISSP official study guide states:

“After detecting and verifying an incident, the next step is response.”

The quote above is the first line of the section on Response (pg. 806), indirectly telling us that Detection is where the incident is declared. Also, in the in the official study guide: 

"Notice that just because an IT professional receives an alert from an automated tool or a user complaint, this doesn’t always mean an incident has occurred. IT personnel investigate these events to determine whether they are incidents.”

### CISSP CBK:

The CBK offers some additional details:

In the Detection (pg. 505) section, we see:

“...the detection may go through a review process during which an analyst reviews the incident and conducts some basic research to determine if the incident is legitimate or a false positive. If the analyst deems the incident valid, response procedures are initiated.”

The Response (pg. 506) section states:

“Triage is an early-stage response process for confirmed incidents and is designed to identify the criticality and categorization of the incident type.” 

Specifically, when an event or alert is detected, it undergoes triage and analysis to determine if it is a legitimate incident that requires further response.

This statement in the Response section of the CBK (pg. 506) may be a bit confusing to the question of declaration:  

“If the detection is validated as an actual incident, then the incident response procedures are formally initiated, and stakeholders are notified that an incident has been declared.”

From the more detailed language of the CBK, we see identification of an incident happens in the Detection phase, and more detailed classification (priority and criticality) happens after initial triage in the Response phase. Because of this and the statement “If the analyst deems the incident valid” (pg. 506) this may be viewed by some as a formal declaration, as it may trigger specific responses, such as invoking BC and DR plans.

Because the language in real exam questions tends to be precise, there should be enough detail between the CBK and the OSG to guide us.

### NIST:  

In the Detection and Analysis step. The NIST document states:

"Detection of security breaches is thus necessary to alert the organization whenever incidents occur. In keeping with the severity of the incident, the organization can mitigate the impact of the incident by containing it and ultimately recovering from it."

### SANS:

In the Identification step. The SANS document states: 

"This particular step requires one to gather events from various sources such as log files, error messages, and other resources, such intrusion detection systems and firewalls, that may produce evidence as to determine whether an event is an incident."

In short:

- Detection tools or humans notice an anomalous event.

- The event is analyzed to see if it is a real incident.

- If analysis validates it as an incident, then the incident is formally declared and response procedures kick off. 

- Declaration of the incident starts the remaining steps of response, mitigation, reporting, recovery, etc.

So, the declaration happens during the response phase, after initial detection but before subsequent incident management steps proceed. This allows proper analysis and confirmation that an incident has genuinely occurred before committing resources to further incident handling.

## Containing an incident

The step where containment is performed in each framework is:

### CISSP:

In the Mitigation step. The CISSP framework states:

"Mitigation steps attempt to contain an incident. One of the primary goals of effective incident management is to limit the effect or scope of an incident."

### NIST: 

In the Containment, Eradication, and Recovery step. The NIST framework states:  

"Containment provides time for developing a tailored remediation strategy. An essential part of containment is decision-making (e.g., shut down a system, disconnect it from a network, disable certain functions)."

### SANS:

In the Containment step. The SANS framework states:

"The primary purpose of this phase is to limit the damage and prevent any further damage from happening ("Uf it security," 2011)."

## Incident Management Activities  

Here are the steps and key activities for each incident response framework:

### CISSP:

1. **Detection** - Monitoring and identifying potential incidents through alerts and user reports.

2. **Response** - Activating the incident response team and coordinating initial response.

3. **Mitigation** - Containing the incident and taking steps to limit its impact.

4. **Reporting** - Notifying appropriate parties internal and external to the organization. 

5. **Recovery** - Restoring affected systems and services to normal operations.  

6. **Remediation** - Identifying and mitigating vulnerabilities that led to the incident.

7. **Lessons Learned** - Documenting the incident and identifying improvements to policies and controls.

### NIST:  

1. **Preparation** - Developing incident response policies, procedures, and resources.

2. **Detection and Analysis** - Discovering the incident and determining its scope and impact. 

3. **Containment, Eradication, Recovery** - Containing the incident, eliminating components, and restoring systems.  

4. **Post-Incident Activity** - Documenting and reporting the incident and identifying improvements.

### SANS:

1. **Preparation** - Developing incident response capabilities and resources.  

2. **Identification** - Discovering the incident and determining if an event is an incident.

3. **Containment** - Isolating affected systems to limit the incident's impact.

4. **Eradication** - Eliminating incident components from systems.

5. **Recovery** - Returning affected systems back to normal operations. 

6. **Lessons Learned** - Documenting the incident and identifying improvements.

**end of item**

# Laws and Regulations Overview:

#### Bank Secrecy Act (BSA)
- **Core Purpose**: To prevent money laundering and requires financial institutions to keep records and file reports on certain financial transactions.
- **Applies To**: Banks and various other financial institutions in the U.S.
- **Regulatory Entity**: Created by the U.S. Congress and enforced by the Financial Crimes Enforcement Network (FinCEN).

#### Computer Fraud and Abuse Act (CFAA)
- **Core Purpose**: To combat hacking, unauthorized access, and fraudulent use of computer systems.
- **Applies To**: Anyone accessing a computer without authorization or exceeding their authorized access.
- **Regulatory Entity**: Created by the U.S. Congress and enforced by the U.S. Department of Justice.

#### Children's Online Privacy Protection Act (COPPA)
- **Core Purpose**: To protect the privacy of children under 13 by restricting the collection and use of their personal information by websites and online services.
- **Applies To**: Websites and online services targeting children or knowingly collecting information from children under 13.
- **Regulatory Entity**: Created by the U.S. Congress and enforced by the Federal Trade Commission (FTC).

#### Digital Millennium Copyright Act (DMCA)
- **Core Purpose**: To address copyright challenges in the digital age, particularly the circumvention of copyright protection systems.
- **Applies To**: Online service providers, users of copyrighted content, and creators.
- **Regulatory Entity**: Created by the U.S. Congress and enforced by the U.S. Copyright Office and the courts.

#### Export Administration Regulations (EAR)
- **Core Purpose**: To control the export of dual-use items (goods and technology that can be used both for civilian and military purposes).
- **Applies To**: U.S. individuals and entities exporting or re-exporting designated items.
- **Regulatory Entity**: Implemented by the U.S. Department of Commerce's Bureau of Industry and Security.

#### Electronic Communications Privacy Act (ECPA)
- **Core Purpose**: To protect wire, oral, and electronic communications during their transmission.
- **Applies To**: Electronic communication service providers and users.
- **Regulatory Entity**: Created by the U.S. Congress and enforced by law enforcement and courts.

#### Federal Information Security Management Act (FISMA)
- **Core Purpose**: To require federal agencies to develop, document, and implement information security programs.
- **Applies To**: Federal agencies and contractors.
- **Regulatory Entity**: Created by the U.S. Congress and overseen by the Office of Management and Budget (OMB).

#### Freedom Of Information Act (FOIA)
- **Core Purpose**: To allow public access to records from any federal agency.
- **Applies To**: Federal government agencies.
- **Regulatory Entity**: Created by the U.S. Congress and administered by each federal agency.

#### General Data Protection Regulation (GDPR)
- **Core Purpose**: To protect data and privacy for all individuals within the European Union (EU) and the European Economic Area (EEA).
- **Applies To**: Organizations operating within the EU and those outside the EU that offer goods/services to EU citizens.
- **Regulatory Entity**: Adopted by the European Parliament and enforced by data protection authorities in each EU member state.

#### Gramm-Leach-Bliley Act (GLBA)
- **Core Purpose**: To require financial institutions to explain their information-sharing practices and protect sensitive data.
- **Applies To**: Financial institutions operating in the U.S.
- **Regulatory Entity**: Created by the U.S. Congress and enforced by several agencies, including the FTC.

#### Health Insurance Portability and Accountability Act (HIPAA)
- **Core Purpose**: To ensure the confidentiality, integrity, and availability of protected health information (PHI).
- **Applies To**: Healthcare providers, health plans, and healthcare clearinghouses.
- **Regulatory Entity**: Created by the U.S. Congress and enforced by the U.S. Department of Health and Human Services.

#### Health Information Technology for Economic and Clinical Health (HITECH)
- **Core Purpose**: To promote the adoption of health information technology and enhance HIPAA enforcement.
- **Applies To**: Entities covered by HIPAA and their business associates.
- **Regulatory Entity**: Created by the U.S. Congress and enforced by the U.S. Department of Health and Human Services.

#### International Traffic in Arms Regulations (ITAR)
- **Core Purpose**: To control the export and import of defense-related articles and services.
- **Applies To**: U.S. individuals and entities involved in the manufacturing, exporting, and brokering of defense-related articles, services, and training.
- **Regulatory Entity**: Created by the U.S. Department of State.

#### Payment Card Industry Data Security Standard (PCI-DSS)
- **Core Purpose**: To enhance payment card security by establishing a set of requirements for processing cardholder data.
- **Applies To**: Merchants and service providers that store, process, or transmit cardholder data.
- **Regulatory Entity**: Established by major credit card companies including Visa, MasterCard, American Express, Discover, and JCB.

#### Sarbanes-Oxley Act (SOX)
- **Core Purpose**: To protect investors from fraudulent financial reporting by corporations.
- **Applies To**: Publicly traded companies in the U.S., their management, and their auditors.
- **Regulatory Entity**: Created by the U.S. Congress and enforced by the U.S. Securities and Exchange Commission.

**end of item**

# Security Models

## What is a Security Model?

A security model is a theoretical framework that defines how security mechanisms in a system should operate. It provides a conceptual structure to enforce security policies, ensuring that systems remain protected from potential threats. These models serve as blueprints or guides to design systems with robust security measures.

## Types of Security Models:

### 1. **State Machine Model**:
A system using the State Machine Model is considered secure if every possible state transition results in a secure state. It's a finite representation of a system's states and the transitions between those states.
- **Characteristic**: Tracks every state transition within the system.
- **Protection Focus**: Both integrity and confidentiality.
- **Usage**: Useful for ensuring systems maintain a secure state through all potential operations.

### 2. **Information Flow Model**:
This model ensures that information doesn't flow in such a way that it breaches security policies, like from a high-security level to a lower one.
- **Characteristic**: Controls the flow of information.
- **Protection Focus**: Primarily confidentiality.
- **Usage**: Useful in military or governmental scenarios where data leakage between clearance levels is a concern.

### 3. **Lattice-based Model**:
Involves a structured, mathematical approach where subjects and objects are given a set of rights, typically represented in a lattice diagram.
- **Characteristic**: Users are given specific rights corresponding to their security clearances.
- **Protection Focus**: Both integrity and confidentiality.
- **Usage**: Often used in environments with multiple classification levels.

### 4. **Non-Interference Model**:
Ensures that high-level activities cannot interfere with (or be inferred by) lower-level systems.
- **Characteristic**: No observable events at a higher security level influence events at a lower security level.
- **Protection Focus**: Primarily confidentiality.
- **Usage**: Critical for multi-level security systems.

## Three Properties of Security Models:

1. **Simple Property (s-property)**: Prevents read up (no-read-up, or "no read from a higher classification level").
2. **Discretionary Property (ds-property)**: Prevents write down (no-write-down, or "no write to a lower classification level").
3. **Star Property (*-property)**: Combines s-property and ds-property. It ensures that a subject with read and write capability can't read from a higher security level and then write that data to a lower security level.

## Security Models and Their Characteristics:

### 1. **Bell LaPadula Model**:
- **Type**: State Machine Model.
- **Focus**: Protects confidentiality.
- **Characteristics**: Enforces mandatory access controls, introduces the Simple Property and Star Property.
- **Usage**: Primarily used in government and military environments.

### 2. **Biba Model**:
- **Type**: State Machine Model.
- **Focus**: Protects integrity.
- **Characteristics**: Introduces the "no write up, no read down" principle (inverse of Bell LaPadula).
- **Usage**: Environments where data integrity is crucial.

### 3. **Brewer and Nash Model (nicknamed "The Chinese Wall")**:
- **Type**: Information Flow Model.
- **Focus**: Protects confidentiality.
- **Characteristics**: Ensures data isn't revealed during certain time periods.
- **Usage**: Financial systems where data about transactions shouldn't be accessible during specific windows of time.

### 4. **Clark-Wilson Model**:
- **Type**: Integrity Model.
- **Focus**: Protects integrity.
- **Characteristics**: Relies on well-formed transaction rules and certification rules to ensure data integrity.
- **Usage**: Commercial environments where transaction integrity is paramount.

### 5. **Graham-Denning Model (includes the "access control triplet")**:
- **Type**: State Machine Model.
- **Focus**: Protects both integrity and confidentiality.
- **Characteristics**: Focuses on the actions that subjects can perform on objects. It introduces the access control triplet: subject, object, and the type of access allowed.
- **Usage**: Theoretical model to describe fundamental operations to manage subjects and objects.

### 6. **Take Grant Model**:
- **Type**: State Machine Model.
- **Focus**: Primarily protects access rights.
- **Characteristics**: Uses directed graph where nodes represent subjects or objects and edges represent access rights.
- **Usage**: Descriptive tool for analyzing or designing secure systems.

**end of item**

# What are security controls?

Security controls are measures or safeguards put in place to protect the confidentiality, integrity, and availability of information assets and systems. They can be technical, physical, or administrative in nature and are designed to counteract vulnerabilities and mitigate threats.

### Functional order of controls:
1. **Deter**: Discourage potential attackers.
2. **Deny**: Prevent unauthorized access.
3. **Detect**: Identify breaches or attempts.
4. **Delay**: Slow down adversaries.
5. **Determine**: Evaluate the nature and impact of events.
6. **Decide**: Act upon information obtained.

### Categories of security controls:
- **Logical (technical) security controls**: These controls involve the use of software and hardware mechanisms to protect information systems. Examples include firewalls, encryption, and authentication mechanisms.
- **Administrative security controls**: These are the policies, procedures, and practices designed to manage and control access to information. Examples include security training, background checks, and security policies.
- **Physical security controls**: These are the tangible measures taken to protect the physical assets of an organization. Examples include security guards, locked doors, and CCTV.

### Site selection and facility design:

#### Considerations for site selection:
- Proximity to natural disaster zones (floods, earthquakes, etc.)
- Access to essential services and utilities
- Proximity to public transportation and infrastructure
- Availability of local workforce
- Neighborhood crime rates

#### Considerations for facility design:
- Secure entry and exit points
- Surveillance and monitoring capabilities
- Disaster resilience (e.g., raised floors in flood-prone areas)
- Adequate ventilation, heating, and cooling
- Secure areas for sensitive data and equipment

### Classes of fires and how they can be extinguished:

- **Class A (ASH) fires**: Involve common combustibles like wood, paper, and cloth. Extinguished with water or monoammonium phosphate.
- **Class B (BOIL) fires**: Involve flammable liquids or gases. Extinguished with carbon dioxide, foam, or dry chemicals.
- **Class C (CONDUCTIVE) fires**: Involve electrical equipment. Extinguished with non-conductive agents like CO2 or dry chemicals.
- **Class D (DILYTHIUM) fires**: Involve combustible metals. Extinguished with special metal fire extinguishers.
- **Class K (KITCHEN) fires**: Involve cooking oils and fats. Extinguished with wet chemical extinguishers.

### Types of sprinkler systems:

- **Deluge systems**: Used in high-hazard areas. Water is released from all sprinklers simultaneously when a fire is detected.
- **Dry pipe systems**: Pipes are filled with air until a fire is detected, then water is released.
- **Preaction systems**: Combine features of wet, dry, and deluge systems. Water release requires detection of a fire and a sprinkler activation.
- **Wet pipe systems**: Pipes are always filled with water, making them quicker to react but susceptible to freezing.

### Access control systems:

- **Biometric Systems**: Rely on unique physical or behavioral characteristics, like fingerprints or voice recognition.
- **Key Card Systems**: Use cards with magnetic strips, barcodes, or RFID chips for access.

### Temperature:

- **Ideal range**: 20°C to 24°C (68°F to 75°F).
- Damage can occur below 0°C (32°F) or above 27°C (80°F).

### Humidity:

- **Ideal range**: 40% to 60% relative humidity.
- Damage to electronics in **low humidity** environments: Electrostatic discharge can build up and discharge on electronic components, causing immediate or latent damage.
- Damage to electronics in **high humidity** environments: Corrosion of metal components, mold growth, and short-circuits.

### Fence:

- Optimal composition: Reinforced metal or concrete fences with anti-climbing measures.
- Optimal placement: Fences should be tall with minimal gaps. For deterring **casual intruders**, a fence height of around 6 to 8 feet is usually sufficient. For more **determined attackers**, fence heights of 8 feet or more, often with additional security measures like barbed or razor wire, are recommended.

### Lights:

- Optimal placement: Lights should cover all dark areas, especially around entrances.
- According to CISSP exam sources, ideal light height allows for wide coverage without creating shadows that intruders could exploit. For large outdoor areas, pole lights of about 20 feet high are common. For illumination, an average of 1-2 foot-candles is recommended for general security lighting. However, more critical areas might require up to 5 foot-candles.

### Types of security controls:

- **Deterrent security controls**: Discourage malicious activity. Examples: Warning signs, mock surveillance cameras.
- **Preventative security controls**: Stop incidents from occurring. Examples: Firewalls, access control lists, encryption.
- **Detective security controls**: Identify incidents. Examples: Intrusion detection systems, audit logs, security cameras.
- **Directive security controls**: Guide users to follow security practices. Examples: Security awareness training, security policy enforcement.
- **Compensating security controls**: Alternative controls used when standard controls aren't viable. Examples: Using multi-factor authentication where biometrics aren't feasible.
- **Corrective security controls**: Address the aftermath of an incident. Examples: Patch management, incident response plans.
- **Recovery security controls**: Restore and validate system performance for business operations after an incident. Examples: Backups, disaster recovery plans.

**end of item**