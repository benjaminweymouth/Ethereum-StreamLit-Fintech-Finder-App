![An image shows a wallet with bitcoin.](Images/19-4-challenge-image.png)
## Cryptocurrency Wallet: Using StreamLit, Ganache and Python

 
This repository explores the following concepts: 

* Generate a new Ethereum account instance by using the mnemonic seed phrase provided by Ganache.

* Fetch and display the account balance associated with your Ethereum account address.

* Calculate the total value of an Ethereum transaction, including the gas estimate, that pays a Fintech Finder candidate for their work.

* Digitally sign a transaction that pays a Fintech Finder candidate, and send this transaction to the Ganache blockchain.

* Review the transaction hash code associated with the validated blockchain transaction.

Once you receive the transaction’s hash code, you will navigate to the Transactions section of Ganache to review the blockchain transaction details. To confirm that you have successfully created the transaction, you will save screenshots to the README.md file of your GitHub repository for this Challenge assignment.
 
## Steps & Screenshots:

Step 1: Download the source code, Install python3, streamlit, and all related dependencies. 

Step 2: Run streamlit in the terminal: type `streamlit run fintech_finder.py`. Then open the app in the localhost with port as indicated in the screenshot: 

[![streamlit run fintech_finder](https://github.com/benjaminweymouth/Ethereum-StreamLit-Python-Work/blob/main/Resources/Screenshots1.png)](https://github.com/benjaminweymouth/Ethereum-StreamLit-Python-Work/edit/main/README.md)

Review the app and functionality in the browser: 
[![streamlit run fintech_finder](https://github.com/benjaminweymouth/Ethereum-StreamLit-Python-Work/blob/main/Resources/Screenshots2a.png)](https://github.com/benjaminweymouth/Ethereum-StreamLit-Python-Work/edit/main/README.md)


Step 3: Select a member, add hours and notice the total wage. Click the Send Transaction button to sign and send the transaction. Screenshots follow: 

[![streamlit run fintech_finder](https://github.com/benjaminweymouth/Ethereum-StreamLit-Python-Work/blob/main/Resources/Screenshots3.png)](https://github.com/benjaminweymouth/Ethereum-StreamLit-Python-Work/edit/main/README.md)

Screenshot: Adding the number of hours for the wage equation

[![streamlit run fintech_finder](https://github.com/benjaminweymouth/Ethereum-StreamLit-Python-Work/blob/main/Resources/Screenshots3aa.png)](https://github.com/benjaminweymouth/Ethereum-StreamLit-Python-Work/edit/main/README.md)

Screenshot: Notice the wage indicated, and click on the transaction button 

[![streamlit run fintech_finder](https://github.com/benjaminweymouth/Ethereum-StreamLit-Python-Work/blob/main/Resources/Screenshots3b.png)](https://github.com/benjaminweymouth/Ethereum-StreamLit-Python-Work/edit/main/README.md)

Screenshot: The Transaction Hash is displayed successfully. 

[![streamlit run fintech_finder](https://github.com/benjaminweymouth/Ethereum-StreamLit-Python-Work/blob/main/Resources/Screenshots3c.png)](https://github.com/benjaminweymouth/Ethereum-StreamLit-Python-Work/edit/main/README.md)


Step 4: Check the account that paid the employee in Ganache. See that the your Ethereum account information has reduced ETH by the correct amount. 

[![streamlit run fintech_finder](https://github.com/benjaminweymouth/Ethereum-StreamLit-Python-Work/blob/main/Resources/Screenshots4a.png)](https://github.com/benjaminweymouth/Ethereum-StreamLit-Python-Work/edit/main/README.md)

Step 5: Navigate to the Transactions section of Ganache. Take a screenshot of your address balance and history on Ganache

[![streamlit run fintech_finder](https://github.com/benjaminweymouth/Ethereum-StreamLit-Python-Work/blob/main/Resources/Screenshots5.png)](https://github.com/benjaminweymouth/Ethereum-StreamLit-Python-Work/edit/main/README.md)

Step 6: Take a screenshot of the transaction details on Ganache

[![streamlit run fintech_finder](https://github.com/benjaminweymouth/Ethereum-StreamLit-Python-Work/blob/main/Resources/Screenshots6.png)](https://github.com/benjaminweymouth/Ethereum-StreamLit-Python-Work/edit/main/README.md)

## Conclusions: 

The streamlit app was successful, and the transaction completed successfully. The amount was appropriate and is utilizing the wage formula as stipulated in the fintech_founder python file. The mnemonic phrase is correctly called, and so is the account information and the account balance. 
