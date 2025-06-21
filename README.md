# 🔐 Hill Cipher with Matrix Inversion $(n×n)$ using Printable ASCII

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

---

## 📂 How to Use

1.  **For Cloud Computing (Google Colab):**
    Simply click on the `computation.ipynb` file within the repository (or navigate to it directly [here](https://github.com/depichan18/secure-hill-cipher-nxn/blob/main/computation.ipynb)) and run it directly in Google Colab.

2.  **For Local Computer:**
    
    a.  **Clone the Repository:**
        Open your terminal or command prompt and run the following command to get a copy of the project:
    
        ```bash
    
         git clone [https://github.com/depichan18/secure-hill-cipher-nxn.git]
        ```
    
    b.  **Run the Script:**
        Navigate into the newly cloned directory:
    
        ```bash
    
        cd secure-hill-cipher-nxn
        ```
    
        Then, execute the main Python script:
        ```bash
    
        python computation.py
        ```

---

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
