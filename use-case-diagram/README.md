Use Case Diagram for Airbnb Clone Backend

📜 Overview
This directory contains the Use Case Diagram for the Airbnb Clone Backend project. The diagram visualizes the interactions between users and the system, focusing on the core features and functionalities. By understanding these interactions, we aim to clarify the roles of various actors and their relationships with the system's functionalities.

🎯 Objective
The use case diagram helps to:

Illustrate how different users interact with the system.
Identify key functionalities required for the Airbnb Clone backend.
Provide a clear understanding of system boundaries and interactions.

🔑 Actors and Use Cases
Actors
Guest: A user searching for and booking properties.
Host: A user listing properties for rental.
Admin: An administrator managing users, properties, bookings, and payments.
Payment Gateway: An external service for processing payments.

Primary Use Cases
For Guest
Register (Includes: Verify Email)
Login
Search Properties (Includes: Filter Results, View Property Details)
Create Booking (Includes: Validate Availability, Extends: Apply Discount)
Cancel Booking (Includes: Check Cancellation Policy)
Process Payment (Includes: Select Payment Method)
Leave Review (Extends: Rate Host)
Receive Notifications (Includes: Booking Confirmation, Payment Status Updates)

For Host
Register (Includes: Verify Email)
Login
Add/Edit Property (Includes: Upload Images, Add Amenities)
Track Booking Status (Includes: View Pending Bookings, Confirm/Reject Bookings)
Handle Payout (Includes: Configure Payout Method)

For Admin
Monitor/Manage Users
Monitor/Manage Listings
Monitor/Manage Bookings
Monitor/Manage Payments

For Payment Gateway
Process Payment (Includes: Validate Payment Method)
Handle Payout (Includes: Issue Payment)