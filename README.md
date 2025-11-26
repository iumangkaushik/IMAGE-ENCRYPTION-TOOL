# 🔐 Image Encryption Utility (Python)
This project offers a lightweight utility for securing image files through symmetric encryption using the cryptography package.

---

# 📦 Highlights

- Utilizes Fernet, which internally uses AES symmetric encryption.

- Automatically generates and stores a secure key.

- Supports encryption and decryption for any binary data (including images).

- Clean and minimal command-line interface.

---

# image-encryption/
│
├── encryptor.py          # Core program containing the menu system and encryption/decryption functions
├── secret.key            # Auto-created encryption key stored securely
├── sample_image.jpg      # (Optional) Test image
├── sample_image.jpg.enc  # Encrypted output of the sample image
├── decrypted_image.jpg   # Resulting file after decryption
├── requirements.txt      # Needed Python packages
└── README.md             # Project overview and usage guide

---
