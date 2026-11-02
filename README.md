# hotel-reservation-application
A Java-based hotel reservation system that allows customers to search for available rooms, create accounts, book rooms, and manage reservations through a CLI. Built using OOP principles, Java Collections, and layered architecture.

A Java-based command-line hotel reservation system that allows customers to search for available rooms, create accounts, book rooms, and view their reservations.

The project demonstrates core Java concepts including Object-Oriented Programming (OOP), Java Collections, interfaces, inheritance, encapsulation, and layered application architecture.

## ✨ Features

### Customer Features
- Create a customer account
- Search for available hotel rooms
- Reserve available rooms
- View existing reservations
- Search rooms based on check-in and check-out dates

### Admin Features
- View all customers
- View all hotel rooms
- View all reservations
- Add new rooms to the hotel

## 🏗️ Application Architecture

The application follows a layered architecture:

CLI → Resources → Services → Data Models

### 1. User Interface
Provides command-line menus for customers and administrators.

- `MainMenu`
- `AdminMenu`

### 2. Resources
Acts as the API between the user interface and service layer.

- `HotelResource`
- `AdminResource`

### 3. Services
Contains the application's business logic and manages in-memory data.

- `CustomerService`
- `ReservationService`

### 4. Data Models
Represents the application's main domain objects.

- `Customer`
- `IRoom`
- `Room`
- `FreeRoom`
- `Reservation`
- `RoomType`

## 📁 Project Structure

hotel-reservation-application/
│
└── src/
    ├── api/
    │   ├── AdminResource.java
    │   └── HotelResource.java
    │
    ├── model/
    │   ├── Customer.java
    │   ├── FreeRoom.java
    │   ├── IRoom.java
    │   ├── Reservation.java
    │   ├── Room.java
    │   └── RoomType.java
    │
    ├── service/
    │   ├── CustomerService.java
    │   └── ReservationService.java
    │
    └── ui/
        ├── MainMenu.java
        └── AdminMenu.java

## 💻 Technologies Used

- Java
- Object-Oriented Programming (OOP)
- Java Collections
- Java CLI
- Interfaces and Inheritance
- Exception Handling

## 🧠 Java Concepts Demonstrated

This project demonstrates:

- **Encapsulation** – Model data is managed through classes and methods.
- **Abstraction** – Interfaces such as `IRoom` define common room behavior.
- **Inheritance** – Specialized room types can extend base room functionality.
- **Polymorphism** – Different room implementations can be handled through the same interface.
- **Collections** – Rooms, customers, and reservations are stored and managed in memory.
- **Layered Architecture** – UI, resources, services, and models are separated to improve maintainability.

## 🚀 How to Run

1. Clone the repository.
2. Open the project in a Java IDE such as IntelliJ IDEA, Eclipse, or VS Code.
3. Make sure a compatible JDK is installed.
4. Compile the Java source files.
5. Run the application's main class.
6. Use the command-line menu to interact with the application.

## 📋 Example Main Menu

Hotel Reservation Application

1. Find and reserve a room
2. See my reservations
3. Create an account
4. Admin
5. Exit

## 🔐 Admin Menu

Admin Menu

1. See all customers
2. See all rooms
3. See all reservations
4. Add a room
5. Back to Main Menu

## 🎯 Project Objective

The objective of this project is to build a functional hotel reservation system while applying fundamental Java programming concepts and good software design practices.

It focuses on separating responsibilities between application layers and using Java Collections for in-memory data management.

## 👩‍💻 Author

**Sneha Gajavelli**

Java Hotel Reservation Application
