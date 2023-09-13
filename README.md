# Project Title: Railway Reservation System

## Project Description:

👉The Railway Reservation System is a terminal-based application that allows users to book and manage railway tickets. This project uses Object Oriented Programming in java.

👉The project will consist of the following modules/Functionalities:

👉Create an ArrayList where available stations are - Delhi, Jaipur, Prayagraj, and Mumbai

### Project Should have below Functionalities- 

Train Information: This module will provide information about the available trains based on the source and destination stations and the date of travel
We just have 3 trains - 
| Train Name         | Time  | Passenger Strength | Train Number            |
| ------------------ | ----- | ------------------ | ------------------------|
| Mumbai - Delhi     | 13:05 | 50                 | 1010 (Mumbai Superfast) |
| Delhi - Jaipur     | 7:00  | 50                 | 2013 (Delhi SuperFast)  |
| Prayagraj - Delhi  | 10:00 | 50                 | 3045 (Prayagraj EXP)    |


**Seat Availability:** This module will check the availability of seats on the selected train and display the available seats to the user.

**Booking:** This module will allow users to book seats on the selected train, using information such as passenger names and seat numbers.

**Canceling:** The user Should have the option to Cancel the booked ticket

**Ticket Display:** This module will display the details of the booked ticket, including the passenger names, seat numbers, train numbers, and fares.

**Error Handling:** This module will handle any errors that may occur during the operation, such as invalid input or trying to book a seat already reserved.



# Short explanation of the Java code for an Online Railway Reservation System:

## Train Class
- The `Train` class represents a train and has the following attributes:
  - `name`: Name of the train route.
  - `time`: Departure time of the train.
  - `passengerStrength`: Maximum passenger capacity of the train.
  - `trainNumber`: Unique train identification number.

## ReservationSystem Class
- The `ReservationSystem` class manages the railway reservation system.
- It initializes two lists:
  - `availableTrains`: Contains predefined train data.
  - `bookedSeats`: Keeps track of booked tickets.
- Key methods in this class include:
  - `displayAvailableTrains()`: Displays information about available trains.
  - `checkSeatAvailability(int trainNumber)`: Checks seat availability for a specific train.
  - `bookTicket(int trainNumber, String passengerName)`: Books a ticket for a passenger on a specific train if seats are available.
  - `cancelTicket(String passengerName)`: Cancels a booked ticket for a passenger.
  - `displayBookedTickets()`: Displays a list of booked tickets.

## Main Class
- The `Main` class serves as the program's entry point.
- It creates instances of the `ReservationSystem` class and a `Scanner` for user input.
- The program runs in a loop, displaying a menu of options for users to choose from.
- Users can perform actions such as:
  - Displaying available trains.
  - Checking seat availability for a specific train.
  - Booking a ticket for a passenger on a specific train.
  - Canceling a booked ticket for a passenger.
  - Viewing a list of booked tickets.
  - Exiting the program.
- User input is processed, and the appropriate methods in the `ReservationSystem` class are called based on the user's choice.

This Java program provides a basic simulation of a railway reservation system, offering users the ability to interact with available trains, check seat availability, book and cancel tickets, and view booked tickets. The program continues to run until the user chooses to exit.


