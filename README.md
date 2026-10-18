# Encrypted document viewer

This repository contains a password entry page and an encrypted document payload. The document is decrypted locally in the visitor's browser. No plaintext document, password, or encryption key is stored in this repository.

Encryption: AES-256-GCM; password derivation: PBKDF2-HMAC-SHA-256 with a random salt and 600,000 iterations. A unique randomly generated sharing password is distributed separately by the document owner.

The repository and the entry page are public. Anyone who receives the password can open the document; access is not bound to a named account.
