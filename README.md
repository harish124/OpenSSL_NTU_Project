# OpenSSL_NTU_Project
This project demonstrates my Hands-on Experience in using OpenSSL library for encryption, decryption, key generation and creating message digests.

# What I have done in this project and what are the files in this repo ?
1. Get a file of size between 1 to 10 MB and name this file plaintext_file.
2. Hash plaintext file using SHA-512. Output the digest to a file named digest_file.hex in hexadecimal format.
3. Generate an RSA-4096 key pair. Output and save the public key in PEM format as RSA_public_key.pem. Output and save the private key in PEM format as RSA_private_key.pem.
4. Sign plaintext file using the RSA private key above and output as signed_file. Verify the signature by using the RSA public key.
5. Generate an AES-256 key and output the string as AES_key.txt.
6. Encrypt the AES key by using the RSA public key and output as encrypted_AES_key.txt.
7. Decrypt encrypted_AES_key.txt by using the RSA private key and output as a string into a file named decrypted_AES_key.txt.
Ensure that the content is identical with AES_key.txt.
8. Encrypt plaintext_file by using the AES key in any mode of operation of your choice, e.g., Galois Counter
Mode (GCM).
9. Output the encrypted file as ciphertext_file and specify the chosen mode of operation. I have choosen Counter mode - Ctr mode in this project. So IV for this is present in iv.txt file
