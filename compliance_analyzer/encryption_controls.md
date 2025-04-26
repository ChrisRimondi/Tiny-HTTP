# Encryption Controls.Md


{
  "implemented-requirements": [
    {
      "uuid": "a1b2c3d4-e5f6-7890-abcd-ef1234567890",
      "control-id": "CRY-01.3",
      "description": "The software implements cryptographic mechanisms to ensure data confidentiality and integrity during transmission by utilizing TLS 1.2. This is achieved by configuring the web server to enforce HTTPS using a valid SSL certificate, preventing unauthorized access during data transmission."
    },
    {
      "uuid": "b1c2d3e4-f5g6-7890-abcd-ef1234567891",
      "control-id": "CRY-01.4",
      "description": "The software employs cryptographic techniques to randomize communication patterns by implementing a secure session management system. This ensures that session identifiers are unique and unpredictable, minimizing the risk of session hijacking."
    },
    {
      "uuid": "c1d2e3f4-g5h6-7890-abcd-ef1234567892",
      "control-id": "CRY-02",
      "description": "Automated mechanisms for authentication to cryptographic modules are implemented using secure API calls that authenticate the server to a Hardware Security Module (HSM) for key management. This ensures that only authorized systems can access cryptographic functions."
    },
    {
      "uuid": "d1e2f3g4-h5i6-7890-abcd-ef1234567893",
      "control-id": "CRY-06",
      "description": "Non-console administrative access is protected using a VPN and strong encryption protocols. All administrative actions are logged, and access is restricted to authenticated and authorized users only."
    },
    {
      "uuid": "e1f2g3h4-i5j6-7890-abcd-ef1234567894",
      "control-id": "CRY-08",
      "description": "The organization has implemented an internal Public Key Infrastructure (PKI) using a dedicated certificate authority (CA) to issue and manage digital certificates securely. This includes regular audits and updates to the PKI system to maintain security."
    },
    {
      "uuid": "f1g2h3i4-j5k6-7890-abcd-ef1234567895",
      "control-id": "CRY-09",
      "description": "The software includes mechanisms for cryptographic key management, ensuring that keys are stored securely using encryption at rest and that access is controlled through role-based access controls (RBAC)."
    },
    {
      "uuid": "g1h2i3j4-k5l6-7890-abcd-ef1234567896",
      "control-id": "CRY-09.1",
      "description": "The system facilitates the production and management of symmetric cryptographic keys using FIPS-compliant key management technology. Regular key rotation policies are enforced to enhance security."
    },
    {
      "uuid": "h1i2j3k4-l5m6-7890-abcd-ef1234567897",
      "control-id": "CRY-09.2",
      "description": "Asymmetric cryptographic keys are generated and managed using FIPS-compliant processes to protect the user's private key. This includes secure storage and access controls to prevent unauthorized access."
    },
    {
      "uuid": "i1j2k3l4-m5n6-7890-abcd-ef1234567898",
      "control-id": "CRY-09.4",
      "description": "The secure distribution of symmetric and asymmetric cryptographic keys is facilitated through established key exchange protocols such as Diffie-Hellman, ensuring that keys are exchanged securely."
    },
    {
      "uuid": "j1k2l3m4-n5o6-7890-abcd-ef1234567899",
      "control-id": "CRY-09.5",
      "description": "Cryptographic keys are bound to individual identities using identity management systems that enforce strict authentication and authorization protocols, ensuring accountability."
    },
    {
      "uuid": "k1l2m3n4-o5p6-7890-abcd-ef1234567800",
      "control-id": "CRY-09.6",
      "description": "Customers are provided with comprehensive key management guidance whenever cryptographic keys are shared, including best practices for storage and use to ensure security."
    }
  ]
}
