# Conversion-Table-Cipher

## Overview
This repository contains a **table-based substitution cipher implemented in C++**, designed for educational purposes. The project demonstrates how characters can be encrypted and decrypted using a conversion (lookup) table.

## Purpose
The main goal of this repository is to support learning and experimentation with **basic cryptography concepts**, such as substitution ciphers, character mapping, and reversible encryption mechanisms.

## How It Works
- A conversion table maps each character to another character using a fixed displacement.
- Encryption is performed by replacing each input character with its mapped value.
- Decryption is achieved by reversing the mapping process using the same table.

## Technologies
- **C++**

## Repository Contents
- Conversion table generation logic
- Encryption using table lookup
- Decryption by reverse table search
- Simple and readable implementation for study purposes

## How to Use
1. Clone the repository:
   ```bash
   git clone https://github.com/cyberdebb/Conversion-Table-Cipher.git
   ```
2. Compile the source code with a C++ compiler.
3. Run the program and test encryption and decryption with custom inputs.

## Notes
- This project is intended for educational and experimental use only.
- The cipher implemented here is not secure and must not be used in real-world or production environments.
