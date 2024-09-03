# Flight Management System

## Overview

The **Flight Management System** is a C++ project that simulates the management of flights, passengers, and associated operations using Object-Oriented Programming (OOP) principles. This system is designed to handle various flight-related tasks such as scheduling, booking, and managing flight details, with a focus on modularity and code organization.

## Features

- **Flight Scheduling**: Create, manage, and update flight schedules, including departure and arrival times.
- **Passenger Management**: Register passengers, manage their bookings, and track their flight history.
- **Time and Date Handling**: Utilize custom classes for managing time (`RelojD.h`) and dates (`Fecha.h`) to ensure accurate scheduling.
- **Data Organization**: Code is organized into classes, each with a specific role, improving maintainability and readability.

## Project Structure

The project is composed of several header (`.h`) files and a main implementation file (`flighs.cpp`):

- **`Fecha.h`**: Handles date-related operations, including setting and comparing dates.
- **`Pasajero.h`**: Manages passenger information, such as names and flight bookings.
- **`RelojD.h`**: Manages time-related functionalities, particularly for scheduling flights.
- **`Vuelo.h`**: Contains the definition of the `Vuelo` class, which manages individual flight details.
- **`vuelA.h`**: Likely contains additional functionalities or variations of the `Vuelo` class, possibly for extended flight management.
- **`flighs.cpp`**: The main implementation file where the core logic of the flight management system is executed.

## Getting Started

### Prerequisites

- C++ Compiler (e.g., GCC)
- Basic understanding of C++ and Object-Oriented Programming (OOP) concepts
### Installation

1. Clone the repository:
2. git clone https://github.com/AlanCoronaaa/management-flighs.git
3.  Navigate to the project directory:
cd management-flighs
4. Compile the code:
g++ -o FlightManagement flighs.cpp
5. Run the application:
./FlightManagement


### Usage

Once the application is running, follow the prompts in the command-line interface to manage flights, passengers, and schedules. The system is designed to handle input errors gracefully and provide a user-friendly experience.

## Contributing

Contributions to improve this project are welcome. Feel free to fork the repository, submit issues, or make pull requests with enhancements or bug fixes.

## License

This project is open-source and available under the [MIT License](LICENSE).
