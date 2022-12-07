# Project Title: FinTech Finder

# Background
You work at a startup that is building a new and disruptive platform called Fintech Finder. Fintech Finder is an application that its customers can use to find fintech professionals from among a list of candidates, hire them, and pay them. As Fintech Finder’s lead developer, you have been tasked with integrating the Ethereum blockchain network into the application in order to enable your customers to instantly pay the fintech professionals whom they hire with cryptocurrency.

In this Challenge, you will complete the code that enables your customers to send cryptocurrency payments to fintech professionals. To develop the code and test it out, you will assume the perspective of a Fintech Finder customer who is using the application to find a fintech professional and pay them for their work.

# What You're Creating
The first file that you will use is called fintech_finder.py. It contains the code associated with the web interface of your application. The code included in this file is compatible with the Streamlit library. You will write all of your code for this Challenge in this file.

The second file that you will use is called crypto_wallet.py. This file contains the Ethereum transaction functions that you have created throughout this module’s lessons. By using import statements, you will integrate the crypto_wallet.py Python script into the Fintech Finder interface program that is found in the fintech_finder.py file.

Integrating these two files will allow you to automate the tasks associated with generating a digital wallet, accessing Ethereum account balances, and signing and sending transactions via a personal Ethereum blockchain called Ganache.

Specifically, you will assume the perspective of a Fintech Finder customer in order to do the following:

* Generate a new Ethereum account instance by using the mnemonic seed phrase provided by Ganache.

* Fetch and display the account balance associated with your Ethereum account address.

* Calculate the total value of an Ethereum transaction, including the gas estimate, that pays a Fintech Finder candidate for their work.

* Digitally sign a transaction that pays a Fintech Finder candidate, and send this transaction to the Ganache blockchain.

* Review the transaction hash code associated with the validated blockchain transaction.

Once you receive the transaction’s hash code, you will navigate to the Transactions section of Ganache to review the blockchain transaction details.

## Summary

Sender's address balance and history
---
![ganache-balance-sender](https://user-images.githubusercontent.com/34729547/206237197-185a6f17-76a8-4302-9960-55ceee773bdd.PNG)

Ganache transaction details
---
![ganache-transaction-details](https://user-images.githubusercontent.com/34729547/206237239-c85bcf0c-1a6c-4f5b-b885-3274d87d2d8f.PNG)

Recipient's address balance and history
---
![ganache-balance-recipient](https://user-images.githubusercontent.com/34729547/206237299-2b450f16-5fc0-41b9-a894-982a70298661.PNG)


## Technologies: Python 3, Streamlit, Ganache
---
Python 3 or later.

Streamlit for web interface.

Ganache for Ethereum accounts.

---

## Usage: streamlit run fintech_finder.py
---

Ensure the proper libraries and dependencies have been imported.

fintech_finder.py:

![image](https://user-images.githubusercontent.com/34729547/206232897-57ad9dec-8d51-4fd3-bec8-f5e96a61faaa.png)

crypto_wallet.py:

![image](https://user-images.githubusercontent.com/34729547/206237124-ea9ac233-28bb-4667-9e3d-5022d590d9ed.png)

---

## Contributors: Nia Robinson

LinkedIn: https://www.linkedin.com/in/niaelanrobinson/

---

## License

MIT License.

