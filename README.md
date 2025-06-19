# 🔐 Hill Cipher with Matrix Inversion (n×n) using Printable ASCII

This project implements the **Hill Cipher encryption and decryption algorithm** using **customizable $n \times n$ matrices** (where $n$ ranges from 2 to 7) and supports **printable ASCII characters** under **modulo 97** arithmetic.

## 🚀 Features

- Encrypt and decrypt text using the Hill Cipher.
- Supports matrix sizes from **2×2 up to 7×7**.
- Works with **printable ASCII characters (mod 97)** for compatibility and readability.
- Input text manually or upload `.txt` files for batch processing.
- Automatically pads plaintext to match block size.
- Ensures key matrix is invertible (mod 97) before use.

## 📚 Concept Overview

- Based on **linear algebra**, particularly matrix multiplication and modular inversion.
- The project highlights the **crucial role of matrix inversion** in the decryption process.
- Designed to show how mathematical concepts like **modular arithmetic** and **determinants** are applied in cryptography.

## 🧠 Educational Value

This project is ideal for students learning about:
- Linear algebra applications in computer science,
- Modular arithmetic,
- Classical ciphers and cryptographic foundations.

## 📂 How to Use

1. Clone this repository.
2. Run the Python script (Colab or local environment).
3. Choose matrix size (n), input mode (text or file), and key matrix.
4. View the encrypted or decrypted result.

## 🛠 Technologies Used

- Python
- `sympy` for matrix operations
- ASCII character manipulation

## 📈 Future Improvements

- Add GUI for user interaction.
- Support Unicode and multilingual encryption.
- Implement standard padding schemes (e.g., PKCS).

---

*Developed as part of a cryptography learning project focused on applying matrix theory in practical computing.*
