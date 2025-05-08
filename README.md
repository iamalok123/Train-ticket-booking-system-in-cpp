# Train Booking System

A C++ based train booking system that allows users to book train tickets with basic user management and booking functionality.

## Features

- User registration and management
- Train booking functionality
- Seat management system
- JSON-based data persistence
- Command-line interface

## Prerequisites

- Windows Subsystem for Linux (WSL) with Ubuntu installed
- C++17 compatible compiler (GCC/G++ recommended)
- Make build system
- Basic C++ development environment
- WSL Ubuntu terminal access

## Project Structure

```
.
├── entities/         # Contains entity classes (User, Vehicle, etc.)
├── service/         # Contains business logic and services
├── external/        # External dependencies
├── main.cpp         # Main application entry point
├── Makefile         # Build configuration
└── db.json          # Database file for storing application data
```

## Building the Project

1. Clone the repository:
```bash
git clone <repository-url>
cd <project-directory>
```

2. Build the project:
```bash
make
```

## Running the Application

After building, run the application:
```bash
./booking_system
```

## Usage

1. When prompted, enter your:
   - User ID
   - Name
   - Aadhar Card Number

2. Select option 1 to book a train

3. Enter the following details:
   - Train ID
   - Train Name
   - Source Station
   - Destination Station

## Future Enhancements

1. **User Authentication**
   - Implement secure login system
   - Password encryption
   - Session management

2. **Booking Features**
   - Multiple seat selection
   - Seat preference options
   - Booking cancellation
   - Booking modification

3. **Train Management**
   - Train schedule management
   - Multiple train routes
   - Fare calculation
   - Seat availability checking

4. **User Interface**
   - Graphical User Interface (GUI)
   - Web-based interface
   - Mobile application

5. **Additional Features**
   - Payment integration
   - Email notifications
   - Booking history
   - User profile management
   - Admin dashboard

