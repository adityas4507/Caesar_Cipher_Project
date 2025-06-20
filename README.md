# Caesar_Cipher_Project
A beginner-friendly Python project that implements the Caesar Cipher to encrypt and decrypt messages. Includes a looping user interface, input validation, shift wrapping, and fun ASCII art. Great for learning string manipulation, loops, and cipher logic.

# 🔐 Caesar Cipher Project

This is a beginner-friendly Python program that implements the **Caesar Cipher** — a classic encryption technique. The user can choose to **encode** (encrypt) or **decode** (decrypt) a message with a custom shift value. The program also includes a loop to keep running until the user decides to stop.

---

## 🎯 Features

- Encrypt or decrypt any message using Caesar Cipher
- Handles uppercase, lowercase, and non-alphabet characters
- Automatically wraps shift values (e.g., shift > 26)
- ASCII art banner and playful UI
- Built-in input validation and restart option

---

## 🧠 How the Caesar Cipher Works

The Caesar Cipher shifts each letter in the message by a certain number of positions in the alphabet. For example, with a shift of `3`:
- a → d
- b → e
- z → c

Decryption is simply shifting the other way.

---

## 🚀 How to Run

1. Make sure you have **Python 3.x** installed.
2. Download or clone this repository.
3. Run the script.

---

## 💡Example for encode:

![image](https://github.com/user-attachments/assets/41a799b1-220d-4581-887e-61474648a5e6)

## 💡Example for decode:

![image](https://github.com/user-attachments/assets/f75b9937-96ed-4e48-adb6-1bb20416612b)

---

## 🛠 Code Highlights

- shift_amount %= len(alphabet) ensures wrapping beyond z. 
- Preserves spaces and punctuation. 
- Loop allows user to encode/decode multiple times. 

---

## 📚 Concepts Used:

- String manipulation
- Loops and conditionals
- List indexing
- Function design
- Modular arithmetic
