# Dual-Key Logical Caesar Cipher with Rail Fence and XOR

A modified cryptographic algorithm developed for CC5009NI - Cyber Security in 
Computing coursework. This project enhances the traditional Caesar Cipher by 
introducing position-based logical operations, Rail Fence transposition, and 
binary-level XOR operations to improve confusion and diffusion.

## Overview
The traditional Caesar Cipher, while simple, suffers from major security 
weaknesses such as a small key space and vulnerability to frequency analysis. 
This project addresses those weaknesses by combining three layers of encryption:

1. **Dual-Key Caesar Cipher** – Uses a main key (K1) applied to all characters, 
   and a logical key (K2) applied based on character position (odd/even).
2. **Rail Fence Transposition** – Rearranges character order using a 2-rail 
   zig-zag pattern to add diffusion.
3. **XOR Operation** – Converts characters to 8-bit ASCII binary and applies a 
   fixed XOR key for an additional layer of binary-level security.

