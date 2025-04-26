# Encryption Controls.Md


{
  "implemented-requirements": [
    {
      "uuid": "f902d5e1-17f8-4e2b-bf12-81c56e0e3f1d",
      "control-id": "CRY-01.3",
      "description": "The system integrates cryptographic mechanisms to ensure confidentiality and integrity during preparation for transmission. Sensitive data is encrypted using AES-256 before transmission, ensuring that only authorized parties can decrypt and access the information."
    },
    {
      "uuid": "c6c5d3f9-0a11-4d5b-bf6f-fb8d8f5ae3c2",
      "control-id": "CRY-01.4",
      "description": "The application utilizes a method to randomize communication patterns by implementing a token-based system, which conceals the actual communication flow, making it difficult for adversaries to predict the sequence of messages."
    },
    {
      "uuid": "8f4e84b8-2f61-4660-8873-1cfb4c6e3c34",
      "control-id": "CRY-02",
      "description": "Automated mechanisms employ OAuth 2.0 for systems to authenticate securely to the cryptographic module, ensuring that only verified entities can access cryptographic services."
    },
    {
      "uuid": "d1eb4abc-04d8-4d8b-9f34-1c1f28f7f7b8",
      "control-id": "CRY-06",
      "description": "The software utilizes TLS 1.2 for non-console administrative access, ensuring that all administrative traffic is encrypted to protect confidentiality and integrity from potential eavesdropping."
    },
    {
      "uuid": "1c9f4d9c-0a4d-4c75-b6f5-a69c1c56e4ef",
      "control-id": "CRY-08",
      "description": "An internal Public Key Infrastructure (PKI) is securely implemented, utilizing a CA server to issue certificates that strengthen secure communications within the network."
    },
    {
      "uuid": "7b4b0e4b-dc4e-4c44-b7a9-6761c0e4f3b2",
      "control-id": "CRY-09",
      "description": "The organization implements a key management solution that includes automated key rotation and storage, ensuring the confidentiality, integrity, and availability of cryptographic keys."
    },
    {
      "uuid": "e0b4c305-4e9e-4f96-bd1e-1a9f5a1d3b03",
      "control-id": "CRY-09.1",
      "description": "Symmetric keys are generated and managed using FIPS-compliant key management technology, ensuring compliance with federal standards for key production and management."
    },
    {
      "uuid": "b3e4f89e-2b31-4e2f-a1a6-1a9f5a1d3b4c",
      "control-id": "CRY-09.2",
      "description": "Asymmetric keys are generated and managed using FIPS-compliant methods, ensuring that private keys are adequately protected and managed throughout their lifecycle."
    },
    {
      "uuid": "e5c6c8a0-5e72-4c90-8f7d-6b1f8c7b4b54",
      "control-id": "CRY-09.4",
      "description": "The secure distribution of both symmetric and asymmetric cryptographic keys is facilitated through an industry-recognized key management platform, ensuring that keys are transmitted securely and are only accessible by authorized entities."
    },
    {
      "uuid": "b1f2d3e6-6d51-4e2b-8a4b-1a9f5a1d3b4d",
      "control-id": "CRY-09.5",
      "description": "Mechanisms are in place to bind cryptographic keys to individual identities through a user authentication system, ensuring accountability and traceability for key usage."
    },
    {
      "uuid": "f3e5e9b4-2e3f-4a5f-9f6d-1a9f5a1d4d5d",
      "control-id": "CRY-09.6",
      "description": "Guidance is provided to customers regarding key management practices when sharing cryptographic keys, ensuring that appropriate security measures are followed."
    }
  ]
}
