🔐 AES Text File Encryptor

A simple and secure text file encryption tool built with Python, using AES-256 symmetric encryption via the cryptography library.
It allows you to encrypt and decrypt .txt files from the command line using a shared secret password.

This project is intended for educational purposes and basic private communication.

🚀 Features

AES-256 encryption (industry-standard)

Password-based key generation (SHA-256)

Encrypt and decrypt text files

Works from the command line

Simple, clean, and easy to understand

Same program for sender and receiver

🛠 Requirements

Python 3.8 or higher

cryptography library

Install the dependency with:

pip install cryptography

📂 Usage

Clone the repository or download the script.

Place the text file you want to encrypt in the same directory.

Run the program:

python encryptor.py


Choose an option:

1 → Encrypt file

2 → Decrypt file

Enter:

Input file name

Output file name

Secret password

⚠️ Important:
The same password must be used to decrypt the file.
If the password is incorrect, the file cannot be recovered.

🔐 Security Notes

Uses AES-256, a secure and widely used encryption standard.

The password is never stored.

Encrypted files are unreadable without the correct password.

Do not share the password in the same channel as the encrypted file.

📘 Example Use Case

Send encrypted messages through email or messaging apps.

Protect sensitive notes or personal data.

Learn the basics of real cryptography in Python.

⚠️ Disclaimer

This project is for educational purposes.
While it uses strong encryption, it is not intended to replace professional security tools.
