# Data Encryption

Examples of Data encryption &amp; Network Security

This repository contains various example of Data Encryption Techniques used for Network Security.

## Introduction

Cryptography involves communication between two users through coded message. Cryptography is an art and science of concealing the information to introduce privacy and secrecy between the intended users.  The three basic goals of security are Confidentiality, Integrity and Availability.
Cryptography involves three basic mechanisms 
  * Symmetric-Key (Private-Key) Encipherment
  * Asymmetric-Key Encipherment(Public-Key)
  * Hashing.
### Symmetric key encipherment 

A single secret key is used for both encryption and decryption. In addition, the encryption and decryption algorithms are inverses of each other. The original message known as plain text is encrypted using a secret key to obtain the unintelligible message called cipher text. This cipher text is transmitted through the channel to the intended receiver. At the receiver, the cipher text is decrypted using the same secret key to obtain the original plain text. 
Traditional Symmetric Ciphers are the foundation to modern ciphers. They are classified into two broad categories
 * Substitution Cipher
    
    A substitution cipher replaces one symbol with another 
 
 * Transposition Cipher.
 
    A transposition cipher does not substitute one symbol for another, instead     it changes(transposes) the location of the symbols.  


## Examples of Dens.

1. To implement Substitution/ Caesar Cipher
   
   Algorithm
   * Enter the plain text.
   * Enter the key 
   * Enter modulus. 
   * Obtain cipher text as follows.
   * Obtain deciphered text as follows. 
   
2. Transposition Cipher and Reverse Cipher
    
    Algoritm
     * Enter the plain text
     *	Enter the positions by which the text has to be transposed
     *	Apply the circular shift logic to obtain the Transposition Cipher.
     *	Apply reverse logic to obtain the plain text back. 


   [Collab Link](https://colab.research.google.com/drive/1VQ8B-Z1AaSX3T1UcIbCfurLwikRKC54j)
   
2. [To implement Brute Force Attack on Traditional Cipher](https://colab.research.google.com/drive/1c5T1nPbo6FPxzqTkmoO06Qu_LVx5ukmx)
