## KryptoJobs2Go Web3 Application

In this Challenge, We will build an application for a company called KryptoJobs2Go. The code will its customers to find fintech professionals from among a list of candidates, hire them, and pay themn using Ethereum.

The first file `krypto_jobs.py` contains the code associated with the web interface of the application using the Streamlit library.

The second file `crypto_wallet.py`. contains the Ethereum transaction functions .By using import statements, we integrate the `crypto_wallet.py` Python script into the KryptoJobs2Go interface program in `krypto_jobs.py` 

Integrating these two files will allow us to automate the tasks associated with generating a digital wallet, accessing Ethereum account balances, and signing and sending transactions via a personal Ethereum blockchain called Ganache.

 To develop the code and test it out, We will assume the perspective of a KryptoJobs2Go customer who is using the application to find a fintech professional and pay them for their work through a streamlit front end Web application.

-------------------------------------------

# Operations: 

* Import Ethereum Transaction Functions into the KryptoJobs2Go Application
* Sign and Execute a Payment Transaction
* Inspect the Transaction on Ganache.

# Streamlit Code

 KryptoJobs2Go customers will select a fintech professional from the
 application interface’s drop-down menu, and then input the amount of time for
 which they’ll hire the worker. The application will calculate the amount that the
 worker will be paid in ether. Using a button, this that will send an Ethereum blockchain transaction that pays the hired candidate. 

![Screen shot StreamLit Interface succesfully generating transaction hash](Images/StreamLit_UI_ScreenShot.png)


# Ganache Transaction
-----------

![alt=""](Images/Ganache_address_balance.png)
![alt=""](Images/to_address_Ganache.png)
![alt=""](Images/transaction_details_ganache.png)




## project issues : 

Error: Transaction's maxFeePerGas (0) is less than the block's baseFeePerGas (527514873). 

Error identified and corrected. However, transactions were still minted on the local block chain. They these blocks do not contain  transaction details. 
![alt=""](Images/Block_scrrenshots_error.png)

Error identified and corrected.
![alt=""](Images/Screenshot_Error_get_balance.png)
