# Blockchain-Based Ledger System

This project is about building a simple a blockchain-based ledger system, completed with a user-friendly web interface. This ledger should allow partner banks to conduct financial transactions (that is, to transfer money between senders and receivers) and to verify the integrity of the data in the ledger.
### What We're Creating
We’ll make updates to the provided Python file (**pychain.py**), which already contains the basic PyChain ledger structure that were already created.

Create a new data class named Record. This class will serve as the blueprint for the financial transaction records that the blocks of the ledger will store.

Change the existing Block data class by replacing the generic data attribute with a record attribute that’s of type Record.

Create additional user input areas in the Streamlit application. These input areas should collect the relevant information for each financial record that you’ll store in the PyChain ledger.

Test your complete PyChain ledger.


## Technologies
This project is written in Python 3.8 with the following libraries and will be coded using Visual Studio Code (not in Jupyter Lab Notebook):

***panda*** -a Python package that provides fast, flexible, and expressive data structures designed to make working with "relational" or "labeled" data both easy and intuitive.

***streamlit*** - is an open-source Python library that makes it easy to create and share beautiful, custom web apps for machine learning and data science. In just a few minutes you can build and deploy powerful data apps.

***dataclasses*** -This module provides a decorator and functions for automatically adding generated special methods such as                           __init__() and __repr__() to user-defined classes.

***datetime*** -The datetime module supplies classes for manipulating dates and times.

***hashlib*** -This module implements a common interface to many different secure hash and message digest algorithms. Included are the FIPS secure hash algorithms SHA1, SHA224, SHA256, SHA384, and SHA512 (defined in FIPS 180-2) as well as RSA’s MD5 algorithm (defined in internet RFC 1321). 

## Installation Guide
Before running the application first install the following dependencies.

import streamlit as st

from dataclasses import dataclass

from typing import Any, List

import datetime as datetime

import pandas as pd

import hashlib

***Usage***
After cloning the repository, open the directory Starter Code and run the program by typing ***streamlit run pychain.py***



***Picture/Visual outputs from localhost:8501***

**Entering the Input Values**


![streamlit1](https://user-images.githubusercontent.com/93211640/166064232-49016da3-77c1-47ad-a14a-09627cfd3d3e.png)

**Add Block button** 


![streamlit2](https://user-images.githubusercontent.com/93211640/166064319-3f54217f-42ba-426f-ada7-775ce4fb7315.png)

**Validation Result** 


![streamlit3](https://user-images.githubusercontent.com/93211640/166064371-d8fd5b5d-6abb-4d12-afa8-48b447d29f39.png)













***Contributors***

James Tagapan

jtagapan@gmail.com

License

Licensed under the MIT License. Copyright 2020# Module_10_Challenge
