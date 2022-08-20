# Bootcamp_Week_19

# Fintech Finder

This program is designed to integrate the Ethereum blockchain network into an application in order to enable customers to instantly pay the fintech professionals whom they hire with cryptocurrency. For development purposes, we will assume the perspective of a Fintech Finder customer who is using the application to find a fintech professional and pay them for their work.


## Technologies

Within this program, we will make use of the following external python modules:

  -- streamlit
  -- dataclasses
  -- typing
  -- web3
  -- dotenv
  -- bip44
  
  Additionally, this program was created within a python v3.7 build, and its relevant dependencies.

---

## Installation Guide

To utilize this program, within your terminal you will have to install the required libraries. Within your terminal, input the following commands:

```python
pip install streamlit
```

```python
pip install dataclasses
```

```python
pip install typing-extensions
```

```python
pip install web3
```

```python
pip install python-dotenv
```

```python
pip install bip44
```

At the beginning of the *fintech_finder.py* file, the technologies are called in with this code:

```
import streamlit as st
from dataclasses import dataclass
from typing import Any, List
from web3 import Web3
w3 = Web3(Web3.HTTPProvider('HTTP://127.0.0.1:7545'))
```

---

## Usage

To operate this program, open up your terminal of choice and navigate to the directory in which you have downloaded the files within this repository. Run the relavant file with the command: 

```python
streamlit run fintech_finder.py
```  

The Streamlit application will run locally in your browser and should launch automatically. From here you can enter the pertinent sender, receiver, and amount details to add to the ledger. This will be immediately updated and can be validated via the the ledger itself. 

---
## Ganache Validation

In the screenshot below we can clearly see within Ganacge the sender’s address balance and history

![history](/Resources/ganache_accounts.PNG)

In the screenshot below we can clearly see within Ganache the transaction itself as well as the accounts for both sender and recipient

![transaction](/Resources/ganache_trans.PNG)


---

## Contributors

Colton Mayes ctmayes@gmail.com

---

## License

This code is created for educational purposes, and it usage therein has no commerical application. It is designated as free-use thusly, and shall remain as such.