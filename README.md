<font size='10'>Cipher Shuffle</font>

17<sup>st</sup> August 2024

Prepared By: `Rishabh Chauhan`

Challenge Author(s): `Rishabh Chauhan`

Difficulty: <font color='orange'>Easy</font>

<br><br>

# Synopsis (!)

Unlock the hint by decoding a Base64 encoded string. Extract the AES key and use it to decrypt the hidden message using AES-GCM. Finally get the flag to complete the challenge.

## Description (!)

- Decode the hint which is Base64 encoded. It will reveal the AES encryption key.
- From the decoded hint, obtain other parameter like nonce, history, and tag.
- Use the nonce, history, and tag to decrypt the message using AES-GCM with provided key.
- The decrypted message will contain the flag.

- The solver.py is developed to solve the challenge by reading the data from challenge.txt file.

## Skills Required (!)

- Python
- Researching Skills
- Encryption
- Encoding

## Skills Learned (!)

- Learn how encoding and decoding works.
- Learn how AES works.

# Enumeration (!)

## Analyzing the source code (*)


# Solution (!)

## Finding the vulnerability (*)


## Exploitation (!)

### Connecting to the server (*)

### Getting the flag (!)

The decrypted message will contain the flag in HTB{FLAG} format.
