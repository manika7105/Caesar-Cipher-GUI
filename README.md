# Caesar-Cipher-GUI
Encrypt and decrypt messages with a custom cipher algorithm. Includes a user-friendly GUI built with Tkinter.

# Encryption/Decryption Tool

This is a Python-based application that allows users to encrypt and decrypt text messages. It uses a custom cipher algorithm (similar to a Vigenère cipher but with modifications) for encryption and decryption. The application provides a graphical user interface (GUI) built with Tkinter for ease of use.

## Features

*   Encrypts text messages using a key.
*   Decrypts encrypted messages using the same key.
*   User-friendly graphical interface.
*   Supports basic text input and output.
*   Includes a reset button to clear all fields.
*   Includes an exit button to close the application.

## How to Use

1.  **Clone the repository:**
    git clone https://github.com/manika7105/Caesar-Cipher-GUI.git

2.  **Run the application:**
    python Encrypt-Decrypt.py

3.  **Enter your message:** Type the text you want to encrypt or decrypt into the "Enter the Message" field.

4.  **Enter your key:** Type the secret key you want to use into the "Enter the key" field.  *Keep this key secure!*

5.  **Choose mode:** Select either "Encrypt" or "Decrypt" using the radio buttons.

6.  **Show Message:** Click the "Show Message" button. The encrypted or decrypted message will appear in the "Result" field.

7.  **Reset:** Click the "Reset" button to clear all fields.

8.  **Exit:** Click the "Exit" button to close the application.

## Algorithm

The encryption algorithm used is a custom cipher that combines elements of a Vigenère cipher and Base64 encoding.  It's important to note that this is *not* a cryptographically secure cipher and is primarily for educational or demonstration purposes.  Do not use it for sensitive data.

## Technologies Used

*   Python 3
*   Tkinter (for the GUI)
*   base64 (for encoding)

## Future Improvements

*   Implement stronger encryption algorithms (e.g., AES, RSA).
*   Add file encryption/decryption capabilities.
*   Improve error handling and input validation.
*   Potentially add more advanced GUI features (e.g., copy/paste, clear text).

## Author

Manika Goel - https://github.com/manika7105
