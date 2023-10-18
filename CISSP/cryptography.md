# Cryptography  

# Table of Contents
1. [Terms and Concepts](#terms-and-concepts)
2. [Ciphers](#ciphers)
3. [Common methods for securing traffic](#common-methods-for-securing-traffic)
4. [Hardware concepts](#hardware-concepts)
5. [Quantum](#quantum)
6. [Asymmetric Algorithms](#asymmetric-algorithms)
7. [Symmetric Algorithms](#symmetric-algorithms)
8. [Other](#other)

## Terms and Concepts

**Algorithm** - A cryptographic algorithm is a mathematical function used for encryption and decryption. Algorithms specify the steps required to transform plaintext into ciphertext and vice versa. Examples: AES, RSA, ECC, 3DES

**Cipher** - A cipher is a cryptographic algorithm used for encryption and decryption. Ciphers apply a key to plaintext to generate ciphertext. Examples: Caesar cipher, substitution cipher, transposition cipher.

**Code** - A code in cryptography converts plaintext into ciphertext using a codebook that maps words/phrases to codewords. Codes are more complex than ciphers and can achieve higher security. Example: Encoding "attack at dawn" as XYZ might give codeword "793".

**Exclusive OR (XOR)** - The XOR operation in cryptography combines two binary strings of equal length, outputting 1 where bits differ and 0 where bits are the same. XOR has useful mathematical properties for cryptography.

**Hash** - A cryptographic hash function converts an input into a fixed-size output known as a hash value or digest. Hashes are one-way functions, cannot be reversed to find the input. Used for message integrity. Examples: MD5, SHA-256.

**Split Knowledge** - Split knowledge distributes a secret (like a cryptographic key) into multiple pieces known as shares. A certain number of shares are required to reconstruct the secret. Improves security. 

**Substitution** - A substitution cipher replaces units of plaintext with ciphertext according to a fixed mapping. Units can be single letters, pairs of letters, etc. Simple substitution ciphers are easy to break. Example: Caesar Cipher.
  
**Symmetric vs Asymmetric Encryption** - Symmetric key cryptography uses the same secret key for encryption and decryption. Asymmetric (public) key cryptography uses a public key for encryption and private key for decryption.

**Transposition** - A transposition cipher changes the position of units in a plaintext message to encrypt it. Example: Rail Fence Cipher.
  
**Work Factor** - Work factor refers to the relative effort needed to defeat a cipher or hash function. Higher work factors improve security against brute force attacks.

**Zero-Knowledge Proof** - In a zero-knowledge proof, a prover convinces a verifier they know some secret information, without revealing the information. Used in cryptographic protocols.

[Back to ToC](#cryptography)

## Ciphers
  
**Block cipher** - Operates on fixed length blocks of plaintext to produce ciphertext blocks. Examples: AES, DES, Blowfish, CAST5

**Stream cipher** - Encrypts individual characters of plaintext one at a time. Examples: RC4, ChaCha20, Salsa20 

**Caesar cipher** - Simple substitution cipher that shifts alphabets by fixed number. Insecure, easy to break. Used as teaching example. Weakness: Small keyspace of 25 possibilities makes brute force trivial.
  
**One-time Pad** - Provides unbreakable encryption using random key as long as message but key distribution can be difficult. Weakness: Key reuse compromises security.

**Substitution cipher** - Substitutes characters for other characters based on fixed mapping that can be implemented manually but is vulnerable to frequency analysis. Examples: Affine, Atbash

**Transposition cipher** - Rearranges characters in plaintext to encrypt by changing letter positions rather than replacing them. Examples: Rail fence, route cipher, columnar transposition
  
**Vigenère cipher** - Improvement over monoalphabetic ciphers using polyalphabetic substitution with repeating key, but vulnerable to Kasiski examination and pattern matching.

[Back to ToC](#cryptography)

## Common methods for securing traffic

**Securing email** - This refers to the use of cryptographic techniques and protocols, like S/MIME (Secure/Multipurpose Internet Mail Extensions) and PGP (Pretty Good Privacy), to protect the confidentiality and integrity of email content and attachments during transit.

**Securing network traffic** - This involves using security measures like VPNs (Virtual Private Networks), which create an encrypted tunnel for data to pass through, or protocols like IPSec (Internet Protocol Security) to ensure that data transmitted over a network remains confidential and has not been tampered with. 

**Securing web traffic** - This typically involves the use of SSL/TLS (Secure Sockets Layer/Transport Layer Security) protocols to encrypt and secure communications between a web user's browser and the web server, ensuring both the confidentiality and authenticity of the data. Websites secured in this manner often have URLs starting with "https://".

[Back to ToC](#cryptography)

## Hardware concepts

**Hardware Security Module (HSM)** - A dedicated hardware device specifically designed to manage, generate, store, and protect cryptographic keys. HSMs offer strong security measures to prevent theft or unauthorized access to the cryptographic material stored.

**Trusted Platform Module (TPM)** - A specialized chip on an endpoint device that stores RSA encryption keys specific to the host system for hardware authentication. The TPM provides a secure generation and storage of cryptographic keys, and it ensures platform integrity.

**Full Disk Encryption (FDE)** - A cryptographic method that encrypts all the data on a hard drive, including the OS and system files, ensuring that in case of loss or theft, the data remains inaccessible without the correct decryption key or password.

[Back to ToC](#cryptography)

## Quantum

**Grover's algorithm** - A quantum algorithm that searches an unsorted database faster than classical algorithms. Potentially reduces the security of cryptographic hashes and symmetric ciphers by half their key lengths. 

**Shor's algorithm** - Quantum algorithm that can factor integers efficiently. Threatens RSA and other public-key algorithms based on the hardness of factoring.

**Post-quantum cryptography** - Cryptographic algorithms that are thought to be secure against the potential future capabilities of quantum computers. Designed to be secure against quantum computers by focusing on problems outside complexity classes like integer factorization. Resistant to Shor's and Grover's algorithms. Examples: Lattice-based, code-based, hash-based, multivariate quadratics.

[Back to ToC](#cryptography)

# Asymmetric Algorithms

**Diffie-Hellman Ephemeral**  
Allows two parties to establish a shared secret over an insecure channel.
- Type: Asymmetric key exchange
- Widespread Use: Yes

**Digital Signature Algorithm**
Digital signature algorithm utilizing the SHA-1 hash function developed by the NSA.
- Type: Asymmetric signature algorithm
- Key Length: 1024-3072 bits  
- Widespread Use: Yes

**El Gamal** 
Public key cryptosystem using discrete logarithms over finite fields.
- Type: Asymmetric encryption algorithm
- Key Length: 1024+ bits
- Widespread Use: No

**Elliptic curve**   
Mathematical curve that is the foundation for elliptic curve cryptography algorithms.
- Type: Basis for asymmetric algorithms

**Elliptic-curve Cryptography**  
Public key cryptography based on elliptic curve discrete logarithm problem.
- Type: Asymmetric encryption and signatures
- Widespread Use: Yes

**Elliptic-curve Diffie-Hellman Ephemeral**
Allows two parties to establish a shared secret over an insecure channel using elliptic curve cryptography.
- Type: Asymmetric key exchange
- Widespread Use: Yes

**Elliptic-curve Digital Signature Algorithm** 
Digital signature algorithm using elliptic curve cryptography.
- Type: Asymmetric signature algorithm 
- Key Length: 160-521 bits
- Widespread Use: Yes
  
**Rivest, Shamir, & Adleman**
Creators of the widely used RSA asymmetric cryptography algorithm.
- Type: Asymmetric algorithm creators

**RSA algorithm**
First public key cryptosystem widely adopted based on factoring large primes.
- Type: Asymmetric encryption and signatures
- Key Length: 1024-4096 bits
- Widespread Use: Yes

[Back to ToC](#cryptography)

# Symmetric Algorithms
  
**Data Encryption Standard**
Early symmetric block cipher standardized by NIST but now considered insecure.
- Type: Legacy symmetric algorithm 
- Key Length: 56 bits
- Widespread Use: No

**Message Digest 5**  
MD5 is a widely used but now broken cryptographic hash function.
- Type: Cryptographic hash function
- Widespread Use: No

**One-time pad**
Unbreakable encryption using a random key as long the message but difficult key distribution.
- Type: Symmetric encryption
- Widespread Use: No
  
**RACE Integrity Primitives Evaluation Message Digest** 
Early hash function that was precursor to SHA-1 algorithm.
- Type: Cryptographic hash predecessor to SHA-1  
- Widespread Use: No

**Rivest Cipher version 4**
RC4 is a widely used stream cipher but has weaknesses enabling attacks.
- Type: Symmetric stream cipher
- Widespread Use: No

**Secure Hashing Algorithm** 
Cryptographic hash functions like SHA-1 and SHA-256 used for message integrity.
- Type: Cryptographic hash function
- Widespread Use: Yes

**Triple Data Encryption Standard**
TDEA applies DES three times for stronger encryption.
- Type: Symmetric block cipher 
- Key Length: 168 bits
- Widespread Use: No

[Back to ToC](#cryptography)

## Other
  
**Challenge-Handshake Authentication Protocol**   
CHAP authenticates a user through an MD5 hash password exchange.
- Function: Authentication protocol
- Widespread Use: Yes
  
**Counter-Mode**  
Block cipher mode turning block cipher into stream cipher using a counter.
- Function: Symmetric encryption mode
- Widespread Use: Yes

**Counter-Mode/CBC-MAC Protocol**
Authentication protocol using cipher block chaining and message authentication codes.  
- Function: Authentication protocol 
- Widespread Use: Yes

**Cryptographic keys**
Secret values used during encryption and decryption processes.
- Function: Generic term for encryption keys

**Encrypted File System**  
File system that encrypts data at rest transparently.
- Function: Encrypted file storage

**Galois/Counter Mode**   
Authenticated encryption mode providing confidentiality and authenticity.
- Function: Authenticated encryption mode
- Widespread Use: Yes

**Hashed Message Authentication Code**  
Symmetric algorithm using hash and secret key to authenticate messages.
- Function: Symmetric authentication algorithm
- Widespread Use: Yes

**Initialization Vector**    
Random seed value used by encryption modes for first block.
- Function: Starting variable for encryption modes
  
**Internet Key Exchange**   
Standardized key exchange protocol commonly used with IPsec.
- Function: Key exchange protocol
- Widespread Use: Yes

**Key clustering**   
Related keys used together make cryptanalysis easier.  
- Function: Cryptanalysis technique

**Key Encryption Key**  
Key used to encrypt lower level keys like data encryption keys.
- Function: Key wrapping

**Perfect Forward Secrecy**     
Ensures session keys cannot be compromised by long term key compromise.
- Function: Forward secrecy
  
**Preshared Key**   
Symmetric key distributed manually before use.
- Function: Manual key distribution

**Pretty Good Privacy**  
Open source end user encryption software suite.
- Function: Encryption software

**Public Key Cryptography Standards**   
Standards for implementing RSA including formatting and padding.
- Function: RSA standards

**Secure Sockets Layer**  
Early encrypted network protocol replaced by Transport Layer Security.
- Function: Legacy encrypted network protocol
- Widespread Use: No
  
**Secure/Multipurpose Internet Mail Extensions**  
Standard for encrypting and authenticating email.
- Function: Email encryption standard
- Widespread Use: Yes

**Simultaneous Authentication of Equals**    
Allows two parties to authenticate each other simultaneously. 
- Function: Mutual authentication

**SSH File Transfer Protocol**  
Secure network protocol for transferring files over SSH.
- Function: Secure file transfer
- Widespread Use: Yes

**Transport Layer Security**  
Modern encrypted network protocol that replaced Secure Sockets Layer.
- Function: Encrypted network protocol
- Widespread Use: Yes

[Back to ToC](#cryptography)