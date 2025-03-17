# Ticket Booking System

Welcome to the Ticket Booking System project! This Java-based application enables users to book tickets for various events, demonstrating a comprehensive implementation of object-oriented programming principles and software development skills.

## Project Overview

The Ticket Booking System is designed to allow users to:

- **Browse Events**: View a list of available events such as concerts, sports, and theater shows.
- **Search and Filter**: Search for events based on criteria like title, date, location, or genre.
- **View Event Details**: Access detailed information about specific events, including title, description, date, location, available seats, and ticket prices.
- **Book Tickets**: Reserve tickets for selected events by specifying the number of tickets and processing payments.
- **View Booking History**: Review past bookings with details of the events attended.

## System Architecture Diagram

Below is the system architecture diagram that represents the application's structure and flow:

<a href="https://ibb.co/S7XZtBsd"><img src="https://i.ibb.co/0VjzCrDF/Ticket-Booking-App-LLD.png" alt="Ticket-Booking-App-LLD" border="0"></a>

**Note:** The diagram will be updated as the project is enhanced.

## Project Structure

The project follows a modular structure to ensure scalability and maintainability:

```
TicketBookingSystem/
│
├── .github/workflows/       # GitHub Actions workflows
├── .idea/                   # IntelliJ IDEA project files
├── .vscode/                 # VSCode project settings
├── app/
│   └── src/
│       └── main/
│           └── java/
│               └── project/
│                   └── ticket/
│                       └── booking/
│                           ├── entities/
│                           │   ├── Ticket.java
│                           │   ├── Train.java
│                           │   └── User.java
│                           ├── services/
│                           │   ├── TrainService.java
│                           │   └── UserBookingService.java
│                           ├── util/
│                           │   └── UserServiceUtil.java
│                           └── App.java
├── gradle/                  # Gradle wrapper files
├── src/main/resources/localDb/  # Local database files
├── .gitattributes
├── .gitignore
├── gradlew
├── gradlew.bat
└── README.md
```

- **entities/**: Contains the core classes representing the main entities in the system, such as `Ticket`, `Train`, and `User`.
- **services/**: Includes service classes like `TrainService` and `UserBookingService` that handle the business logic.
- **util/**: Contains utility classes, such as `UserServiceUtil`, providing helper methods.
- **App.java**: The entry point of the application.

## How to Access and Run the Project

To set up and run the Ticket Booking System locally, follow these steps:

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/yashdesai023/TicketBookingProject.git
   ```
2. **Navigate to the Project Directory**:
   ```bash
   cd TicketBookingProject
   ```
3. **Build the Project**:
   Ensure you have [Gradle](https://gradle.org/) installed. Then, execute:
   ```bash
   ./gradlew build
   ```
4. **Run the Application**:
   After a successful build, run:
   ```bash
   java -cp build/libs/TicketBookingProject.jar project.ticket.booking.App
   ```

## Skills Demonstrated

This project showcases the following skills:

- **Java Programming**: Utilized Java to develop a robust ticket booking system, implementing object-oriented principles.
- **Software Design**: Designed a modular architecture to ensure scalability and maintainability.
- **Version Control**: Employed Git and GitHub for version control and collaboration.
- **Build Automation**: Used Gradle for building and managing project dependencies.
- **Database Management**: Implemented local database management for storing and retrieving booking information.

## Contact Information

For any inquiries or further information, feel free to reach out:

- **LinkedIn**: [Yash S. Desai](https://www.linkedin.com/in/yash-s-desai-/)
- **Email**: desaisyash1000@gmail.com

Thank you for exploring the Ticket Booking System project!

