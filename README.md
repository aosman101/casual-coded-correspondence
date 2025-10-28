# Casual Coded Correspondence

A hands-on cryptography notebook where you **decode and encode messages** using the **Caesar** and **Vigenère** ciphers. Includes a brute-force Caesar solver and punctuation/spacing preservation so examples stay readable.

> Built as a single Jupyter Notebook for easy, copy-pasteable experimentation.

---

## ✨ What’s inside

- **Caesar cipher tools**
  - Decode/encode with a chosen shift (0–25).
  - Try-all-shifts **brute-force** helper to solve unknown shifts.
- **Vigenère cipher tools**
  - Encode/decode using a repeating keyword.
- **Friendly UX**
  - Keeps spaces and punctuation intact.
  - Clear, step-by-step cells you can run top-to-bottom.

> The Caesar cipher shifts each letter by a fixed offset, using modulo 26. This method is a classic example of monoalphabetic substitution. In contrast, the Vigenère cipher employs a series of Caesar shifts based on a keyword that is repeated throughout the text. This represents a simple form of polyalphabetic substitution.

---

## 🚀 Project structure

├─ coded_correspondence.ipynb   # This notebook contains all the tasks and helpers.

└─ README.md.
