Markdown# TH - Text File Encryptor/Decryptor (v1.0)

A simple, console-based tool to **encrypt** and **decrypt** text files (`.txt`) using strong **AES-256-GCM** authentication encryption, with key derivation via **PBKDF2-HMAC-SHA256**.

Perfect for protecting sensitive text files locally on Windows.

## Features

- Strong encryption: AES-256-GCM (authenticated encryption)
- Secure key derivation: PBKDF2 with 200,000 iterations and random salt
- Interactive mode with graphical file picker (via Tkinter)
- Command-line mode for scripting/automation
- Optional saved master password (stored in plain text in a local `credenciales.json` file – **use only on trusted machines**)
- Automatic copy of the output file to the Desktop
- Colored console output (cross-compatible with Windows thanks to Colorama fallback)
- Supports both encryption (`.txt` → `.enc`) and decryption (`.enc` → `.dec.txt`)

## Requirements

- Python 3.7+
- Required packages:
  - `cryptography`
  - `colorama` (optional – for colored output; falls back gracefully if missing)

Install dependencies with:

```bash
pip install cryptography colorama
