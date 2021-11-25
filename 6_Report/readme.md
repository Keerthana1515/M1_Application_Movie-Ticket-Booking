# Mini Project
# Application_Movie Ticket Booking

Codacy | Code Quality | Unity | CI
------|----------|-------|--------------
|[![Codacy Badge](https://app.codacy.com/project/badge/Grade/3f974e6ad6764f4881ee91e9edb54348)](https://www.codacy.com/gh/Keerthana1515/M1_Application_Movie-Ticket-Booking/dashboard?utm_source=github.com&amp;utm_medium=referral&amp;utm_content=Keerthana1515/M1_Application_Movie-Ticket-Booking&amp;utm_campaign=Badge_Grade)| ![Code inspector CodeQuality](https://api.codiga.io/project/29933/score/svg)|[![Unit Testing - Unity](https://github.com/Keerthana1515/M1_Application_Movie-Ticket-Booking/actions/workflows/unity.yml/badge.svg)](https://github.com/Keerthana1515/M1_Application_Movie-Ticket-Booking/actions/workflows/unity.yml)|[![C/C++ CI - Build Status](https://github.com/Keerthana1515/M1_Application_Movie-Ticket-Booking/actions/workflows/cppcheck.yml/badge.svg)](https://github.com/Keerthana1515/M1_Application_Movie-Ticket-Booking/actions/workflows/cppcheck.yml)|
||![Code inspector CodeQuality](https://api.codiga.io/project/29933/status/svg)|

# Requirements
## Introduction
  The aim of the project is to provide information of the MOVIE TICKET BOOKING SYTEM to a customer to book  the tickets.The project has been developed to carry out process easily and quickly.The system enables the user to Book tickets,Cancel tickets,View all booking records

## Research
Cinemas help in contributing to our daily memories as they provide an essential part of our culture,going to cinemas has been the culture of almost all the families of today’s generation. It is a time when the family can spend some time altogether by stealing some hours from their busy schedule. Movie Ticket Booking System provides the customers facility to book tickets for a movie and to gather information about the movies and theaters.Customers can book ticket of his choice and may cancel a ticket

The main goal of our project is to provide various types of customer facilities, and provide good  customer service
   It should fulfill almost all the process requirements of booking a ticket

## Features
#### Booking tickets
#### Cancel tickets
#### Change ticket price(only admin)
#### View all booking records
## Benefits
### Movie Ticket Booking system provides wide range of benefit they are as follows
#### Provides flexibility
#### For better performance
#### User Friendly
#### Can Select the seats as per choice

### Defining Our System
### Explanation
Movie Ticket Booking System have few inbuilt features like
      Admin
    * Login 
    * Can Change Price of a Ticket.
    * Can View the Reserved Tickets.
    * Exit System.
      User
    * Login with Credatials.
    * View the Movies Avaliable.
    * Purchase a Ticket.
    * View the avaliable seats.
    * Cancel a Ticket.
    * Exit System.
   
## SWOT ANALYSIS
![SWOT Analysis](https://github.com/goutami8989/Stepin_Movie-Ticket-Booking-System/blob/main/1_Requirements/swot-analysis.PNG)

### 4W&#39;s and 1&#39;H

## Who
### * Theater

## What
*   To bulid a system to book ticket,cancel ticket,view reserverd seats,change price of ticket(only admin)

## When
*   When user wants to carry out the tasks quickly and this reduces manual work and saves time

## Where
*   This issue is in all parts of the world in theater where there is a lot of booking,cancellation of tickets happening in all the time

## How
*   By creating a system which will provide all the functionalities required,the booking of, cancelling of the tickes and other actions will be take more time and system needs more workers for these actions

### Detail requirements

## High Level Requirements 
| ID | Description | Category | Status | 
| ----- | ----- | ------- | ---------|
| HR01 | User shall be able to login to the system| Techincal | IMPLEMENTED | 
| HR02 | User shall be able to purchase a ticket | Techincal | IMPLEMENTED |
| HR03 | User shall be able to get summary of the ticket booked | Techincal | IMPLEMENTED |
| HR04 | User shall be able to cancel a ticket| Techincal | IMPLEMENTED |
| HR05 | User shall be able to view the reserved seats  | Techincal | IMPLEMENTED |

### Low level Requirements
 
| ID | Description | HLR ID | Status (Implemented/Future) |
| ------ | --------- | ------ | ----- |
|LR01|User shall be able to login to the system with correct login details|HR01|IMPLEMENTED|
|LR02|User need to book a ticket in a user entry mode|HR01|IMPLEMENTED|
|LR03| If appropriate login details are not entered a message is displayed-"wrong password" | HR01 | IMPLEMENTED |
|LR04 |Displaying the movies available  | HR02 | IMPLEMENTED |
|LR05| Admin can change the price for the movie| HR02|IMPLEMENTED|
|LR06 |If user specifies seat number which  is booked ,message appears that the seat is unavaliable  | HR05 | IMPLEMENTED |
|LR07 |Displaying the summary of the ticket booked  | HR03 |IMPLEMENTED|
<!--
Refernces Have refered google for some part of coding and information
-->

# Design

## High Level Design 
## * Architecture Design
![Architecture](https://github.com/goutami8989/Stepin_Movie-Ticket-Booking-System/blob/main/2_Architecture/highlevel.png)

## * Usecase Diagram
![UsecaseDiagram](https://github.com/goutami8989/Stepin_Movie-Ticket-Booking-System/blob/main/2_Architecture/Usecasehdl.png)

## Low Level Design 
## * Level0
![Level0](https://github.com/goutami8989/Stepin_Movie-Ticket-Booking-System/blob/main/2_Architecture/Level0.png)

## * Level1
![Level1](https://github.com/goutami8989/Stepin_Movie-Ticket-Booking-System/blob/main/2_Architecture/Level1.png)

# Implementation
## Folder Structure
Folder        | Description
--------------| ----------------------------------------------
`inc`         |  header files
`src`         | Source code files for solvinng Arthimetic operations
`test`        | All source code and data for testing purposes
`unity`       | Files for unit testing
`Documentaion` | Doxyfile and Makefile

# Test Plan and Test Ouput

| **Test ID** | **HLT ID** | **Description**                                              | **Exp IN** | **Exp OUT** | **Actual Out** |**PASS/FAIL**  |    
|-------------|-----|--------------------------------------------------------------|------------|-------------|----------------|------------------|
|  T_01|H_01| Provide required details for login to book a ticket| password| Successfully logined In | Successfully logined In| PASS |
|  T_02|H_01| When wrong password is entered| Password|  Entered Password is wrong | Entered Password is wrong | PASS |
|  T_03|H_02|Display the  details of movie available|  Enter choice | Display list | Display list | PASS |
|  T_04|H_02| Purchase a ticket for the movie available | enter choice | ThankYou for Booking Ticket | ThankYou for Booking Ticket| PASS |
|  T_05|H_03|  Summary of a ticket for purchased movie| enter choice | Booking ID,Customer name,Show Name,Hallno,Price | Booking ID,Customer name,Show Name,Hallno,Price| PASS |
|  T_06|H_04| Cancel a ticket   |ID number|  Your ticket is cancelled | Your ticket is cancelled | PASS |
|  T_07|H_03| Change the price of ticket (only admin) | password| Please enter new price | Please enter new price   | PASS |
|  T_08|H_03| Change the price of ticket after login (only admin) | enter new price -price|Price Updated Successfully | Price Updated Successfully  | PASS |
|  T_09|H_03|When wrong password is entered while Changing the price of ticket (only admin) | password | Entered Password is wrong  |  Entered Password is wrong |PASS |
|  T_10|H_05|To view the reserved ticke |password| summary of tickeT|summary of ticket | PASS |
|  T_11|H_05|When wrong password is entered to view the reserved ticket|Correct Password | Entered Password is wrongt|Entered Password is wrong | PASS |

### Screenshots
![screen](https://github.com/goutami8989/Stepin_Movie-Ticket-Booking-System/blob/main/5_Images/Image1-login%20page.PNG)
![screen](https://github.com/goutami8989/Stepin_Movie-Ticket-Booking-System/blob/main/5_Images/image2-user%20mode.PNG)
![screen](https://github.com/goutami8989/Stepin_Movie-Ticket-Booking-System/blob/main/5_Images/image3-user%20mode.PNG)
![screen](https://github.com/goutami8989/Stepin_Movie-Ticket-Booking-System/blob/main/5_Images/image3-usermode1.PNG)
![screen](https://github.com/goutami8989/Stepin_Movie-Ticket-Booking-System/blob/main/5_Images/image4-purchase%20ticket.PNG)
![screen](https://github.com/goutami8989/Stepin_Movie-Ticket-Booking-System/blob/main/5_Images/image5-details%20to%20purchase%20ticket.PNG)
![screen](https://github.com/goutami8989/Stepin_Movie-Ticket-Booking-System/blob/main/5_Images/image6-summary%20of%20ticket.PNG)
![screen](https://github.com/goutami8989/Stepin_Movie-Ticket-Booking-System/blob/main/5_Images/image7-purchase%20a%20ticket%201.PNG)
![screeh](https://github.com/goutami8989/Stepin_Movie-Ticket-Booking-System/blob/main/5_Images/image8-summary%20of%20a%20ticket1.PNG)
![screen](https://github.com/goutami8989/Stepin_Movie-Ticket-Booking-System/blob/main/5_Images/image9-booking%20same%20seatnum.PNG)
![screen](https://github.com/goutami8989/Stepin_Movie-Ticket-Booking-System/blob/main/5_Images/image10-booking%20same%20seatnum%20(alert%20msg).PNG)
![screen](https://github.com/goutami8989/Stepin_Movie-Ticket-Booking-System/blob/main/5_Images/image11-book%20other%20seat%20num1.PNG)
![screen](https://github.com/goutami8989/Stepin_Movie-Ticket-Booking-System/blob/main/5_Images/image12-cancelticket.PNG)
![screen](https://github.com/goutami8989/Stepin_Movie-Ticket-Booking-System/blob/main/5_Images/image13-summary%20of%20cancelticket.PNG)
![screen](https://github.com/goutami8989/Stepin_Movie-Ticket-Booking-System/blob/main/5_Images/image14-admin%20login.PNG)
![screen](https://github.com/goutami8989/Stepin_Movie-Ticket-Booking-System/blob/main/5_Images/image15-changeprice.PNG)
![screen](https://github.com/goutami8989/Stepin_Movie-Ticket-Booking-System/blob/main/5_Images/image15wrong%20login.PNG)












