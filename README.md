# :pushpin:	 # _Test Planing_ 

## :pushpin:	# Guru99 Aplication 

## :pushpin:	 ## Guru99 Bank Project

 
## :pushpin:	 ## _Software request_
 
1.3
 
03/11/2023

## :pushpin:	  Revision history


| Date | Description   | Author   | Comments |
| :-----: | :---: | :---: | :---: |
|03.11.2023 | Test Plan for version 1.1   | -   | Draft test plan |
| 06.12.2023 | v1.1  | Ravan Ungar   | - |


# :pushpin:	# 1.Intro

#### :pushpin:	#### The Guru99 Bank project aims to provide net banking facility to its customers.
#### :pushpin:	#### This release will have limited features. Over a period of time , new and new functionalities will be added to the site.

## :pushpin:	## Introduction
The Guru99 Bank project aims to provide net banking facility to its customers.
This release will have limited features. Over a period of time , new and new functionalities will be added to the site.

### :pushpin:	### 1.1 Purpose
The Purpose of this document is to outline the requirements for the Guru99 Banking website to be developed for Guru99 Tech. Pvt. Ltd. This document will be used by all stakeholders including developers and testers.
### :pushpin:	### 1.2 Scope
The scope of this project is limited to the testing of the features described in the succeeding sections of this document.
Non-functional testing like stress,performance is beyond scope of this project.
Automation testing is beyond scope.
Functional testing & external interfaces are in scope and need to be tested
The banking site will be only compatible with Chrome version 27 and above

# :pushpin:	# 1.3 Testing section
## 1.4 Test Planning
The Test Plan is designed to describe all details of testing for the X module from the Guru99 application.

The plan identifies the items to be tested, the features to be tested, the types of testing to be performed, the personnel responsible for testing, the resources and schedule required to complete testing, and the risks associated with the plan

1.5. # Specific Requirements
The Guru99 Bank will have 2 roles
### 1.	Manager
### 2.	Customer
Following features/modules will be available to these 2 different roles

| Manager | Customer   | 
| :-----: | :---: | 
|New Customer| Balance enquiry   | 
| Edit Customer | Fund Transfer  |
|Delete Customer| Mini Statement   | 
| New Account | Customized Statement  |
|Edit Account| Change Password | 
|Delete Account | Login & Logout  |
|Deposit|  | 
| Withdrawal |  |
|Fund Transfer|    | 
| Change Password |  |
|Balance Enquiry| | 
|Mini Statement |  |
|Customized Statement|  | 
|Login & Logout |   |

### 1.6 Roles assigned to the project and persons allocated
| Date | Description   | Author   | Comments |
| :-----: | :---: | :---: | :---: |
|03.11.2023 | Test Plan for version 1.1   | -   | Draft test plan |
| 06.11.2023 | v1.1  | Ravan Ungar   | - |


1.7 Test scope
Tests in scope:
Tests not in scope:
1.1.5 Risks detected
Project risks:
Product risks:
1.1.6 Evaluating entry criteria
The entry criterias defined in the Test Planning phase have been achieved and the test process can continue.

1.8 Test Monitoring and Control
It will be done by generating periodic reports that reflect the current status of the test.
### Daily Report 


1.9 Test Analysis
The testing process will be executed based on the above requirements for the Dependents module. The following test conditions were found:

## :paperclip:	## _Fund Transfer_
-	Payers account no
*	Payees account no
+	Amount
-	Submit
*	Reset

## :paperclip:	## _Change Password_
-	Old Password
*	New Password
+	Confirm Password
-	Submit
*	Reset

## :paperclip:	## _Balance enquiry_
-	Account No
*	Submit
+	Reset

## :paperclip:	## _Mini Statement_
-	Account No
*	Submit
+	Reset

## :paperclip:	## _Customized Statement_
-	Account No
*	From Date
+	To Date
-	Amount Lower Limit
*	Number Of Transaction
+	Submit
-	Reset

