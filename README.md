# Caesar Cipher in Go

This is a simple Go program that implements a Caesar cipher (letter rotation encryption). It allows you to encrypt and decrypt messages using a specified shift key.

## Features

- Encrypts a plain text string by shifting letters in the alphabet.
- Decrypts the encrypted string back to the original text.
- Demonstrates string manipulation using Go's standard library.

## How It Works

- The `encrypt` function shifts each letter in the input text based on a generated cipher alphabet.
- The `decrypt` function reverses the process using the same shift key.
- Only uppercase English letters (A–Z) are handled.

## Example

```bash
Plain Text: HELLOWORLD
Encrypted : WORLDHELLO
Decrypted : HELLOWORLD
Getting Started
Prerequisites
Go 1.18 or higher

Running the Program
bash
Copy
Edit
go run main.go
Code Overview
hashLetterFn: Generates a shifted alphabet used for encryption/decryption.

encrypt: Converts plain text to cipher text.

decrypt: Reverses the encryption process.

main: Example usage with hardcoded inputs.

Customization
You can change the plainText and key in the main() function to try different inputs and shifts.

License
This project is licensed under the MIT License.

yaml
Copy
Edit

---

Would you like to include test cases or example usage with command-line input next?
