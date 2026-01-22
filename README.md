# 🖼️ Image Encryption & Decryption Tool (Python)

A Python-based **Image Encryption and Decryption** application built for learning and demonstration purposes.
The project uses a **simple XOR-based encryption algorithm** and provides a **user-friendly GUI** developed with **Tkinter**.

This tool demonstrates the fundamentals of **file-level encryption**, **byte manipulation**, and **basic cryptographic concepts** in a clear and interactive way.

---

## 🚀 Features

* 🔐 **Image Encryption**
  Encrypt JPG images using a user-defined numeric key.

* 🔓 **Image Decryption**
  Decrypt encrypted images using the same key applied during encryption.

* 🖥️ **Graphical User Interface (GUI)**
  Clean and intuitive interface built with Tkinter.

* 🧪 **Educational Focus**
  Designed to help understand how XOR-based encryption works at the byte level.

---

## ⚙️ How It Works

### 🔑 Encryption

* The selected image is read as a **byte array**
* Each byte is XORed with the provided integer key
* The resulting output is saved as an encrypted image file

### 🔁 Decryption

* The encrypted image is processed using the **same key**
* Applying XOR again reverses the operation
* The original image is restored

> ⚠️ **Note:**
> XOR encryption is used here **for learning purposes only** and should **not** be considered secure for real-world applications.

---

## 🧰 Requirements

* Python 3.x
* Tkinter (comes pre-installed with most Python distributions)
* Pillow (PIL)

---

## 📦 Installation

Clone the repository:

```bash
git clone https://github.com/farixzz/image-encryption-decryption.git
cd image-encryption-decryption
```

Install dependencies:

```bash
pip install -r requirements.txt
```

Or install manually:

```bash
pip install Pillow
```

---

## ▶️ Usage

Run the application:

```bash
python image_encryption_decryption.py
```

### Using the GUI:

1. Click **Choose Image** to select a JPG file
2. Enter an **integer key** in the input field
3. Click **Encrypt** to encrypt the image
4. Click **Decrypt** to restore the original image

Encrypted and decrypted images can be saved to your preferred location.

---

## 📁 Project Structure

```
image-encryption-decryption/
│
├── image_encryption_decryption.py   # Main application script
├── requirements.txt                 # Project dependencies
└── README.md                        # Project documentation
```

---

## 🛡️ Use Case

* Learning **basic cryptography concepts**
* Understanding **byte-level file manipulation**
* Academic demonstrations
* Cybersecurity & Python practice projects

---

## 📜 License

This project is licensed under the **MIT License**.
See the `LICENSE` file for more details.

---

⭐ If you find this project useful, consider starring the repository!
