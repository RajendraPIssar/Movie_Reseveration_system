# 🎬 Movie Reservation System

A Python-based movie ticket reservation system that allows users to browse movies, select seats, and manage bookings through a console-driven interface.

---

## 📋 Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Project Structure](#project-structure)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
  - [Running the Application](#running-the-application)
- [Usage](#usage)
- [System Design](#system-design)
- [Contributing](#contributing)
- [License](#license)

---

## Overview

The **Movie Reservation System** is a terminal-based application built in Python that simulates a real-world cinema booking workflow. Users can view available movies, choose showtimes, select seats, and confirm reservations — all through an interactive command-line interface.

This project demonstrates core Object-Oriented Programming (OOP) principles including encapsulation, class design, and state management.

---

## Features

- 🎥 Browse available movies and showtimes
- 💺 Interactive seat selection with availability tracking
- 🎟️ Ticket booking and reservation confirmation
- ❌ Reservation cancellation support
- 📋 View existing bookings
- 🔒 Basic input validation and error handling

---

## Project Structure

```
Movie_Reseveration_system/
└── Movie_reservation_system/
    └── *.py        # Core application modules
```

---

## Getting Started

### Prerequisites

- Python **3.7+**
- No external dependencies required (standard library only)

### Installation

```bash
# Clone the repository
git clone https://github.com/RajendraPIssar/Movie_Reseveration_system.git

# Navigate into the project directory
cd Movie_Reseveration_system/Movie_reservation_system
```

### Running the Application

```bash
python main.py
```

> **Note:** Replace `main.py` with the actual entry-point filename if different.

---

## Usage

1. Launch the application via terminal.
2. Select an option from the main menu (e.g., View Movies, Book Ticket, Cancel Reservation).
3. Follow the on-screen prompts to complete your booking.
4. Your reservation details will be displayed upon confirmation.

**Example interaction:**

```
===== Movie Reservation System =====
1. View Movies
2. Book a Ticket
3. Cancel Reservation
4. View My Bookings
5. Exit

Enter your choice: 2

Available Movies:
  [1] Inception       - 7:00 PM  | Seats Available: 45
  [2] Interstellar    - 9:30 PM  | Seats Available: 20
  [3] The Dark Knight - 6:00 PM  | Seats Available: 60

Select a movie: 1
Select your seat (e.g., A3): A3

Booking confirmed! 🎉
Movie: Inception | Seat: A3 | Time: 7:00 PM
```

---

## System Design

The system is built around the following core concepts:

| Component        | Responsibility                                      |
|-----------------|-----------------------------------------------------|
| `Movie`          | Stores movie metadata (title, genre, showtimes)    |
| `Seat`           | Tracks individual seat availability and status     |
| `Reservation`    | Links a user, movie, and seat into a booking       |
| `ReservationManager` | Handles CRUD operations on reservations        |
| `UI / Menu`      | Drives the interactive terminal interface          |

**Key OOP principles applied:**
- **Encapsulation** — seat state and booking logic are self-contained within classes
- **Abstraction** — the menu layer is decoupled from the business logic
- **Separation of Concerns** — data models are distinct from user interaction

---

## Contributing

Contributions are welcome! To contribute:

1. Fork the repository
2. Create a feature branch: `git checkout -b feature/your-feature`
3. Commit your changes: `git commit -m "Add your feature"`
4. Push to the branch: `git push origin feature/your-feature`
5. Open a Pull Request

Please ensure your code follows PEP 8 style guidelines.

---

## License

This project is open source and available under the [MIT License](LICENSE).

---

## Author

**Rajendra P. Issar**  
[GitHub Profile](https://github.com/RajendraPIssar)
