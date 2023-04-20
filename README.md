# Challenge-19
Ethereum ~ Crypto payment system
# history 50 > terminal_history.txt

# Integrating the Ethereum blockchain network - Developer
Enable customers to send cryptocurrency payments to fintech professionals.
## Technologies
["Fintech_finder.py" imports]

import streamlit as st
from dataclasses import dataclass
from typing import Any, List
from web3 import Web3
w3 = Web3(Web3.HTTPProvider('HTTP://127.0.0.1:7545'))
from crypto_wallet import generate_account, get_balance, send_transaction

["Crypto_wallet.py" imports]

import os
import requests
from dotenv import load_dotenv
load_dotenv()
from bip44 import Wallet
from web3 import Account
from web3 import middleware
from web3.gas_strategies.time_based import medium_gas_price_strategy

---

## Installation Guide
run program using streamlit

---

## Usage
generates a digital wallet, which access, your Ethereum account balances, sign and send transactions via a personal Ethereum blockchain called Ganache.




* Step 1: Generate a new Ethereum account instance by using the mnemonic seed phrase provided by Ganache.

* Step 2: Fetch and display the account balance associated with your Ethereum account address.

* Step 3: Calculate the total value of an Ethereum transaction, including the gas estimate, that pays a Fintech Finder candidate for their work.

* Step 4: Digitally sign a transaction that pays a Fintech Finder candidate, and send this transaction to the Ganache blockchain.

* Step 5: Review the transaction hash code associated with the validated blockchain transaction.


*Ganache main and transaction page*
![Ganache main page](https://github.com/MxP05/Challenge-19/blob/main/Images/ganacheeth.png?raw=true)
![Ganache transactions page](https://github.com/MxP05/Challenge-19/blob/main/Images/Ganachetransact.png?raw=true)
---

## Contributors

MxP05

---

## License
Enables customers to send cryptocurrency payments to fintech professionals.
