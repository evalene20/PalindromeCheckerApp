# Hotel Booking Management System  
**App-Based Learning Using Core Java & Data Structures**

## Overview
The Hotel Booking Management System is a console-based application built using Core Java, designed to demonstrate how fundamental data structures and object-oriented principles are applied in real-world software systems.

This project emphasizes practical learning by showing how theoretical concepts such as queues, sets, and maps solve real business problems like booking management, inventory tracking, and request handling.

---

## Objective
The primary goal of this project is to bridge the gap between academic concepts and real-world application development by:

- Applying Core Java concepts in a structured system
- Demonstrating the role of data structures in software design
- Building a scalable and maintainable booking system
- Simulating real-world challenges such as concurrency and data consistency

---

## Key Features

### 1. Fair Request Handling
- Implements FIFO (First-In-First-Out) using queue-based structures  
- Ensures booking requests are processed in the order they are received  

### 2. Real-Time Inventory Management
- Tracks room availability dynamically  
- Maintains consistency across booking and cancellation operations  

### 3. Prevention of Double Booking
- Uses uniqueness enforcement (e.g., sets/maps)  
- Ensures a room cannot be booked more than once for the same time slot  

### 4. Extensible System Design
- Modular and object-oriented architecture  
- Easy to extend with new features such as payment integration or UI layers  

---

## Learning Approach

This project follows an incremental development model:

- Each feature introduces a new concept
- Previously learned concepts are continuously reinforced
- Design evolves from simple implementations to more robust solutions

### Focus Areas
- Core Java (Classes, Objects, Encapsulation, Inheritance)
- Data Structures (Queue, HashMap, HashSet, List)
- Object-Oriented Design Principles
- Clean and Maintainable Code Practices

---

## Project Structure
hotel-booking-system/
│
├── src/
│ ├── model/ # Core entities (Room, Booking, User)
│ ├── service/ # Business logic
│ ├── util/ # Helper classes and utilities│ └── main/ # Entry point of the application
│
├── README.md
└── .gitignore


---

## Technologies Used

- Java (Core Java)
- Java Collections Framework
- Object-Oriented Programming Principles

---

## How It Works

1. Users request room bookings
2. Requests are queued and processed sequentially
3. System checks room availability
4. Booking is confirmed if constraints are satisfied
5. Inventory is updated in real time
6. Duplicate or conflicting bookings are prevented

---

## Scope & Limitations

- Console-based application (no graphical UI)
- No database integration (in-memory data handling)
- Single-user simulation (no real concurrency handling)

---

## Future Enhancements

- Add database support (JDBC / Hibernate)
- Implement REST APIs for integration
- Build a web or mobile UI
- Introduce multi-threading for concurrent booking handling
- Add payment and authentication modules

---

## Learning Outcome

By completing this project, you will:

- Understand how data structures are used in real applications
- Gain hands-on experience in designing scalable systems
- Learn when and why to use specific data structures
- Improve problem-solving and software design skills

---

## Getting Started

### Prerequisites
- Java JDK 8 or above
- Any IDE (IntelliJ IDEA, Eclipse, VS Code)

### Run the Project

```bash
# Compile
javac Main.java

# Run
java Main
