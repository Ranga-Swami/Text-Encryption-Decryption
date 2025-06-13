# **Image Encryption & Decryption**
---

### 🔐 **Caesar Cipher GUI Application Overview**

This code is a graphical user interface (GUI) implementation of a **Caesar Cipher**, a type of substitution cipher where each letter in the plaintext is **shifted** a certain number of positions down the alphabet. The GUI is built using the **Tkinter** library in Python.

---

### 🧠 **Class: CaesarCipher**

This class represents the Caesar Cipher algorithm and contains two main methods: `encrypt` and `decrypt`.

* 🛠️ **`__init__` Method**:
  Initializes the cipher with a **shift value**, which determines how many positions each letter should be shifted.

* 🔒 **`encrypt` Method**:
  Takes a message as input and returns the encrypted version. It loops through each character, and if it's a letter, shifts it using ASCII values.

* 🔓 **`decrypt` Method**:
  Similar to `encrypt`, but shifts characters in the **opposite direction** to restore the original message.

---

### 🖥️ **Class: GUI**

This class handles the graphical interface and user interaction of the application.

* 🛠️ **`__init__` Method**:
  Sets up the GUI components like labels, input boxes, and buttons.

* 🔒 **`encrypt` Method**:
  Triggered when the "Encrypt" button is clicked. It:

  * Gets user input
  * Creates a `CaesarCipher` object
  * Encrypts the message
  * Displays the result

* 🔓 **`decrypt` Method**:
  Works similarly to the encrypt method but performs **decryption** instead.

---

### 🚀 **Main Application**

* A **Tkinter window** is created.
* An instance of the `GUI` class is initialized.
* The GUI **event loop** is started with `root.mainloop()`.

---

### 📋 **How to Use**

1. ▶️ **Run** the code to launch the GUI.
2. 📝 **Enter a message** in the "Enter a message:" text box.
3. 🔢 **Enter a shift value** in the "Enter a shift value:" text box.
4. 🔒 **Click "Encrypt"** to encrypt the message.
5. 📄 **View the result** in the "Result:" text box.
6. 🔓 **Click "Decrypt"** to decrypt the message back.

---

### ⚠️ **Note**

* ✅ Works with **alphabetic characters** only.
* 🔠 **Preserves case** (uppercase/lowercase).
* 🚫 **Non-alphabetic characters** (spaces, punctuation) remain unchanged.

