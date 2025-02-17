# Machine Encryption/Decryption

This simple Python script implements a basic encryption and decryption algorithm using a Caesar cipher. It allows you to encrypt or decrypt a message using a predefined key.

## Usage

1. Run the script using Python.
2. Enter your secret message when prompted.
3. Choose the mode:
   - Enter `E` to encode (encrypt) the message.
   - Enter `D` to decode (decrypt) the message.
4. The script will output the encrypted or decrypted message.

## Implementation

The script defines a function `machine()` which performs the encryption or decryption based on the chosen mode. It utilizes a Caesar cipher with a fixed key to encode and decode messages.

## Example

```python
python machine.py
```

```bash
Please enter your secret message: Hello, World!
Please enter the mode : Encode(E) or Decode(D) :E
```

```bash
Jgnnq, Xqmdr!
```

## Note

This script is for educational purposes and should not be used for sensitive data encryption as it employs a simple and easily breakable encryption method.