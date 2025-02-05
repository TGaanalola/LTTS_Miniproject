# Requirements
## Introduction
 *	Banks play an important role in the financial system and the economy. To ensure a smooth running of the banking system, it must be properly managed. With the help of Bank management system the user can perform all the tasks like creating an account, deposit amount, withdraw amount, check balance, view all account holders details, close an account and modify an account.
 * This topic was chosen because it gives me an opportunity to develop a software for solving financial applications of a customer in banking environment in order to nurture the needs of an end banking user by providing various ways to perform banking tasks and provides me flexibility to understand multiple C programming concepts.


## Research
### Benefits of Bank management system:
  * Bank is the place where customers feel the sense of safety for their property. In the bank, customers deposit and withdraw their money. Transaction of money also a part of it. Now to keep the belief and trust of customers, there is the positive need for management of the bank, which can handle all this with comfort and ease. Smooth and efficient management affects the satisfaction of the customers and staff members, indirectly. And of course, it encourages management committee in taking some needed decision for future enhancement of the bank. Now-a-days, managing a bank is a tedious job upto certain limit so software that reduces the work is essential. Also the present computer world is getting faster and faster day-by-day. Thus, considering above necessities, the software for bank management has became necessary which would be useful in managing the bank more efficiently.
  * This project has been developed to carry out the processes easily and quickly, which is not possible with the manuals systems, which are overcome by this software.
## Cost and Features
 * Bank Management system software cost varies with the changes in market demand and also with variations and upgradations.
## Defining Our System
### Existing system
 * In the existing system the transactions are done only manually but in proposed system we have to computerize all the banking transaction using the software Bank management system.
 * Disadvantages of existing system:
     * Lack of security of data.
     * More man power.
     * Time consuming.
     * Consumes large volume of pare work.
     * Needs manual calculations.
     * No direct role for the higher oﬃcials.
     * Damage of machines due to lack of attention.
  * To avoid all these limitations and make the working more accurately the system needs to be computerized.
### Proposed system
 * The aim of proposed system is to develop a system of improved facilities. The proposed system can overcome all the limitations of the existing system. The system provides proper security and reduces the manual work.
 * Advantages of proposed system:
  * The system is very simple in design and to implement. The system requires very low system resources and the system will work in almost all conﬁgurations. It has gotfollowing features 
     * Security of data.
     * Ensure data accuracy’s.
     * Proper control of the higher oﬃcials.
     * Reduce the damages of the machines.
     * Minimize manual data entry.
     * Minimum time needed for the various processing.
     * Greater eﬃciency.
     * Better service.
     * User friendliness and interactive.
   
## SWOT ANALYSIS
![image](https://user-images.githubusercontent.com/81503646/114817678-1540d800-9dd8-11eb-992c-a7f6263e62f6.png)


# 4W&#39;s and 1&#39;H

## Who:
* Banks use this system inorder to save time and cost.

## What:
* Bank management system can help the user to perform all the tasks like creating an account, deposit amount, withdraw amount, check balance, view all account holders details, close an account and modify an account.

## When:
* In banks there are huge number of customers whose data needs to be processed. The record of the customer can be added, updated, searched and deleted. It is based on a concept to generate and maintain daily payment transactions with the customer’s account. 

## Where:
* This problem can occur in different banking sectors all over the world.

## How:
* An effective bank management can help you derive maximum profits with minimum risks.

# Detail requirements
## High Level Requirements:
| ID | Description | Status | 
| ----- | ----- | ---------|
| HR01 | User shall be able to create new account | Implemented |
| HR02 | User shall be able to add account details of the customers | Implemented |
| HR03 | User shall be able to deposit cash | Implemented |
| HR04 | User shall be able to withdraw cash | Implemented |
| HR05 | User shall be able to display account information | Implemented |
| HR06 | User shall be able to search for an account | Implemented |
| HR07 | Data should not be lost in case of failure | Future |
| HR08 | Data should always be stored when closing the system | Implemented |

##  Low level Requirements:
| ID | Description | HLR ID | Status (Implemented/Future)|
| ----- | --------- | ------| ------ |
| LR01 | User can login to the system and manage all the functionalities of banking management | HR01 | Implemented  |
| LR02 | User can be able to login only if the password is 10 characters long | HR02 |  Implemented |
| LR03 | If user searches for an invalid ID "No Record Found" message should be displayed | HR01, HR02 |  Implemented  |
| LR04 | User can search the details of an account, if account is found else "Record not found" will be printed.  | HR06 |  Implemented  |
| LR05 | If opening the file fails, then the system shloud prompt the message "Unable to access file" and should not end the program execution | HR06 |  Implemented  |
| LR05 | When user logs off the system perform check and save data to file (1). If new data in inserted add it to file (2). If New data is not inserted do not add anything to file | HR08 |  Implemented  |
