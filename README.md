# EwalletService
Developed the application of E-wallet Service using the Spring boot Framework. The features of wallet was to do a transaction, checking balance and balance history
"WalletService" is a Spring Boot JPA application that stores user wallet information.I have used MySql. On successful transaction we send sms and email to sender and receiver. WalletService communicate with UserService using RestTemplate . Also, written a transaction job that run every month and send transation history of a user on his mail id with proper file attachment . "UserService" is a Spring Boot JPA application that stores user information. We have used MySql Databse.

