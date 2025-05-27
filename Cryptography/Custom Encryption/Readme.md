Custom Encryption — picoCTF 2024
Category: Medium | Cryptography

![Screenshot 2025-05-28 004825](https://github.com/user-attachments/assets/2607b49a-3283-4b5e-9f6e-38b2e33a5411)
Challenge Description
Can you get sense of this code file and write the function that will decode the given encrypted file content?
You are given:

A code file with the encryption logic

An enc_flag file containing encrypted numbers
![Screenshot 2025-05-28 004842](https://github.com/user-attachments/assets/abd95ab2-b5b4-41ab-a215-a81e7cf745dc)

 Inspect the Encrypted File
Open enc_flag.
It contains values of a = 95, b = 21, and a list of encrypted integers:
![Screenshot 2025-05-28 005157](https://github.com/user-attachments/assets/2fe19033-1e7f-456b-99d8-a303435b4c6d)


Understand the Encryption Logic
From the provided custom_encryption.py:
![Screenshot 2025-05-28 005445](https://github.com/user-attachments/assets/b2b1b395-450b-486f-8cdd-54cf06d4ec06)

Write the Decryption Script
Use this script to decode the ciphertext:
![Screenshot 2025-05-28 005821](https://github.com/user-attachments/assets/81e2d097-22be-41cf-b2df-7498edd38c4c)
Reverse the String
Use dcode.fr or any string reversal tool to fix it.
![Screenshot 2025-05-28 010125](https://github.com/user-attachments/assets/3f9b3bde-9001-4986-89e9-7aa712ee5b76)
Final Flag:
picoCTF{custom_d2cr0pt6d_66778b34}

![Screenshot 2025-05-28 010146](https://github.com/user-attachments/assets/29eb8a90-6fb4-4d75-a1d7-6a3880988d04)
