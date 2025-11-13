# Python-projects
All the project made for practicing python basics and revision and doing some fun in python.
# Caesar Cipher Encoder/Decoder

A simple Python script that implements the classic Caesar cipher for encrypting and decrypting messages.

## Features

*   **Encode Text**: Encrypts a given message by shifting each letter by a specified amount.
*   **Decode Text**: Decrypts an encrypted message back to its original form.
*   **Handles Non-Alphabetic Characters**: Non-alphabetic characters (numbers, symbols, spaces) are preserved as-is.
*   **Interactive Loop**: Allows for multiple encode/decode operations without restarting the script.

## How to Use

1.  **Run the script**: Execute the Python script.
2.  **Choose Direction**: When prompted, type `encode` to encrypt a message or `decode` to decrypt.
3.  **Enter Message**: Type the message you wish to process.
4.  **Enter Shift Number**: Provide an integer for the shift amount. This determines how many positions each letter will be shifted.
5.  **Continue or Exit**: After a message is processed, you will be asked if you want to perform another operation. Type `yes` to continue or `no` to exit.

### Example Interaction

```
Type 'encode' to encrypt, type 'decode' to decrypt:
encode
Type your message:
hello world
Type the shift number:
5
The encoded text is mjqqt btwqi
Type 'yes' if you want to go again. Otherwise type 'no'.
yes
Type 'encode' to encrypt, type 'decode' to decrypt:
decode
Type your message:
mjqqt btwqi
Type the shift number:
5
The decoded text is hello world
Type 'yes' if you want to go again. Otherwise type 'no'.
no
Goodbye
```

## Technologies Used

*   Python 3
