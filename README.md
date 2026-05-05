# ENIGMA
ENIGMA is a secure messaging system developed as a semester project. It implements multiple classical encryption techniques with support for layered encryption to enhance message security. The system also manages encryption keys dynamically and supports secure file storage for encrypted data. There are 2 roles, a user and an admin, admin can add new organizations to the system, that can use the system.

## Features
- User and Admin Role
- Admin can easily add new organizations
- Multiple encryption methods:
-- Caesar Cipher
-- Reverse Cipher
- Multi-layer encryption and decryption support
- Secure key management using data structures
- File handling for storing encrypted messages and keys
- User-based system for sending encrypted messages
---

## Technologies Used
- C++
- Data Structures:
- Stack (for reversing / layered encryption)
- Queue (for Caesar cipher processing)
- Linked List (for dynamic key management)
- File Handling
---

## How It Works
- User inputs a message
- Inputs encryption key
- System applies layered encryption
- Encrypted message is saved to file
- Decryption retrieves original message using stored keys
---

## Learning Outcomes
- Practical use of data structures in real applications
- Understanding of classical encryption techniques
- File handling and data persistence in C++

---

## Future Improvements
- Add modern encryption algorithms (AES, RSA)
- GUI-based interface
- User authentication system
- Network-based secure messaging
