# **Use Case Diagram for Airbnb Clone Backend**

## 📜 Overview  
This directory contains the Use Case Diagram for the **Airbnb Clone Backend** project. The diagram visualizes the interactions between users and the system, highlighting the core features and functionalities. By mapping these interactions, we aim to clarify the roles of various actors and their relationships with the system's capabilities.

---

## 🎯 Objective  
The Use Case Diagram serves the following purposes:  
- **Illustrate** how different types of users interact with the backend system.  
- **Identify** the key functionalities necessary for building the Airbnb Clone backend.  
- **Define** system boundaries and describe user interactions with various components.  

---

## 🔑 Actors and Use Cases  

### **Actors**
1. **Guest**: A user searching for and booking properties.  
2. **Host**: A user listing properties for rental.  
3. **Admin**: An administrator responsible for managing users, properties, bookings, and payments.  
4. **Payment Gateway**: An external service used to process payments securely.  

---

### **Primary Use Cases**  

#### **For Guest**
1. **Register** (Includes: Verify Email)  
2. **Login**  
3. **Search Properties** (Includes: Filter Results, View Property Details)  
4. **Create Booking** (Includes: Validate Availability; Extends: Apply Discount)  
5. **Cancel Booking** (Includes: Check Cancellation Policy)  
6. **Process Payment** (Includes: Select Payment Method)  
7. **Leave Review** (Extends: Rate Host)  
8. **Receive Notifications** (Includes: Booking Confirmation, Payment Status Updates)  

---

#### **For Host**
1. **Register** (Includes: Verify Email)  
2. **Login**  
3. **Add/Edit Property** (Includes: Upload Images, Add Amenities)  
4. **Track Booking Status** (Includes: View Pending Bookings, Confirm/Reject Bookings)  
5. **Handle Payout** (Includes: Configure Payout Method)  

---

#### **For Admin**
1. **Monitor/Manage Users**  
2. **Monitor/Manage Listings**  
3. **Monitor/Manage Bookings**  
4. **Monitor/Manage Payments**  

---

#### **For Payment Gateway**
1. **Process Payment** (Includes: Validate Payment Method)  
2. **Handle Payout** (Includes: Issue Payment)  

---