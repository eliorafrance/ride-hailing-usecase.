# ride-hailing-usecase.
# Ride-Sharing System Documentation

## Description
This ride-sharing system facilitates transportation by connecting passengers with drivers. It enables users to register, request rides, track their journeys, and make payments efficiently. Administrators manage the overall system operations, ensuring a seamless experience for both drivers and passengers while handling disputes and monitoring rides.

## Actors and Responsibilities

### 1. **Passenger**
- **Responsibilities**:
  - Register an account and log in.
  - Request rides and track ride status.
  - Make payments for rides.
  - Rate drivers and view ride history.

### 2. **Driver**
- **Responsibilities**:
  - Register an account and log in.
  - Accept or decline ride requests.
  - Update availability status.
  - Complete rides and view earnings.
  - Rate passengers.

### 3. **Administrator**
- **Responsibilities**:
  - Monitor rides and handle disputes.
  - Verify drivers and set pricing.
  - Generate reports on system performance and usage.

### 4. **Payment System**
- **Responsibilities**:
  - Process payments made by passengers for rides.

## Use Cases

### UC1: Register Account
**Actors**: Passenger, Driver  
**Description**: Users can create an account by providing necessary personal information.

### UC2: Login
**Actors**: Passenger, Driver, Admin  
**Description**: Users can log into their accounts using their credentials.

### UC3: Request Ride
**Actors**: Passenger  
**Description**: Passengers can request a ride from their current location to a specified destination.

### UC4: Track Ride
**Actors**: Passenger  
**Description**: Passengers can view the current status and location of their requested ride.

### UC5: Make Payment
**Actors**: Passenger, Payment System  
**Description**: Passengers can pay for their rides through secure payment methods.

### UC6: Rate Driver
**Actors**: Passenger  
**Description**: After completing a ride, passengers can rate their driver based on their experience.

### UC7: View Ride History
**Actors**: Passenger  
**Description**: Passengers can view a history of all their completed rides.

### UC8: Accept/Decline Ride
**Actors**: Driver  
**Description**: Drivers can choose to accept or decline ride requests based on their availability.

### UC9: Update Availability
**Actors**: Driver  
**Description**: Drivers can update their status to available or unavailable for rides.

### UC10: Navigate to Passenger
**Actors**: Driver  
**Description**: Drivers can navigate to the passenger's location after accepting a ride request.

### UC11: Complete Ride
**Actors**: Driver  
**Description**: Drivers can mark a ride as complete once the passenger has reached their destination.

### UC12: View Earnings
**Actors**: Driver  
**Description**: Drivers can view their earnings from completed rides.

### UC13: Rate Passenger
**Actors**: Driver  
**Description**: After completing a ride, drivers can rate their passengers.

### UC14: Monitor Rides
**Actors**: Admin  
**Description**: Administrators can monitor ongoing rides for safety and efficiency.

### UC15: Handle Disputes
**Actors**: Admin  
**Description**: Administrators can resolve disputes between drivers and passengers.

### UC16: Verify Drivers
**Actors**: Admin  
**Description**: Administrators can verify the credentials and background of drivers before they can accept rides.

### UC17: Generate Reports
**Actors**: Admin  
**Description**: Administrators can generate reports on system metrics, including ride statistics and user feedback.

### UC18: Set Pricing
**Actors**: Admin  
**Description**: Administrators can set and adjust pricing for rides based on various factors.
