# Folder-Encryption-and-Decryption-Project
# Folder Encryption and Decryption Project

## Introduction

This project focuses on encryption and decryption of folders using the Advanced Encryption Standard (AES) algorithm, with implementation using Python's `cryptography` package and the `Fernet` module for file encryption. The project ensures folder protection by encrypting data, providing a layer of security to prevent unauthorized access in the event of physical device theft.

The folder encryption scrambles data into ciphertext, which can only be decoded with the decryption key. This technique guarantees data privacy and integrity, contributing to a safer environment for storing sensitive information.

## Technologies Used
- **Programming Language**: Python
- **Encryption Algorithm**: AES via `Fernet`
- **Python Libraries**: `cryptography`, `tkinter` (for GUI), `smtplib` (for sending emails)
- **Operating Systems Supported**: Windows, Linux

## Features
- **Folder Encryption**: Encrypt the contents of a folder to prevent unauthorized access.
- **Folder Decryption**: Restore the contents of an encrypted folder to its original state.
- **Key Generation**: Secure and unique encryption keys are generated for each folder.
- **Batch Encryption**: Allows batch encryption of multiple files within a folder.
- **GUI Support**: Simple graphical user interface for encrypting and decrypting folders.

## Requirements
To run this project, the following software and libraries are required:
- **Python IDE** (e.g., PyCharm, VSCode)
- **Python Libraries**:
  - `cryptography`
  - `tkinter` (for GUI development)
  - `smtplib` (for email notifications)

You can install the required libraries using pip:
```bash
pip install cryptography
pip install tk
```

## Learnings
During this project, the focus was on implementing secure cryptographic techniques to protect sensitive data through folder encryption. The project also provided exposure to:
- **Symmetric Key Encryption**: Using `Fernet`, a symmetric encryption algorithm, we ensure strong privacy and authenticity guarantees.
- **GUI Design**: Built a user-friendly interface using `tkinter` to facilitate ease of use.
- **Batch Processing**: Efficiently handled large-scale folder encryption and decryption.
- **Email Notifications**: Integrated email functionality to notify users of successful operations.

## Conclusion
This project demonstrates the importance of encryption and how it can be applied to secure sensitive data on local systems. By implementing folder encryption, users can ensure that their data remains unreadable without the proper decryption key, protecting against unauthorized access and theft.
