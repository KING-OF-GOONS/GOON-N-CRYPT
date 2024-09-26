# GOON-N-CRYPT
AES ENCRYPTION PROGRAM
GOON-N-CRYPT - Self-Destructing Encryption Tool
This is the code for GOON-N-CRYPT, a web-based tool for encrypting and decrypting messages with a self-destruct mechanism.

Features:

Encrypts messages using AES encryption with a user-provided passkey.
Decrypts previously encrypted messages with the same passkey.
Allows self-destructing encrypted messages, rendering them unreadable after decryption.
Features a Matrix rain background effect for a cool aesthetic.
Requirements:

A web browser with JavaScript enabled.
The CryptoJS library for encryption/decryption (included in the code).
Functionality:

Enter the message you want to encrypt/decrypt in the "Message to Encrypt/Decrypt" text area.
Enter your desired passkey in the "Passkey" field.
Click "ENCRYPT" to encrypt the message or "DECRYPT" to decrypt an existing encrypted message.
The encrypted/decrypted message will appear in the "Encrypted/Decrypted Message" text area.
Clicking "SELF DESTRUCT" will mark the current message-passkey combination as destroyed, making the encrypted message unreadable even if the passkey is known.
Security:

This tool uses AES encryption, a strong encryption standard. However, the security of the encrypted messages ultimately depends on the strength of the chosen passkey.
Important: The self-destruct functionality relies on client-side JavaScript code and may not be completely secure in all scenarios.
Disclaimer:

This tool is for educational purposes only. Use it responsibly and be aware of the limitations of client-side encryption.