## :paperclip:	## _New Customer_
-	Customer Name
*	Gender
+	Date of Birth
-	Address
*	City
+	State
- PIN
*	Telephone Number
+	Email Id 
-	Submit
*	Reset

## :paperclip:	## _New Account_
-	Customer Id
*	Account Type
+	Initial deposit
-	Submit
*	Reset

## :paperclip:	##  _Deposit_
-	Account Number
*	Amount Deposit
+	Description
-	Submit
*	Reset

## :paperclip:	##  _Withdraw_
-	Account Number 
*	Amount
+	Description
-	Submit
*	Reset

## :paperclip:	##  _Delete Customer_
-	Customer Id
*	Submit
+	Reset

## :paperclip:	##  _Edit Account_
-	Account Number
*	Submit
+	Reset

## :paperclip:	## Form after submitting Edit Account
-	Customer Id 
*	Account Type (Drop Down - Saving or Current)
+	Balance 
-	Submit
*	Reset

## :paperclip:	##  _Delete Account_
-	Account Number
*	Submit
+	Reset

## :paperclip:	##  _Edit Customer_
-	Customer Id
*	Submit
+	Reset

## :paperclip:	## Form after submitting Edit Customer
-	Customer Name 
*	Gender 
+	Date of Birth
-	Address
*	City
+	State
-	PIN
*	Telephone Number
+	Email Id 
-	Submit
*	Reset

1.10 Test Design
Functional test cases were created in Zephyr Squad. Based on the analysis of the specifications, the test design techniques used for generating test cases are:

