# Password and Secrets Vault Management Application

## Algorithms used
* SHA256 - Predictable password hash
* Argon2 - Unpredictable password hash for the database
* pbkdf2 - Generate the vault key
* AES256 - Encrypt and decrypt the vault

## Data flow
<img src="./diagram.png" width="500px" />
