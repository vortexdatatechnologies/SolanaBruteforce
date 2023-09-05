# SolanaBruteforce
This repository contains a Python script that generates and verifies mnemonic pair keys on the Solana network. The script uses random mnemonic words to create pairwise keys, and then queries the Solana network to check if the accounts associated with the keys have non-zero balances. When an account with a balance is found, the public key and corresponding seed are stored in a text file.

## Key features:

- Generates random mnemonic pair keys using a predefined list of mnemonic words.
- Uses the Solana Python library to query the balance of accounts associated with the generated public keys.
- Provides a mechanism to verify accounts with non-zero balances in the Solana network.
- Includes a delay between queries to avoid excessive load on the Solana API.
## Caution:
Please use this script responsibly and consider the resources and limitations of the Solana network. Generating a large number of Solana API requests may have undesirable impacts on the network. Read and understand the terms of use of the services you interact with before running this script.

## Note:
This script is provided for educational purposes and to show how you can interact with the Solana network using mnemonic keys.