Test cases: -> 
The test cases with steps can be viewed here: [Test Cases](https://github.com/razvanandrei1974/Proiect-Jira-/blob/main/Testcase%20pdf.pdf)

1.11 Test Implementation
The following elements are needed to be ready before the test execution phase begins:

enter here what needs to be ready for the test execution to begin

## :paperclip:	## 2 Test Execution
- Test cases are executed on the created test Cycle summary: [Cycle Summary](https://github.com/razvanandrei1974/Proiect-Jira-/blob/main/test%20summary%2006.12.2023.pdf)

### 2.1. Definitions, Acronyms, and Abbreviations
Abbreviation	Word
M	Manager
C	Customer

### 2.1.1 Entry criteria defined
Smoke test passed (being the most basic type of test, this is a very important entry criteria in the process of testing)
testing environment is up and running
### 2.1.2. Exit criteria:
90% of tests are passed
no Critical issues have Open status
update tests are 100% passed (update tests will not generate other new issues that impact the application)
### 2.1.3. Risks:
user data (banking related data, funds, transactions, etc) might be impacted with update tests
stability risks (crashes, disconnects, etc)
IE browser might have performance issues
versions of IE older than 1.5923e have security vulnerabilities (we could mention what vulnerabilities are)
the web page pagination could be impacted when opened on mobile devices
stress conditions might impact the web application
new browser might not be supported

## 2.2. Test Analisys

| Module Name | Aplicabile Rules   | Description   |
| :-----: | :---: | :-------------------------------------------------------------:  |
|Balance enquiry|  Manager customer  | **Customer:**  A customer can have multiple bank accounts. He can view balance of his accounts only . Manager: A manager can view balance of all the customers who come under his supervision|
|Fund Transfer|  Manager customer  |Customer: A customer can have transfer funds from his “own” account to any destination account. Manager: A manager can transfer funds from any source bank account to destination account|				   							
|Mini Statement|  Manager customer  |A Mini statement will show last 5 transactions of an account. Customer: A customer can see mini-statement of only his “own” accounts. Manager: A manager can see ministatement of any account. |	 
|Customized Statement|  Manager customer  |A customized statement allows you to filter and display transactions in an account based on date, transaction value Customer: A customer can see Customized- statement of only his “own” accounts Manager: A manager can see Customized -statement of any account |
|Change Password|  Manager customer  |Customer: A customer can change password of only his account.Manager: A manager can change password of only his account. He cannot change passwords of his customers |
|New Customer|  Manager   |Manager: A manager can add a new customer.Manager: A manager can edit details like address, email , telephone of a customer. |
|New Account|  Manager   |Currently system provides 2 types of accounts ●	Saving ●	Current A customer can have multiple saving accounts (one in his name , other in a joint name etc).He can have multiple current accounts for different companies he owns. Or he can have a multiple current and saving accounts. Manager: A manager can add a new account for an existing customer.  |
|Edit Account|  Manager   |Manager: A manager can add a edit account details for an existing account|
|Delete Account|  Manager   |Manager: A manager can add a delete an account for a customer.|
|Delete Customer|  Manager   |A customer can be deleted only if he/she has  no active current or saving accounts Manager: A manager can delete a customer.|
|Deposit|  Manager   |Manager: A manager can deposit money into any account. Usually done when cash is deposited at a bank branch.|
|Withdrawal|  Manager   |Manager: A manager can withdraw money from any account. Usually done when cash is withdrawn at a bank branch.|

## 2.2.1.Test implementation

### New Account
- T1    Customer Id - Customer ID is required
* T2    Customer Id - Special character are not allowed
+ T3    Customer Id - Characters are not allowed
- T3.1 Customer Id - First character cannot have space

### New Customer
- T4    Customer Name – Numbers are not allowed
* T5    Customer Name – Special characters are not allowed
+ T6    Customer Name -  Customer name must not be blank
- T7    Customer Name - First character cannot have space
* T8    Address - Address Field must not be blank
+ T9    Address - First character can not have space
- T10  Address - Special characters are not allowed
* T11  City - Special character are not allowed
+ T12  City - City Field must not be blank
- T13  City – Numbers are not allowed
* T14  City - First character can not have space
+ T15  State – Numbers are not allowed
- T16  State - State must not be blank
* T17  State – Special characters are not allowed
+ T17.1  State – First character cannot have space
- T18  Pin - Characters are not allowed
* T19  Pin - PIN Code must not be blank
+ T20  Pin – Special characters are not allowed
- T21  Pin – PIN Code must have 6 Digits
* T22  Pin - First character can not have space
+ T23  Telephone Number – Mobile no must not be blank
- T24  Telephone Number  – Special character are not allowed
* T25  Telephone Number  – Character are not allowed
+ T26  Telephone Number - First character can not have space
- T27  Email : Email ID must not be blank
* T28  Email : Email ID is not valid
+ T29  Email : First character can not have space

### Balance Enquiry
- T30  Account No must not be blank
* T31  Special character are not allowed
+ T32  Characters are not allowed
 
### Customized Statement Form
- T33  Account No - Account Number must not be blank
* T34  Account No - Characters are not allowed
+ T35  Account No - Special characters are not allowed
- T36  Amount Lower Limit – Special character are not allowed
* T37  Amount Lower Limit – Amount Lower Limit is required
+ T38  Amount Lower Limit – Characters are not allowed
- T39  Number of Transaction – Special character are not allowed
* T40  Number of Transaction  - Number of Transaction must not be blank
+ T41  Number of Transaction – Character are not allowed

### Delete Account Form
- T42  Account No must not be blank
* T43  Special character are not allowed
+ T44  Characters are not allowed

### Delete Customer
- T45  Customer Id - Customer ID is required
* T46  Customer Id - Special character are not allowed
+ T47  Customer Id - Characters are not allowed
- T47.1  Customer Id - First character cannot have space

### Deposit
- T48  Account No must not be blank
* T49  Special character are not allowed
+ T50  Characters are not allowed
- T51   Amount field must not be blank
* T52   Special characters are not allowed
+ T53   Characters are not allowed
- T54   Description must not be blank
 
### Edit Account
- T55   Account No must not be blank
* T56   Special character are not allowed
+ T57   Characters are not allowed

### Edit Customer form
- T58   Customer Id - Customer ID is required
* T59   Customer Id - Special character are not allowed
+ T60   Customer Id - Characters are not allowed
- T60.1   Customer Id - First character can not have space

### Edit Customer
- T61   Address - Address Field must not be blank
* T62   Address - First character can not have space
+ T63   Address - Special characters are not allowed
- T64   City - Special character are not allowed
* T65   City - City Field must not be blank
+ T66   City – Numbers are not allowed
- T67   City - First character can not have space
* T68   State – Numbers are not allowed
+ T69   State - State must not be blank
- T70   State – Special characters are not allowed
* T70.1   State – First character cannot have space
+ T71   Pin - Characters are not allowed
- T71   Pin - PIN Code must not be blank
* T72   Pin – Special characters are not allowed
+ T73   Pin – PIN Code must have 6 Digits
- T74   Pin - First character cannot have space
* T75   Telephone Number – Mobile no must not be blank
+ T76   Telephone Number  – Special character are not allowed
- T77   Telephone Number  – Character are not allowed
* T78   Telephone Number - First character cannot have space
+ T79   Email : Email ID must not be blank
- T80   Email : Email ID is not valid
* T81   Email : First character cannot have space 

### Fund Transfer
- T82   Payers Account Number must not be blank
* T83   Special characters are not allowed
+ T84   Characters are not allowed
- T85   Payees Account Number must not be blank
* T86   Special characters are not allowed
+ T87   Characters are not allowed
- T88   Amount Field must not be blank
* T89   Characters are not allowed
+ T90   Special characters are not allowed
- T91   Description cannot be blank
 
### Login
- T92   User-ID must not be blank
* T93   Password must not be blank
+ Mini Statement Page
- T94   Account No must not be blank
* T95   Special character are not allowed
+ T96   Characters are not allowed

### Change Password
- T97   Old Password must not be blank
* T98   New Password must not be blank
+ T99   Enter at-least one numeric value
- T100 Enter at-least one special character
* T101 Choose a difficult Password
+ T102 Confirm Password must not be blank
- T103 Passwords do not Match 


### Withdraw
- T104 Account No must not be blank
* T105 Special character are not allowed
+ T106 Characters are not allowed
- T107 Amount Field must not be blank
* T108 Characters are not allowed
+ T109 Special characters are not allowed
- T110 Description cannot be blank


## 3.0.  Test closure
- at least 95% of tests are passed
* no Critical issues have Open status
  

  # 3.1 Test deliverables
  
 ### Test cases
 [Test cases](https://github.com/razvanandrei1974/Proiect-Jira-/blob/main/Testcase%20pdf.pdf)
  Daily test summary report
 - [Daily test summary report(number of tests ran today, % of them failed, passed, re-test, etc](https://github.com/razvanandrei1974/Proiect-Jira-/blob/main/test%20metrics.pdf)
  Traceability matrix
 - [Traceability matrix](https://github.com/razvanandrei1974/Proiect-Jira-/blob/main/Forward%20Traceability_6_12_2023.pdf)
  Test case results
 - [Test case results](https://github.com/razvanandrei1974/Proiect-Jira-/blob/main/UngarRazvan-TMTA12%20(2).pdf)
 - ![Dashboard](https://github.com/razvanandrei1974/Proiect-Jira-/blob/main/DASHBOARD_Page_1.jpg)
 - ![Dashboard2](https://github.com/razvanandrei1974/Proiect-Jira-/blob/main/DASHBOARD_Page_2.jpg)
 - ![Dashboard3](https://github.com/razvanandrei1974/Proiect-Jira-/blob/main/DASHBOARD_Page_3.jpg)
   Test completion report
 - ![Test completion report](https://github.com/razvanandrei1974/Proiect-Jira-/blob/main/test%20summary%2006.12.2023.pdf)
  - we have 10 days of testing
 - we have 2000 regression tests
 - in order to finish the regression run we would need to run an ~ of 35 tests/day

_____________________________________________________________________________________________________________________________________________________________________________


