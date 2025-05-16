# 🔐 CRYPTXFER

**CRYPTXFER** is a secure, self-hosted file transfer and storage application. It encrypts files locally in the browser using AES-GCM and protects them with a user-defined passphrase. Only someone with the correct passphrase can decrypt the file, ensuring privacy and control over your data.

---

## 🌐 Use Cases

CRYPTXFER is ideal for:

- 🗄️ **Personal Cloud Storage**: Encrypt files before uploading to cloud services.
- 🔗 **Secure File Sharing**: Share sensitive documents with trusted contacts.
- 🔐 **Local Password Vault**: Save credentials or private notes in encrypted files.
- 💾 **Backup Solution**: Secure your backups with strong encryption.
- 🧾 **Confidential Business Data**: Protect financial records, legal files, etc.
- 🩺 **Medical Files**: Help maintain HIPAA compliance with patient record encryption.
- 📚 **Academic Research**: Safeguard unpublished findings when collaborating.

---

## ✅ Benefits

- **🔒 End-to-End Encryption**: Files are encrypted on your device before upload.
- **🛡️ Enhanced Privacy**: Even if storage is compromised, your files remain unreadable.
- **🧩 No Vendor Lock-in**: Use and store encrypted files anywhere you like.
- **🧠 Open Source & Auditable**: Transparent and modifiable.
- **📱 Cross-Platform**: Works on any modern browser.
- **🧭 Intuitive UI**: Designed for users of all technical levels.
- **🖼️ Content-Agnostic**: Encrypt any file format — from PDFs to media files.
- **🚫 No Accounts Needed**: Use instantly without registration.

---

## 🔧 Features

- **AES-GCM Encryption** – Modern, secure, and authenticated file encryption.
- **Passphrase Protected** – Files are tied to your passphrase, not your identity.
- **Web Interface** – Simple upload/download with drag-and-drop support.
- **Music Player** – Built-in player for audio files (MP3, WAV, etc.).
- **Privacy First** – No passphrase or unencrypted data is ever stored.

---

## 🛠️ Tech Stack

| Layer       | Technology            |
|-------------|------------------------|
| **Frontend** | HTML, CSS, JavaScript |
| **Backend**  | Python (Flask)        |
| **Encryption** | PyCryptodome (AES-GCM) |

---

## 📥 Installation

```bash
# Clone the repository
git clone https://github.com/Vishwas-Chaudhary/CRYPTXFER.git
cd CRYPTXFER

# Install dependencies
pip install -r requirements.txt

# Run the app
python app.py
