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