Here is the answer with Crossover Error Rate (CER) added:

# Identity and Access Management Concepts

- [Attribute-based Access Control](#attribute-based-access-control)
- [Access Control List](#access-control-list)
- [Access Review](#access-review)
- [Authorization](#authorization)
- [Authentication](#authentication)
- [Biometric Systems](#biometric-systems)
- [Discretionary Access Control](#discretionary-access-control)
- [False Acceptance Rate](#false-acceptance-rate)
- [False Rejection Rate](#false-rejection-rate)
- [Crossover Error Rate](#crossover-error-rate)
- [Identity as a service (IDaaS)](#identity-as-a-service-idaas)
- [Identity proofing](#identity-proofing)
- [Identity Provider](#identity-provider)
- [Kerberos](#kerberos)
- [Key Distribution Center](#key-distribution-center)
- [Mandatory Access Control](#mandatory-access-control)
- [Multifactor Authentication](#multifactor-authentication)
- [One-Time Password](#one-time-password)
- [Open Authorization (OAuth)](#open-authorization-oauth)
- [Privileged Access Management](#privileged-access-management)
- [Personal Identity Verification](#personal-identity-verification)
- [Role-Based Access Control](#role-based-access-control)
- [Single factor authentication](#single-factor-authentication)
- [Single Sign-On](#single-sign-on)
- [Ticket Granting Ticket](#ticket-granting-ticket) 
- [User Entitlement Audit](#user-entitlement-audit)

## Attribute-based Access Control
- Controls access based on attributes of the subject, object, environment conditions, and contextual information. Useful for dynamic access control models.

## Access Control List
- Specifies access rights granted to users or groups for specific objects like files or directories. Used to implement discretionary or role-based access control. 

## Access Review 
- Periodic review of user entitlements to ensure they are appropriate based on job function. Helps revoke unnecessary privileges.

## Authorization
- Process of determining what level of access a subject is allowed to a certain object based on rules. Usually done after authentication.  

## Authentication
- Verifying the identity of a subject who generates a request. Typically by validating something they know (password), have (smartcard), or are (biometrics).

## Biometric Systems
- Uses biological traits like fingerprints or retina scans to identify individuals. Avoid issues like lost passwords.

## Discretionary Access Control  
- Subjects can transfer access rights to objects under their control to other subjects. Identity-based access control.

## False Acceptance Rate
- Percentage of invalid inputs incorrectly accepted as valid by a biometric system. Measure of type I errors.

## False Rejection Rate
- Percentage of valid inputs incorrectly rejected as invalid by a biometric system. Measure of type II errors.

## Crossover Error Rate
- Rate at which false acceptances equal false rejections in a biometric system. Used to measure system accuracy.

## Identity as a service (IDaaS)
- Outsources identity management functions like single sign-on, authentication, authorization, and auditing to a cloud provider.

## Identity proofing
- Process used to collect and verify information about a person for the purpose of issuing credentials. Ensures proper binding of identity to credentials.  

## Identity Provider
- Entity that creates, maintains, manages identity information, provides authentication services, and asserts subject identities.

## Kerberos
- Authentication protocol using secret-key cryptography and a trusted third party - the key distribution center. Provides single sign-on.

## Key Distribution Center
- Trusted third party in Kerberos that issues ticket granting tickets used for authentication. 

## Mandatory Access Control
- System-controlled access based on subject and object labels like classification level. Subjects cannot change access controls.

## Multifactor Authentication 
- Require two or more factors to authenticate like a password (know) and one-time code (have) or biometric (are). Stronger than single factor.

## One-Time Password
- Password only valid for a single session or transaction. Protects against replay attacks.

## Open Authorization (OAuth)
- Standard for token-based authorization workflows. Allows access without exposing credentials. Used by many web APIs.

## Privileged Access Management
- Controls and monitors access to privileged accounts like admins. May include just-in-time provisioning.

## Personal Identity Verification
- United States standard (FIPS 201) for identity credentials like smart cards. Used by government agencies. 

## Role-Based Access Control
- Grants access based on subject's roles and responsibilities. Simplifies privilege management.

## Single factor authentication
- Only one factor used to authenticate like a password. Weaker security than multifactor. 

## Single Sign-On 
- Allows access to multiple systems after signing in once. Provides convenience and centralizes authentication.

## Ticket Granting Ticket
- Issued by the KDC in Kerberos and used to obtain additional service tickets without reauthenticating.

## User Entitlement Audit
- Reviews user access across systems and applications to find inappropriate, excessive or unused entitlements to revoke.