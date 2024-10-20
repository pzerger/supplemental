# Data Security

## Table of Contents

- [Data/Information Lifecycle](#datainformation-lifecycle)
- [Data Destruction](#data-destruction)
- [Data Protection](#data-protection)
- [Data Roles](#data-roles)
- [Sensitive Data Types](#sensitive-data-types)

## Data/Information Lifecycle

Description of how data is created, stored, used, and retired.

- **Create/Creation**: The process of generating new data or information.

- **Classification**: Categorizing data based on its sensitivity and importance to determine security controls. Data should be classified as soon as possible after creation to facilitate data protection.

- **Store/Storage**: Saving and retaining data in a repository like a database or file server. Data should be encrypted at rest.

- **Use/Usage**: Accessing and utilizing data for its intended business purpose. Data should be encrypted in-transit.

- **Share/Sharing**: Disseminating or providing access to data to authorized users. Data protection should travel with the data, even outside the organization.

- **Archival/Retention**: Storing data long-term for legal, compliance or historical purposes. 

- **Destruction**: Permanently deleting data when no longer needed. Data should be destroyed as quickly as allowable, as additional data = additional risk.

[Back to ToC](#table-of-contents)

## Data Destruction

Methods and practices for securely destroying data to prevent unauthorized access.

- **Clearing (overwriting)**: Overwriting data making it recoverable with forensics. Leaves data remnants. Allows forensic recovery. Low security.

- **Cryptographic erasure**: Encrypting data then destroying the keys. Leaves encrypted data remnants. Prevents forensic recovery if keys are destroyed. Medium security.

- **Degaussing**: Removing magnetic field erasing data on tapes/disks. Leaves no data remnants. Prevents forensic recovery. High security. 

- **Destruction**: Physical destruction of media. Leaves no data remnants if destroyed completely. Prevents forensic recovery if fully destroyed. High security.

- **Erasing**: Deleting pointers to data. Leaves data remnants. Allows forensic recovery. Low security.

- **Purging**: Removing data completely. Leaves no data remnants. Prevents forensic recovery. High security.

[Back to ToC](#table-of-contents)

## Data Protection

Strategies and tools used to protect data from corruption, compromise or loss.

- **Anonymization**: Removing personally identifiable information from data.

- **Cloud Access Security Broker (CASB)**: Managing access and enforcing security policies for cloud services.

- **Data classification**: Categorizing data by sensitivity for access control.

- **Data Loss Prevention (DLP)**: Preventing unauthorized release of sensitive data.

- **Data marking/labeling**: Visually tagging data for handling instructions.

- **Data handling**: Processes for using and protecting data.

- **Pseudonymization**: Replacing identifying data with artificial identifiers.

- **Record retention**: Maintaining records for a defined period.

- **Tape Backup Security**: Protecting tape backups from theft/damage.

- **Tokenization**: The process of replacing sensitive data with unique identification symbols or tokens that have no extrinsic or exploitable meaning or value. Provides security benefits for sensitive data like payment cards, social security numbers, customer credentials and healthcare records while still allowing systems to use that data in operations like analytics and machine learning.

[Back to ToC](#table-of-contents)

## Data Roles

The responsibilities and requirements of those who interact with data in various capacities.

- **Asset Owners**: Responsible for an organization's assets.

- **Business/Mission Owners**: Own business processes using the data.

- **Data Administrators**: Manage databases and data storage systems.  

- **Data breach notification**: Required disclosure of breaches.

- **Data Controller (GDPR)**: Determines data processing purposes and means.

- **Data custodian**: Protects and uses data according to policy.

- **Data owner/controller (GDPR)**: Determines purposes and means of processing data.

- **Data Processor (GDPR)**: Processes personal data on controller's behalf.

- **Data subject (GDPR)**: Person identified by their personal data.

- **Data Transfer (GDPR)**: Moving personal data cross-border.

- **Data User**: Access and uses data appropriately.

[Back to ToC](#table-of-contents)

## Sensitive Data Types

Sensitive data encompasses any information that, if compromised, could lead to harm, loss, or unauthorized access. Here are some common types:

### Personally Identifiable Information (PII)
PII is any data that can be used to identify an individual. This includes:

* **Basic information:** Name, address, phone number, email address
* **Identifiers:** Social Security number, driver's license number, passport number
* **Financial data:** Bank account numbers, credit card numbers
* **Biometric data:** Fingerprints, facial recognition, iris scans
* **Online identifiers:** IP address, cookie data
* **Geolocation data:** Precise location information

### Protected Health Information (PHI)
PHI is any information about health status, provision of healthcare, or payment for healthcare that is created or received by a covered entity. This includes:

* Medical history
* Diagnoses
* Treatments
* Prescriptions
* Insurance information
* Billing records
* Patient names and addresses

### Cardholder Data (CHD)
CHD refers to any information related to a credit or debit card, including:

* Cardholder name
* Card number
* Card expiration date
* Card verification code (CVV)
* PIN

### Financial Information
Financial information encompasses data related to an individual's or organization's financial status. This includes:

* Bank account numbers and routing numbers
* Account balances and transaction history
* Payment card details (beyond CHD, such as payment preferences, billing addresses)
* Investment information
* Tax records

### Intellectual Property
Intellectual property (IP) refers to creations of the mind, such as inventions, literary and artistic works, designs, and symbols. Sensitive IP includes:

* Trade secrets: Confidential business information that provides a competitive advantage
* Patents: Exclusive rights granted for inventions
* Copyrights: Exclusive rights for literary, dramatic, musical, and artistic works
* Trademarks: Words, symbols, or designs identifying goods or services

### Government Identification
Government identification documents are issued by government authorities for verification of identity. Sensitive data within these documents includes:

* Passport numbers
* Driver's license numbers
* Military ID numbers
* National identification numbers

### Government Records
Government records contain information collected by government agencies. Sensitive data within these records includes:

* Tax returns
* Voter registration information
* Criminal records
* Birth and death certificates
* Social security records

### Children's Information
Children's information is any data related to individuals under a specified age (typically 13 in the US). This includes:

* Name
* Address
* Online activity
* Personal preferences
* Educational information

### Biometric Data
Biometric data refers to unique physical characteristics used for identification. This includes:

* Fingerprints
* Facial recognition
* Iris scans
* Voice patterns
* DNA

**Note:** The specific definition of sensitive data can vary depending on the jurisdiction and industry. It's essential to comply with relevant data protection regulations and industry standards.

