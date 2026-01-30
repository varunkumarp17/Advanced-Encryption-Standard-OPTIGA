# AES Encryption & Decryption using mbedTLS on PSoC (ModusToolbox)

This project demonstrates **AES-128 encryption and decryption (ECB mode)** using the **mbedTLS library** on a **PSoC OPTIGA IoT Kit** with **ModusToolbox**.

The application:
- Initializes the board and UART
- Encrypts a 16-byte plaintext using AES-128
- Decrypts the ciphertext back to plaintext
- Prints plaintext, ciphertext, and decrypted output to the UART console

---

## 🛠️ Hardware & Software Requirements

### Hardware
- PSoC™ OPTIGA™ IoT Kit (or compatible PSoC board)
- USB cable for programming and UART debug

### Software
- ModusToolbox™ (3.x or later)
- GNU ARM toolchain (installed via ModusToolbox)
- Serial terminal (PuTTY, Tera Term, Minicom, etc.)

---
