
# 🚑 Ambulance Booking System (C Language)

## Ahmedabad Online Ambulance Booking Servicing System

A console-based Ambulance Booking System developed using the C programming language.  
This project simulates an online ambulance booking service where users can book an ambulance, receive a unique token number, and check booking status using their registered mobile number.

---

## 📌 Project Description

The Ambulance Booking System is a menu-driven C application designed to manage ambulance bookings efficiently.  
The system stores booking data in memory using structures and arrays and performs proper input validation to ensure accurate information.

The application automatically:
- Generates a unique token number
- Assigns a random ambulance status
- Allows users to check booking details later using a mobile number

This project is suitable for BCA students, beginners in C programming, and academic mini-projects.

---

## 🛠️ Technologies Used

### Programming Language
- C

### Header Files
- stdio.h  
- stdlib.h  
- string.h  
- ctype.h  
- time.h  

### Concepts Used
- Structures
- Arrays
- Functions
- Menu-driven programming
- Input validation
- Random number generation
- Loops and conditional statements

---

## ✨ System Features

- Book an ambulance with patient details
- Auto-generated unique token number
- First name and last name validation
- Mobile number validation (exactly 10 digits)
- Disease / medical condition validation
- Random ambulance status assignment:
  - Available
  - On the Way
  - Busy
- Search booking using mobile number
- Handles invalid menu input
- Maximum booking limit (100 bookings)

---


## 🧾 Booking Information Stored

| Field Name          | Description                     |
|---------------------|---------------------------------|
| Token Number        | Auto-generated unique number    |
| First Name          | Patient's first name            |
| Last Name           | Patient's last name             |
| Mobile Number       | 10-digit contact number         |
| Disease/Condition  | Medical issue description       |
| Ambulance Status   | Current ambulance status        |

---

## 🔄 Program Flow

1. Display main menu
2. User selects an option
3. If Book Ambulance:
   - Collect patient details
   - Validate inputs
   - Generate token number
   - Assign random status
   - Display booking confirmation
4. If Check Status:
   - Ask for mobile number
   - Search booking
   - Display booking details
5. If Exit:
   - Terminate the program

---

## ▶️ How to Compile and Run

### Compile
```

gcc ambulance_booking_system.c -o ambulance

```

## 📂 Project Structure

```

Ambulance_Booking_System/
│
├── ambulance_booking_system.c
└── README.md

```

---

## 🧪 Sample Output

```

===========================================================
BOOKING CONFIRMATION
====================

Token Number        : 1
First Name          : Rahul
Last Name           : Sharma
Mobile Number       : 9876543210
Disease/Condition   : Accident
Current Status      : On the Way
================================

Your booking has been confirmed!

```

---

## 🧠 Learning Outcomes

- Understanding structures and arrays in C
- Implementing input validation
- Creating menu-driven applications
- Using random number generation
- Solving real-world problems using C

---

## 🚀 Future Enhancements

- File handling for permanent storage
- Location-based ambulance allocation
- Emergency priority system
- Admin management module
- Multi-city support

---

## 👨‍💻 Author

Name: Divyesh Modhvadiya  
Course: BCA   
Programming Language Used : C  

---



