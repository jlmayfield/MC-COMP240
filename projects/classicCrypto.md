---
layout: page
title: COMP240 - Classic Cryptography at the CLI
permalink: /teaching/COMP240/projects/classicCrypto
---

## The Goal

Create a &ast;nix CLI program for doing classic crptographic functions
* monoalphabetic substitution key generation
   * basic keywords, shifts, and reversals
   * via transposition by Grid and decimation
* Encrypt and Decrypt monoalphabetic substitution given key.  
* Polybius Square (Khan pg 83) codes
* Transposition Systems
   * Skytale and simple column/row Transposition
   * grid with column number key

Should be scriptable (multiple encrypt/decrypts for a given key or system of keys) but offer some interactive UI elements (key generation/management for sure). Should adhere to argument [standards](https://pubs.opengroup.org/onlinepubs/9699919799/basedefs/V1_chap12.html) and [also](https://www.gnu.org/software/libc/manual/html_node/Getopt-Long-Options.html).

## The Tools

C + getopt_long function. Secure C programming practices. Clang static analysis.
