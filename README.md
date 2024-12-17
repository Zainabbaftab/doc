# Online Bus Ticket Booking Platform

## Overview
The Online Bus Ticket Booking platform is a full-stack application designed to streamline the process of booking, managing, and tracking bus tickets. It includes separate functionalities for passengers, admins, and bus operators. The platform ensures a seamless experience from ticket booking to journey tracking, with real-time updates and efficient management of schedules and bookings.

---

## Features

### *Passenger Functionality:*
- Register, login, and manage personal profiles.
- Browse available buses, select seats, and book tickets.
- Track booking status in real-time.
- View booking history and provide feedback.

### *Admin Functionality:*
- Manage users (passengers and bus operators) and bus details.
- Monitor schedules and receive notifications for issues.
- Oversee bookings and update their status.
- Access platform-wide data for analytics and reporting.

### *Bus Operator Functionality:*
- View assigned bookings and update trip status.
- Manage bus details, routes, and schedules.
- Access trip history and passenger feedback.

---

## Technology Stack
- *Backend:* Node.js, Express.js
- *Frontend:* React.js, Tailwind CSS
- *Database:* MongoDB
- *Authentication:* JWT for secure role-based access control

---

## Requirement Analysis

### *Stakeholder Needs:*

#### *Passengers:*
- Easy registration and login.
- A user-friendly interface for browsing and booking tickets.
- Real-time updates on booking and journey status.

#### *Admins:*
- Tools for managing users, buses, and bookings.
- Schedule management with notifications for issues.
- Access to analytics and reports.

#### *Bus Operators:*
- A system to manage bus schedules and routes.
- Tools to view and update trip assignments.

### *Platform Requirements:*
- Secure authentication and role-based access control.
- Scalable backend to handle increasing users and bookings.
- Efficient schedule and booking management.

---

## Functional Requirements
- User registration and role-based authentication.
- CRUD operations for buses, users, and bookings.
- Real-time updates for booking and trip status.
- Schedule management with notifications.

## Non-Functional Requirements
- Scalability to accommodate growth.
- High availability and performance.
- Secure data handling.
- Intuitive UI/UX for all roles.

---

## API Documentation

### *Authentication Endpoints*

#### *Passenger Authentication:*
- POST /passenger-register: Register a new passenger.
- POST /passenger-login: Login for passengers.
- POST /passenger-logout: Logout from the platform.

#### *Bus Operator Authentication:*
- POST /operator-register: Register a new bus operator.
- POST /operator-login: Login for bus operators.
- POST /operator-logout: Logout from the platform.

#### *Admin Authentication:*
- POST /admin-register: Register a new admin.
- POST /admin-login: Login for admins.
- POST /admin-logout: Logout from the platform.

### *Bus Management Endpoints (Admin)*
- POST /create-bus: Add a new bus to the schedule.
- POST /update-bus: Update bus details.
- POST /delete-bus: Remove a bus from the schedule.
- GET /buses: Retrieve the list of buses.

### *Booking Management Endpoints*

#### *Passengers:*
- POST /book-ticket: Book a bus ticket.
- GET /bookings: View booking history.
- GET /booking-status/:id: Get the status of a specific booking.

#### *Admins:*
- GET /all-bookings: View all bookings.
- POST /update-booking-status: Update the status of a booking.

#### *Bus Operators:*
- GET /assigned-trips: View assigned trips.
- POST /update-trip-status: Update the status of a trip.

### *Schedule Management Endpoints*
- GET /schedule: View schedule details.
- POST /update-schedule: Update schedule details.

---

## Entity-Relationship Diagram (ERD)
![erd png](https://github.com/user-attachments/assets/f403d513-7139-4d8b-a9e9-81cbc04b3b9a)


## Data Flow Diagram (DFD)
![dfd png](https://github.com/user-attachments/assets/73744f3a-4c1b-40ef-90a8-ab3e6ed8b71b)


---

## Final Summary

The *Online Bus Ticket Booking Platform* is a robust full-stack solution for managing bus schedules, bookings, and operations. It offers role-based functionalities for passengers, admins, and bus operators, ensuring a smooth user experience and efficient management processes.

### *Key Highlights:*
- Real-time booking and journey tracking.
- Schedule management with issue notifications.
- Secure role-based authentication.
- Scalable architecture using Node.js, React.js, and MongoDB.

With its intuitive design and efficient backend, the platform ensures a seamless flow of operations, from ticket booking to trip completion.

---

*Thank You!*

This documentation provides a complete overview of the platform, including requirements, API endpoints, and system diagrams.
