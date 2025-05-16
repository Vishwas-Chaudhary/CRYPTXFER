# 🔐 CRYPTXFER – Secure, Private & Encrypted File Sharing

![CRYPTXFER Demo](https://your-demo-gif-link-here.gif) <!-- Replace with actual GIF URL -->

**CRYPTXFER** is a lightweight and privacy-first file encryption and sharing tool built for individuals who value **data control**, **security**, and **simplicity**. Whether you're transferring sensitive documents, personal media, or project files — CRYPTXFER ensures they stay **encrypted**, **private**, and **only accessible with your passphrase**.

---

## ✅ Features

- 🔐 **AES encryption**: Military-grade symmetric encryption with integrity checks
- 🔑 **Passphrase protected**: Only the correct phrase can decrypt your files
- 🌐 **Web-based interface**: Upload, download, and decrypt via browser
- 🎧 **Music streaming**: Stream encrypted music files securely
- 🧩 **Universal file support**: Upload and encrypt any file type
- 💻 **Self-hosted**: Run locally, no dependency on third-party cloud
- 🧠 **Stateless design**: Passphrases and keys never leave your machine

---

## 🧠 How It Works

- Files are encrypted using **AES** before upload.
- Encrypted files are stored in the `encrypted_files/` directory.
- Users must enter the same passphrase to decrypt and access the files.
- The app can directly stream audio from encrypted `.mp3` files.

---

## 🛠️ Tech Stack

| Layer      | Technology                |
|------------|---------------------------|
| Backend    | Python, Flask             |
| Encryption | PyCryptodome (AES)        |
| Frontend   | HTML, CSS, Vanilla JS     |

---

## 📁 Project Structure

CRYPTXFER/
├── app.py # Flask app entry point (routes and server logic)
├── encryption.py # AES encryption/decryption functions
├── requirements.txt # Python dependencies
├── encrypted_files/ # Directory to store encrypted files
├── static/
│ ├── css/ # Custom styling (optional)
│ ├── js/ # Frontend JavaScript logic
│ └── music/ # (Optional) For serving encrypted music streams
└── templates/
└── index.html # Main HTML page served by Flask
---

## ⚙️ Getting Started

```bash
# Clone the repository
git clone https://github.com/Vishwas-Chaudhary/CRYPTXFER.git
cd CRYPTXFER

# Install dependencies
pip install -r requirements.txt

# Run the app
python app.py
