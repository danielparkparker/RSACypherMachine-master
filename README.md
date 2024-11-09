# RSACypherMachine-master
project

# RSA Cipher Machine

The RSA Cipher Machine is a project created to demonstrate how RSA encryption works using Python. RSA encryption is a type of cryptography that keeps messages safe using prime numbers and special mathematical techniques.

## Project Structure

- **lib/mathRSA.py** - Contains the math needed to create RSA keys and manage encryption.
- **lib/stringRSA.py** - Encrypts and decrypts text using the RSA algorithm.
- **lib/enigma.py** - The main interactive program where you can input commands to use the RSA Cipher Machine.
- **primes/primeGen.py** - A generator to create large prime numbers for the encryption process.
- **helpMenu.txt** - A text file that lists available commands and basic usage instructions.

## Requirements
- **Python 3** must be installed on your system.

## How to Use
1. Open a terminal or command prompt on your computer.
2. Navigate to the `lib` directory of the RSA Cipher Machine project.
3. Run the following command to start the RSA Cipher Machine:
   ```
   python3 enigma.py
   ```
4. Once the program starts, you can use commands to encrypt or decrypt messages.

## Commands
To get a list of available commands and how to use them, type:
```
help
```
in the interactive shell after starting `enigma.py`.

## Example
After starting `enigma.py`, you might type something like this:
```
encrypt "Hello, world!"
decrypt "EncryptedMessage"
```

## Notes
- **Public and Private Keys**: In RSA, a public key is used to encrypt a message, and only the corresponding private key can decrypt it.
- **Prime Generation**: RSA uses large prime numbers, which this project generates with the `primeGen.py` script.

Happy encrypting!
