


# CryptoChatSecure 
![GitHub](https://img.shields.io/badge/license_-PrashantChapagain-red)

**The PKI-powered fortress for encrypted messaging**

Welcome to **CryptoChatSecure**, where your conversations aren't just private — they're **armored with cryptography**. This isn't your average chat app. It’s a **battle-hardened communication system** built with Public Key Infrastructure (PKI), digital certificates, AES encryption, and RSA signatures.  

Whether you're guarding trade secrets or just flexing your cryptographic muscles — this is your domain.


---
Here is a **clean, professional project structure section** you can paste directly into the **README.md** for the **Secure PKI Chat** repository.
It is written in a GitHub friendly format and suitable for cybersecurity or academic submissions.

---

##  Project Structure

```bash
Secure-PKI-Chat/
│
├── main.py                    # Application entry point
│
├── crypto/                     # Cryptographic operations
│   ├── key_manager.py          # RSA key generation and storage
│   ├── encryptor.py            # Message encryption and decryption
│   ├── signer.py               # Digital signature creation and verification
│   └── certificate.py          # Self-signed certificate handling
│
├── pki/                        # Public Key Infrastructure components
│   ├── ca.py                   # Certificate Authority logic
│   ├── trust_store.py          # Trusted certificate management
│   └── validation.py           # Certificate validation and revocation checks
│
├── server/                     # Backend server logic
│   ├── server.py               # Secure socket server
│   ├── auth.py                 # User authentication using PKI
│   └── session.py              # Secure session handling
│
├── client/                     # Client-side logic
│   ├── client.py               # Secure client connection
│   ├── chat.py                 # Encrypted messaging logic
│   └── ui.py                   # Client-side interface handler
│
├── templates/                  # HTML templates (if using web UI)
│   └── index.html              # Main application interface
│
├── static/                     # Static assets
│   ├── css/                    # Stylesheets
│   ├── js/                     # Frontend scripts
│   └── images/                 # Icons and UI images
│
├── keys/                       # Cryptographic keys (excluded from Git)
│   ├── private/                # Private keys
│   └── public/                 # Public keys and certificates
│
├── logs/                       # Application and security logs
│   └── security.log            # Authentication and message logs
│
├── tests/                      # Unit and integration tests
│   ├── test_crypto.py          # Cryptography tests
│   ├── test_pki.py             # PKI validation tests
│   └── test_chat.py            # Secure chat tests
│
├── requirements.txt            # Python dependencies
├── README.md                   # Project documentation
├── LICENSE                     # License information
└── .gitignore                  # Git ignored files
```

---
##  Quick Start — Deploy the Shield

###  Clone the Arsenal
```bash
git clone https://github.com/Prashant-chaps/Secure-PKI-Chat.git
cd Secure-PKI-Chat
````

###  Launch the Encrypted Arena

Make sure Docker is installed:

```bash
sudo apt install docker.io
```

Then:

```bash
sudo docker-compose up --build
```

---

##  Engage in Secure Communication

Open your browser and march to:
`http://localhost:5000`

1. **Register** with a username and role.
2. **Download your private key**.
3. **Enter the secure zone** and start chatting — encrypted and signed.

---

## Features That Fortify You

* **PKI Authentication**
  Generate RSA key pairs and x.509 certificates to prove your identity like a true digital knight.

* **End-to-End Encrypted Messaging**
  AES & RSA ensure every whisper stays between allies — even file transfers.

* **Digital Signatures**
  Sign each message and file. No fakes. No fraud. Just verifiable truth.

* **Dockerized**
  One command launch. Anywhere. Anytime.

---

##  Why CryptoChatSecure?

Because privacy isn't a privilege — it’s a right.
Use it for:

*  Confidential team discussions
* Secure legal or business exchanges
*  Learning the real-world power of cryptography

**It's not just code. It’s a castle.**

---

##  Tech Stack

| Tech            | Role                            |
| --------------- | ------------------------------- |
| 🐍 Python       | Core engine with Flask magic    |
| 🔑 Cryptography | RSA, AES, and PKI mechanisms    |
| 🐳 Docker       | Smooth, isolated deployment     |
| 🧱 SQLite       | Lightweight battlefield tracker |

---

##  Want to Contribute?

Feel the fire? Fork the project, build your improvements, and send a pull request!
Let’s craft the most secure chat system out there — **together**.

---

##  Security Reminder

>  **Your private key is your soul** — guard it with your life.
> This app uses a simulated CA — never use test keys in production without replacing them with a secure CA setup.

---

## Credits & Legacy
**Forged with passion on December 20, 2025.**
Keep the crypto flame alive. 



