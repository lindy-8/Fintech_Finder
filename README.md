# Fintech Finder
This is a visual studio file that utilizes two files, fintech_finder.py and crypto_wallet.py, that enables the ability automate tasks that come with generating wallets, retreiving account balances, and sending and validating transactions. The Fintech Finder application uses a personal ethereum blockchain via Ganache and its respective mnemonic seed phrase(s). This allows customers to find fintech professionals from a pool of candidates, look at their rates, assess possible hours, hire them, and pay them.
---

## Technologies & Libraries

This project utilizes python 3.7 with the following packages:

* [Web3](https://github.com/web3/web3.js) - A python interface for interacting with the Ethereum blockchain and ecosystem.

* [Streamlit](https://github.com/streamlit) - The fastest way to build data apps in Python. Information on github.

* [Dataclasses](https://docs.python.org/3/library/dataclasses.html) - This module provides a decorator and functions for automatically adding generated special methods.

* [Haslib](https://docs.python.org/3/library/hashlib.html) - This module implements a common interface to many different secure hash and message digest algorithms.

* [Typing](https://docs.python.org/3/library/typing.html) - This module provides runtime support for type hints.

* [Ganache](https://trufflesuite.com/ganache/) - A program that allows you to quickly set up a local blockchain, which you can use to test and develop smart contracts.

* [Bip44](https://pypi.org/project/bip44/) - A Python implementation for deriving hierarchical deterministic wallets from a seed phrase based on the BIP-44 standard.

* [MNEMONIC](https://pypi.org/project/mnemonic/) - A Python implementation for generating a 12- or 24-word mnemonic seed phrase based on the BIP-39 standard.
---

## Pre Installation Guide

You will have to download and install Ganache and run the quick start for this application.

Prior to running the application and code, please install the following dependencies:

```
import streamlit as st
from dataclasses import dataclass
from typing import Any, List
from web3 import Web3
w3 = Web3(Web3.HTTPProvider('HTTP://127.0.0.1:7545'))
```

```
import os
import requests
from dotenv import load_dotenv
load_dotenv()
from bip44 import Wallet
from web3 import Account
from web3 import middleware
from web3.gas_strategies.time_based import medium_gas_price_strategy
```

---
## Images

<img width="241" alt="Inspector" src="https://user-images.githubusercontent.com/117557983/232958479-d144e20b-fc84-4c35-ba2c-835dd516660d.PNG">

<img width="1241" alt="Interface" src="https://user-images.githubusercontent.com/117557983/232958549-b335ba9b-0a5e-4379-9d45-ce8c63056474.PNG">

<img width="885" alt="Ganache" src="https://user-images.githubusercontent.com/117557983/232958596-cfcfc8b7-34fc-4ef1-aa94-17de8f23f4f6.PNG">


## Contributors
DU starter code

Ben Lindauer

---

## License

MIT
