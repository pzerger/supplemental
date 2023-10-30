# Threat Modeling

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