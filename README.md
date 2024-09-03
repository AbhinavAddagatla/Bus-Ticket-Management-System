# Bus-Ticket-Management-System
## Overview
The Bus Ticket System is a Java-based project designed to manage bus ticketing operations, including issuing tickets, canceling them, and managing passenger information. The project is organized into several classes that encapsulate the core functionality and data structures required for the system. It demonstrates object-oriented principles like inheritance, encapsulation, and polymorphism.
## Features:
### Object-Oriented Design:

The project is designed with OOP principles, with classes representing real-world entities like buses, passengers, and tickets.
Inheritance is used to extend functionality (e.g., SeniorCitizen inherits from Passenger).
### Ticket Management:

Tickets can be issued and canceled, with validations to prevent duplicate tickets or exceeding bus capacity.
Tickets are linked to passengers, allowing detailed tracking of who is traveling on each bus.
### Passenger Management:

The system can manage different types of passengers, including special categories like senior citizens.
It can retrieve and filter passengers based on attributes like gender.
### Bus Management:

Buses are managed within the system, each with a unique identifier, source, and destination.
The system tracks all tickets issued for each bus.
### Exception Handling:

Custom exceptions like InvalidBusException, TicketAlreadyExistException, and TicketDoesNotPresentException are used to handle error conditions gracefully.
### Utility Classes:

TicketNoGenerator is a utility class used for generating unique ticket numbers, ensuring no duplication.
## Potential Enhancements:
### Persistence: 
Currently, the data is managed in-memory. Implementing a database layer would allow the system to persist data between sessions.
### User Interface: 
Adding a graphical or command-line interface would make the system more user-friendly.
### Reporting: 
Generate reports, such as lists of all passengers on a bus or ticket sales summaries.
#### This project provides a solid foundation for managing bus tickets in a simple system. It can be extended or adapted to more complex scenarios as needed.
