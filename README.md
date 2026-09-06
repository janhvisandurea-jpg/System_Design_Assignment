# Cinema Booking System

A simple **C++ based Cinema Booking System** designed to simulate the real-world process of booking movie tickets.
The system allows users to browse movies, select a show, choose available seats, calculate the total ticket price, select a payment method, and generate a booking confirmation.

##  Project Overview

The Cinema Booking System provides a console-based interface for managing movie ticket bookings.

The booking process follows this flow:

Movie Selection → Show Selection → Seat Selection → Price Calculation → Payment → Ticket Confirmation

This project was developed to understand how a real-world booking system can be designed and implemented using C++.

---

# Features

- 🎥 View available movies
- 🌐 Display movie language and duration
- 🕐 Select available show timings
- 🖥️ Select cinema screen
- 💺 View available seats
- 🎟️ Book multiple seats
- 💰 Automatic ticket price calculation
- 💳 Multiple payment options:
  - UPI
  - Card
  - Cash
- ✅ Booking confirmation
- 🧾 Generate a ticket containing:
  - Movie name
  - Screen
  - Show timing
  - Selected seats
  - Total amount
  - Payment status

---

#🛠️ Technologies Used

- **C++**
- **Object-Oriented Programming Concepts**
- **Data Structures**
- **Conditional Statements**
- **Loops**
- **Functions**
- **Console-based User Interface**

---

# System Workflow

```text
        ┌─────────────────────┐
        │        START        │
        └──────────┬──────────┘
                   │
                   ▼
        ┌─────────────────────┐
        │   View Movies       │
        └──────────┬──────────┘
                   │
                   ▼
        ┌─────────────────────┐
        │  Select Movie       │
        └──────────┬──────────┘
                   │
                   ▼
        ┌─────────────────────┐
        │  Select Show/Screen │
        └──────────┬──────────┘
                   │
                   ▼
        ┌─────────────────────┐
        │  View Available     │
        │      Seats          │
        └──────────┬──────────┘
                   │
                   ▼
        ┌─────────────────────┐
        │   Select Seats      │
        └──────────┬──────────┘
                   │
                   ▼
        ┌─────────────────────┐
        │ Calculate Total     │
        │      Amount         │
        └──────────┬──────────┘
                   │
                   ▼
        ┌─────────────────────┐
        │ Select Payment      │
        │       Method        │
        └──────────┬──────────┘
                   │
                   ▼
        ┌─────────────────────┐
        │ Generate Ticket &   │
        │ Confirm Booking     │
        └──────────┬──────────┘
                   │
                   ▼
        ┌─────────────────────┐
        │         END         │
        └─────────────────────┘
