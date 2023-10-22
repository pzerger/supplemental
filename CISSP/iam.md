# Identity and Access Management Concepts

- [Authentication Methods](#authentication-methods)
- [Authorization Concepts](#authorization-concepts)  
- [Access Control Models](#access-control-models)
- [Identity Management](#identity-management)
- [Other Security Concepts](#other-security-concepts)

## Authentication Methods

- **Multifactor Authentication** - Require two or more factors to authenticate like a password and one-time code or biometric. Stronger than single factor. 

- **Single Sign-On** - Allows access to multiple systems after signing in once. Provides convenience and centralizes authentication.

- **Kerberos** - Authentication protocol using secret-key cryptography and a trusted third party - the key distribution center. Provides single sign-on. 

- **Biometric Systems** - Uses biological traits like fingerprints or retina scans to identify individuals. Avoid issues like lost passwords.

- **One-Time Password** - Password only valid for a single session or transaction. Protects against replay attacks.

[Back to ToC](#identity-and-access-management-concepts)

## Authorization Concepts

- **Authorization** - Process of determining what level of access a subject is allowed to a certain object based on rules. Usually done after authentication.

- **Access Control List** - Specifies access rights granted to users or groups for specific objects like files or directories. Used to implement discretionary or role-based access control.

- **Open Authorization (OAuth)** - Standard for token-based authorization workflows. Allows access without exposing credentials. Used by many web APIs. 

[Back to ToC](#identity-and-access-management-concepts)

## Access Control Models  

- **Discretionary Access Control** - Subjects can transfer access rights to objects under their control to other subjects. Identity-based access control.

- **Mandatory Access Control** - System-controlled access based on subject and object labels like classification level. Subjects cannot change access controls.  

- **Role-Based Access Control** - Grants access based on subject's roles and responsibilities. Simplifies privilege management.

- **Attribute-based Access Control** - Controls access based on attributes of the subject, object, environment conditions, and contextual information. Useful for dynamic access control models.

[Back to ToC](#identity-and-access-management-concepts)

## Identity Management

- **Identity Proofing** - Process used to collect and verify information about a person for the purpose of issuing credentials. Ensures proper binding of identity to credentials.

- **Identity Provider** - Entity that creates, maintains, manages identity information, provides authentication services, and asserts subject identities.

- **Identity as a service (IDaaS)** - Outsources identity management functions like single sign-on, authentication, authorization, and auditing to a cloud provider.

[Back to ToC](#identity-and-access-management-concepts)

## Other Security Concepts

- **Access Review** - Periodic review of user entitlements to ensure they are appropriate based on job function. Helps revoke unnecessary privileges. 

- **User Entitlement Audit** - Reviews user access across systems and applications to find inappropriate, excessive or unused entitlements to revoke.

- **Privileged Access Management** - Controls and monitors access to privileged accounts like admins. May include just-in-time provisioning.

- **Personal Identity Verification** - United States standard (FIPS 201) for identity credentials like smart cards. Used by government agencies.

- **False Acceptance Rate** - Percentage of invalid inputs incorrectly accepted as valid by a biometric system. Measure of type I errors. 

- **False Rejection Rate** - Percentage of valid inputs incorrectly rejected as invalid by a biometric system. Measure of type II errors.

- **Crossover Error Rate** - Rate at which false acceptances (type 1 errors) equal false rejections (type 2 errors) in a biometric system. Used to measure system accuracy.

[Back to ToC](#identity-and-access-management-concepts)