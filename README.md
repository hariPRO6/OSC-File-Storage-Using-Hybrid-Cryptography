# 🚀 Secure Safe - Encrypted File Storage System

## 📚 Table of Contents
- [Overview](#overview)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## 🔍 Overview
**Secure Safe** is a web-based application designed for secure file storage and transfer. It employs advanced cryptographic techniques to ensure the confidentiality and integrity of user data. By utilizing a hybrid encryption approach, Secure Safe allows users to upload, store, and download files securely.

## ✨ Features
- 🔒 **Hybrid Cryptography**: Combines symmetric and asymmetric encryption methods for enhanced security.
- 🛡️ **Multi-Layered Encryption**: Files are segmented and encrypted using different algorithms (e.g., AES, ChaCha20).
- 🔑 **Secure Key Management**: Unique keys are generated and securely stored for each file segment.
- 🌐 **User -Friendly Interface**: Simple and intuitive design for easy file upload and download.
- ✅ **Data Integrity**: Ensures that files remain unchanged during transfer.

## 🛠️ Technologies Used
- **Backend**: Python, Flask
- **Frontend**: React, HTML5, CSS3, JavaScript
- **Cryptography**: Cryptography Library (e.g., PyCryptodome)
- **Database**: SQLite (or any other database of your choice)

## 📥 Installation
To set up the Secure Safe project locally, follow these steps:

1. **Clone the repository**:
   ```bash
   git clone https://github.com/yourusername/secure-safe.git
   cd secure-safe  
2. **Set up a virtual environment (optional but recommended):**
    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows use `venv\Scripts\activate`
3. **Install the required packages:**
    ```bash
    pip install -r requirements.txt
4. **Run the application:**
    ```bash
    python app.py
