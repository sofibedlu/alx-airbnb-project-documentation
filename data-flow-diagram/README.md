# Data Flow Diagram (DFD) for Airbnb Clone Backend

This directory contains the Data Flow Diagram (DFD) illustrating the flow of data within the backend system of the Airbnb Clone project.
The DFD provides a visual representation of how key entities, processes, and data stores interact to support the core functionalities of the application.

---

## 📄 Overview

The Airbnb Clone backend is designed to handle various features such as user management, property listings, booking management, and payment processing.
The DFD helps to map the movement of data between users, processes, and storage systems, providing a clear understanding of backend operations.

---

## 🖼️ Data Flow Diagram

The DFD visualizes the interaction of:
1. **External Entities**:
   - `User`: Represents guests, hosts, and admins interacting with the system.
   - `Payment Gateway`: Handles secure payment transactions (e.g., Stripe, PayPal).
   - `Email Service`: Sends email notifications (e.g., SendGrid, Mailgun).

2. **Processes**:
   - `User Management`: Handles user registration, login, and profile updates.
   - `Property Listings`: Manages the creation, editing, and deletion of property details.
   - `Search and Filtering`: Enables users to search and filter properties by various criteria.
   - `Booking Management`: Handles booking requests, validations, and cancellations.
   - `Payment Processing`: Manages secure payment transactions.
   - `Reviews and Ratings`: Captures and manages user reviews and host responses.
   - `Notifications System`: Sends booking confirmations and updates via email.

3. **Data Stores**:
   - `Users Table`: Stores user details (guests, hosts, admins).
   - `Properties Table`: Maintains property listing details.
   - `Bookings Table`: Tracks booking statuses and details.
   - `Payments Table`: Logs payment transactions.
   - `Reviews Table`: Stores user reviews and ratings.

---

## 🔀 Data Flow Description

### **Entities → Processes**
- Users send data like registration details, search criteria, or booking requests to the backend processes.

### **Processes → Data Stores**
- Processes interact with data stores to save, retrieve, or update information such as user profiles, property details, and booking statuses.

### **Processes → External Entities**
- Notifications and confirmations are sent back to users via the Notifications System and Email Service.
- Payment Processing interacts with Payment Gateways for secure transactions.

---