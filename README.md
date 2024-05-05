
# Cyber Guardian

## Project Goal
Cyber Guardian aims to provide robust security for digital documents through encryption, decryption, signing, and verification to ensure data integrity and confidentiality.

## Target Audience
This application is intended for individuals or organizations needing to secure sensitive information in their documents. It is especially useful for those without a deep background in cryptography.

## Current Capabilities
- Encrypt and decrypt documents to protect confidentiality.
- Sign and verify documents to ensure authenticity and integrity.
- User-friendly interface for easy interaction with security features.

## Getting Started
1. Clone the repository.
2. Install required libraries: `pip install bcrypt nacl ipywidgets`.
3. Run `Cyber_Guardian.ipynb` via Jupyter Notebook.

## System Overview
Cyber Guardian is built using Python and utilizes several libraries such as `bcrypt`, `nacl`, and `ipywidgets` for cryptographic operations and user interface management. The system architecture integrates these components seamlessly to provide a secure environment for document handling.

## Security Considerations
The application uses industry-standard encryption and hashing algorithms to secure data. Risks include potential exposure to data breaches if cryptographic keys are mishandled. Measures such as key encryption and secure storage practices are in place to mitigate these risks.

## Future Developments
- Expanding file format support.
- Enhancing the cryptographic algorithm strength.
- Implementing additional user management features.

## Lessons Learned
During development, initial attempts to implement custom encryption algorithms were replaced with industry-standard libraries to enhance security and maintainability.
