# One-Time Pad Encryption in C

## Overview

This project implements a **One-Time Pad (OTP)** encryption system in C. The OTP encryption method is a theoretically unbreakable cipher when the key is truly random, as long as the key is as long as the message and used only once.



## Files

- **enc.c**: C program for encrypting a plaintext file with a one-time pad key.
- **dec.c**: C program for decrypting a ciphertext file using the same one-time pad key.


## Requirements

- C compiler (e.g., GCC)
- Basic understanding of command line usage

## Compilation

To compile the encryption and decryption programs, run the following commands in your terminal:

```bash
gcc enc.c -o enc
gcc dec.c -o dec
```

## Usage
- ./enc secret
- ./dec crypt.out key.out

