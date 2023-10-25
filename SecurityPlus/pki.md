# Public Key Infrastructure (PKI)

- [Certificate Authority Types](#certificate-authority-types)
- [Certificate Types](#certificate-types)
- [Certificate Authorities](#certificate-authorities)
- [Certificates](#certificates)  
- [Certificate Status and Revocation](#certificate-status-and-revocation)
- [Certificate Usage](#certificate-usage)

## Certificate Authority Types

- **Certificate Authority (CA)**: An entity that issues digital certificates. CAs act as a trusted third party.

- **Root certification authority** - The top level CA that issues certificates to subordinate CAs, but does not issue certs to end entities.

- **Intermediate certification authority** - A CA issued a certificate by a root or another intermediate authority to issue end entity certificates.

- **Issuing certification authority** - The CA that provides certificates directly to end entities like servers, devices or individuals.

[Return to ToC](#public-key-infrastructure-pki)

## Certificate Types 

- **Distinguished Encoding Rules (DER)** - Binary encoded certificate commonly with `.crt` extension. Does NOT include the private key.

- **Privacy enhanced mail (PEM)** - Base64 encoded cert with header/footer, `.pem` extension. DOES include the private key.

- **Base64-encoded (CER)** - Base64 encoded version of DER cert, uses `.cer` extension. Does NOT include the private key.

- **PKCS#12 standard (P12)** - Encrypted container with private key and certs, uses `.p12` or `.pfx`.

- **Cryptographic Message Syntax Standard (P7B)** - Just the certificates without private key, `.p7b` extension. Does NOT include the private key.

[Return to ToC](#public-key-infrastructure-pki)


## Certificates

- **Certificate**: A digital document that certifies the ownership of a public key by the named subject of the certificate.

- **Common Name**: An attribute within a certificate that provides an identifier for the subject of the certificate, often a hostname or organization name.

- **Subject Alternative Name (SAN)**: An optional extension that allows additional hostnames or IPs to be associated with a certificate. Use when you need to support multiple DNS domains and IP addresses from a single certificate.

- **Wildcard Certificate**: A certificate that secures a domain and unlimited number of subdomains, e.g. *.example.com. Use when you need to support multiple host names in the same DNS domain from a single certificate.

[Return to ToC](#public-key-infrastructure-pki)

## Certificate Status and Revocation

- **Certificate Revocation List (CRL)**: A list of certificates that have been revoked by the CA before their expiration date.

- **Online Certificate Status Protocol (OCSP)**: A protocol used to obtain the revocation status of a digital certificate. 

- **Certificate Stapling**: A method for a server to send its certificates and a valid OCSP response to a client, to prove its legitimacy.

[Return to ToC](#public-key-infrastructure-pki)

## Certificate Usage  

- **Certificate Pinning**: A process where web applications instruct clients to expect a specific public key or set of keys, enhancing security.

- **Certificate Stapling**: A method for a server to send its certificates and a valid OCSP response to a client, to prove its legitimacy.

- **Certificate Signing Request (CSR)**: A message sent from an applicant to a CA to apply for a digital identity certificate. 

- **Certificate Renewal**: The process of obtaining a new certificate for an existing key pair before the old certificate expires.

- **Certificate Expiration**: Certificates have a defined validity period and expire after that time if not renewed.

[Return to ToC](#public-key-infrastructure-pki)