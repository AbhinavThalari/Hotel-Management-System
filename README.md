#  Hotel Management System (C Program)

##  Overview
This is a **simple Hotel Management System** implemented in the **C programming language**.  
It allows a hotel administrator to:
- View the list of all rooms and their booking status  
- Book a room for a guest  
- Check out a guest from a booked room  

The system uses a structure array to store room data, making it an excellent learning project for understanding **structures, arrays, strings, and user interaction** in C.

---

##  Features
-  **View All Rooms** – Display room numbers, availability, and guest names  
-  **Book a Room** – Assign a guest name to an available room  
-  **Check Out** – Free a booked room and mark it as available  
-  **Menu Interface** – Simple, command-line driven program  

---

##  Code Structure

| Function | Description |
|-----------|--------------|
| `initializeRooms()` | Initializes all rooms with default values (not booked) |
| `displayRooms()` | Displays all rooms with booking status and guest names |
| `bookRoom()` | Books an available room for a guest |
| `checkOut()` | Checks out a guest and frees up the room |
| `main()` | Handles the main menu and user input loop |

---

##  Data Structure

```c
struct Room {
    int roomNumber;
    int isBooked;
    char guestName[50];
};


