# Event Booking Backend

## Overview

The Event Booking Backend is a RESTful API built with FastAPI for managing events, users, tickets, and payments. It serves as the backend for the Event Booking System, allowing event organizers to create and manage events and attendees to book tickets.

## Features

- User authentication and authorization
- Event creation and management
- Ticket booking and seat management
- Payment processing integration
- API documentation with Swagger UI

## Getting Started

### Prerequisites

- Python 3.8 or higher
- PostgreSQL
- pip (Python package installer)

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/event-booking-backend.git
   cd event-booking-backend

   ```

2. Create and activate a virtual environment:

   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows, use `venv\Scripts\activate`

   ```

3. Install the dependencies:

   ```bash
   pip install -r requirements.txt
   ```

4. Start the server:

   ```bash
   uvicorn app.main:app --reload
   ```

   The API will be available at http://localhost:8000.

### API Documentation

- Swagger UI: http://localhost:8000/docs
- ReDoc: http://localhost:8000/redoc

### License

This project is licensed under the Custom License.

### Contact

For questions or support, contact Devin Barboza at devin.barboza12@gmail.com.
