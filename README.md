# BadBankApp

Project Title: Banking Application

Description/Motivation: This project helps customers with full banking capabilities.  Customers can create accounts, make a deposit and withdraw an amount from the bank. 

Installation Guidelines: Clear instructions on how to get your project up and running.
1. Get the code from git using git clone https://github.com/suhasini-uidev/BadBankApp.git
2. Open a terminal and go to the directory.
3. Install mongodb node modules using command 'npm install mongodb'
4. Run the code using command 'node index.html'
5. Connect to the banking app using 'http://localhost:3000' in the browser

Screenshots: Refer to the 3 screen shots listed below for usage
1. LandingPage.png  shows the screen when you connect to the application from the browser
2. CreateAccount.png shows how one can create an account using the application.  Shows detail on how User, Email and password can be entered from url.  Display the account details after the account is displayed.
3. AllAccounts.png shows the url to display all accounts and how the accounts are displayed.

Technology used: The technologies used are HTML, CSS, javascript, React, Docker, Express, Nodejs and some packages that are useful for this project.

Features: The features in banking application  :-
A Customer is required to create an account to avail services offered by Bank. Bank verifies detail and creates new account for each new customer, Each customer can check the balance in bank account ,A customer can execute cash transactions where the customer must either add cash value to bank account or withdraw cash from account. Either of two or both that is credit as well as debit cash, might be executed to successfully execute one or multiple transactions.After each successful transaction customer might get details for action, Alldata button to check all the transactions the customer performed on his account, In future I want to include a Login  and Logout  buttons with Authentication.
Creating Accounts: We can use the url, http://localhost:3000/account/create/<name>/<email>/<password> in a browser to create an account.
Display All Accounts: Lists all the accounts by accessing url, http://localhost:3000/account/all in a browser

License: MIT
