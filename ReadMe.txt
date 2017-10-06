CUSTOMER MANAGEMENT SYSTEM
(By Ashveen Bansal)
Introduction:
The objective behind this project is to make a simpler version of Customer Management System, abbreviated as CMS henceforth, used by banks. The assumptions taken to make the CMS are:
1)	There are just two kind of employees – Manager and Accountants.
2)	Manager can add accountants, who further have access to data of all the customers. 
3)	Manager can view the EMI and net payable interest on two types of loan the bank offers – car and home. 
4)	The record of the transactions done by a customer is not saved. Only current balance is saved.
5)	A minimum balance of Rs. 100 must be maintained.

Languages:
Front End: Java Swings
Back End: MySQL

Working:
 
On starting the CMS, a windows appears where user has to select his type – Manager or Accountant. 

His selection takes him to the login page of that user. For manager, the username and password is inbuilt into the system with username being “ashveen” and password “ashveenbansal”. The username and password of managers are as entered by Manager while adding them and are saved in database project in the table accountants, where the passwords are saved as simple varchar for the sake of simplicity. 

The manager has three options:
•	Add Accountants - To add new accountants
 
•	Edit Accountants - To view/edit current accountants
 

•	Loan - To view the EMI and net payable interest at two kind of loans – home and car for which interest rate are set at 8.35% and 9.25% respectively.

 
Accountants also has three options – 
•	Add Customer – To add new customers

•	View Customer – To view name, mobile number and balance of the customer based on his id and also credit/debit his account. Trying to debit an amount greater than balance or which would lead to balance being less than 100 fails and a dialog box appears. 

•	Edit Customer – To edit details of any customer based on his id.
 

