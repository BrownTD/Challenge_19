# Challenge_19

For this challenge I am working as a lead developer at a firm named Fintech Finder. I have been tasked with integrating the Ethereum blockchain network into the application in order to enable our customers to instantly pay the fintech professionals whom they hire with cryptocurrency.

In this challenge assignment I will generate a new Ethereum account instance by using the mnemonic seed phrase provided by Ganache, fetch and display the account balance associated with my Ethereum account address, calculate the total value of an Ethereum transaction(including gas estimations, that pay the candidate for their work), digitally sign a transaction that pays the Fintech Finder Candidate and send the tansaction to the Ganashe Blockchain, and review the transaction hash code aassociated with the validated blockchain transaction.

# Technologies

This project utilizespython 3.7 with the following packages:

- streamlit 

- Web3 

# Installation Guide

Before running the application install the following dependencies.

import streamlit as st
from typing import Any, List
from web3 import Web3
w3 = Web3(Web3.HTTPProvider('HTTP://127.0.0.1:7545'))
Usage


# Contributors

Completed by

Nevyn Brown

# License

MIT
