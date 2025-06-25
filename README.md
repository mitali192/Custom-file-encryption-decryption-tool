# Custom-file-encryption-decryption-tool
A command-line utility in Python for advanced file encryption and decryption. It employs AES-256 symmetric encryption with robust PBKDF2 key derivation from a user-defined passphrase, ensuring strong data confidentiality.

Features
- Encrypts files using AES-256 in CBC mode  
- Securely derives keys from passwords using PBKDF2 with SHA256  
- Generates unique cryptographic salts and Initialization Vectors (IVs) per encryption  
- Supports large files by processing data in chunks  
- Includes comprehensive error handling for file operations and password validation

Technologies Used
- Python 3.x  
- cryptography library (AES, PBKDF2, padding primitives)  
- secrets module (Cryptographically strong randomness)

File Structure
- `encrypt_tool.py` → Main encryption/decryption script handling password prompts, AES encryption logic, and file processing

How to Run
1. Clone the repository (ensure `encrypt_tool.py` is present):
git clone https://github.com/YOUR_USERNAME/YOUR_REPO_NAME.git
cd YOUR_REPO_NAME
