# Custom Feistel
## Feistel Cipher Implementation

This repository contains a Python implementation of a simple Feistel cipher. The code takes a plaintext message as input, encrypts it using a Feistel cipher with two rounds, and then decrypts the ciphertext to recover the original plaintext.

### Key Features

* **Random Key Generation:** The code generates random keys for each round of the Feistel cipher using the `rand_key()` function.
* **Feistel Function:** The `f()` function implements the Feistel function, which takes two binary strings as input and returns their XOR.
* **Binary to Decimal Conversion:** The `BinaryToDecimal()` function converts a binary string to its decimal equivalent.
* **Encryption and Decryption:** The code implements the encryption and decryption processes, performing two rounds of Feistel operations.

### Usage

1. **Input Plaintext:** Enter the plaintext message you want to encrypt when prompted.
2. **Encryption:** The code will encrypt the plaintext and print the resulting ciphertext.
3. **Decryption:** The code will then decrypt the ciphertext and print the recovered plaintext.

### Example

```
Plain Text: Hello World
Cipher Text:  |@]jS{c43$
Decrypt of Cipher Text is:  b'Hello World'
```

### Notes

* The code uses a simple Feistel cipher with two rounds. 
* The keys are generated randomly and are not stored or reused.
* The code assumes that the plaintext is in ASCII format.
* The decryption process uses the same keys as the encryption process.

### Future Improvements

* Implement a more complex Feistel function.
* Use a more secure key generation method.
* Implement a key management system.
* Add support for different character encodings.

This implementation provides a basic understanding of the Feistel cipher and its application in cryptography.

---

**This is a well-structured Markdown README with clear headings, subheadings, and code examples. It provides a concise and informative overview of the project, its features, usage, and potential improvements. You can further enhance it by adding screenshots, diagrams, or a more detailed explanation of the code logic.**
