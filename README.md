# Bus Ticket Booking App

## Problem Statement

You are tasked with developing a multi-threaded Java application for a Bus Ticket Booking System. The system handles the booking of bus tickets for various routes and allows multiple users to book tickets concurrently. The application is expected to handle thousands of requests per second, ensuring data consistency and avoiding conflicts.

1. Design a multi-threaded solution for the Bus Ticket Booking System. Consider the following requirements:

   a. Each bus route has a fixed number of available seats, and the system should prevent overbooking.
   b. Users can search for available buses, view available seats, and book tickets.
   c. When a user books a ticket, the system should reserve the seats for a specific time (e.g., 5 minutes) to complete the booking process.
   d. If a user doesn't complete the booking within the reservation time, the reserved seats should be released for others to book.
   e. The application should handle concurrent booking requests from multiple users without data corruption or inconsistency.

2. Implement synchronization mechanism.