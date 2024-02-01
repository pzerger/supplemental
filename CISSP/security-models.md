# Security Models

## Table of Contents

- [Security Model Types](#security-models)
  - [State Machine Model](#state-machine-model)
  - [Information Flow Model](#information-flow-model)
  - [Lattice-based Model](#lattice-based-model)
  - [Non-Interference Model](#non-interference-model) 
- [Models Grouped by Focus](#models-grouped-by-focus)
- [Security Model Properties](#security-model-properties)
- [Key Security Models](#key-security-models)
  - [Bell-LaPadula Model](#bell-lapadula-model)
  - [Biba Model](#biba-model)
  - [Brewer and Nash Model](#brewer-and-nash-model)
  - [Clark-Wilson Model](#clark-wilson-model)
  - [Graham-Denning Model](#graham-denning-model)
  - [Take-Grant Model](#take-grant-model)

## Security Model Types

### State Machine Model

- Type: Formal model  
- Protects: Integrity and confidentiality
- Used for: Specifying and enforcing security policies
- Characteristics: Defines finite states and transitions between them to model allowable actions in a system

### Information Flow Model

- Type: Formal model
- Protects: Confidentiality
- Used for: Tracking information flow between subjects and objects
- Characteristics: Labels subjects and objects with security levels and ensures no flows from higher to lower levels

### Lattice-based Model

- Type: Formal model
- Protects: Confidentiality 
- Used for: Multilevel security policies with hierarchical security levels
- Characteristics: Defines partially ordered set of security levels with least upper bound and greatest lower bound operations

### Non-Interference Model

- Type: Formal model
- Protects: Confidentiality
- Used for: Isolation between classifications in multilevel systems
- Characteristics: Ensures actions by users at high security levels do not affect or interfere with lower security levels

[Back to ToC](#table-of-contents)

## Models Grouped by Focus

Here is a grouping of security models based on whether they focus primarily on protecting confidentiality or integrity:

**Confidentiality Focus**

- Bell-LaPadula Model
- Brewer and Nash Model (Chinese Wall)  
- Graham-Denning Model
- Information Flow Model
- Take-Grant Model

**Integrity Focus**

- Biba Model
- Clark-Wilson Model

**Mixed Confidentiality and Integrity**

- State Machine Model

[Back to ToC](#table-of-contents)

## Security Model Properties

The simple property, discretionary property, and star property are key elements that can be used to categorize and understand the goals of different security models:

**Simple property** - The simple property (read) prevents subjects from reading objects at higher security levels, protecting confidentiality. Models like Bell-LaPadula aim to enforce this property.

**Discretionary property** - The discretionary property allows owners of objects to control the access rights to those objects. This supports user privacy and data ownership.

**Star property** - The star property (write) prevents subjects from writing objects at lower security levels, protecting integrity. Models like Biba aim to enforce this property.

[Back to ToC](#table-of-contents)

## Key Security Models

### Bell-LaPadula Model

- Type: Information flow model
- Protects: Confidentiality
- Levels: Classification levels and categories
- Rules: No read up, no write down
- Used in: Multilevel secure military systems
- Based on access control triple of subject, object, access rights

### Biba Model

- Type: Information flow model  
- Protects: Integrity
- Levels: Integrity levels
- Rules: No read down, no write up
- Used in: Protecting integrity in critical systems
- Based on access control triple of subject, object, access rights

### Brewer and Nash Model (aka "Chinese Wall model")

- Type: Information flow model  
- Protects: Confidentiality and conflict of interest
- Levels: Conflict of interest classes  
- Rules: Subjects can only access data in one class per dataset
- Used in: Financial, legal, auditing systems

### Clark-Wilson Model

- Type: Integrity model 
- Protects: Integrity
- Levels: None
- Rules: Well-formed transactions transform valid states
- Used in: Database/transaction systems

### Graham-Denning Model 

- Type: Information flow model
- Protects: Confidentiality 
- Levels: Security labels with 8 primitive processes
- Rules: Information flow control through processes
- Used in: Multilevel secure OS/applications
- Based on access control triple of subject, object, access rights

### Take-Grant Model

- Type: Information flow model 
- Protects: Confidentiality
- Levels: Objects and privileges
- Rules: Transfer privileges between subjects/objects  
- Used in: Specifying access control policies
- Based on access control triple of subject, object, access rights

[Back to ToC](#table-of-contents)