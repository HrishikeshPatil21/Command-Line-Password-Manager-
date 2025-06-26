# Command-Line-Password-Manager-
This project is a secure Python-based command-line application designed to manage and protect user passwords. It uses a master password to control access and applies AES encryption (via the cryptography library) to store all credentials safely in a local file.
Users can add, view, and manage credentials for multiple websites or apps. Passwords are encrypted and stored in a JSON file (vault.json), and can only be accessed after entering the correct master key. The project uses getpass to securely input passwords without displaying them on the screen.
