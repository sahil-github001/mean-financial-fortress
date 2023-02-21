# Bank-Site-Angular-Financial-Fortress
Financial Fortress is a simple banking application built with Angular for the frontend, Node.js Express for the backend, and MongoDB for the database. The purpose of this application is to allow users to register an account, login, and perform basic banking operations like depositing and withdrawing money. Additionally, users can delete their accounts, logout, and view their transaction history.

The registration process requires the user to enter their account number, username, and password. This information is then stored in the MongoDB database for future reference. Once registered, the user can log in using their account number and password to access the banking features of the application.

The deposit feature allows users to deposit money into their account by entering their account number, password, and the amount they wish to deposit. The application will update the user's account balance in the database accordingly.

The withdraw feature allows users to withdraw money from their account by entering their account number, password, and the amount they wish to withdraw. The application will update the user's account balance in the database accordingly, but only if the user has sufficient funds to complete the transaction.

The delete account feature allows users to permanently delete their account from the database.

Finally, the view transactions feature allows users to view their transaction history, including deposit and withdrawal transactions. This information is retrieved from the MongoDB database and displayed to the user.

