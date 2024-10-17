# Hotel Management System

A simple hotel management system built in C that allows a user to manage room bookings, customer records, and other related tasks. This project includes features for booking rooms, viewing, searching, editing, and deleting customer records.

## Table of Contents
- [Features](#features)
- [Requirements](#requirements)
- [Installation](#installation)
- [Usage](#usage)
- [File Structure](#file-structure)
- [Contributing](#contributing)
- [License](#license)

## Features

1. **Login System**
   - Username: `user`
   - Password: `pass`
   - Allows up to 3 login attempts; locks the user out after 4 failed attempts.
   - Password input is masked for security.

2. **Main Menu Options:**
   - **1. Book a Room**: Allows users to input customer details and save them to the system.
   - **2. View Customer Records**: Displays a list of all the customer records with their details.
   - **3. Delete Customer Record**: Deletes a customer record by room number.
   - **4. Search Customer Record**: Searches for and displays a customer record by room number.
   - **5. Edit Customer Record**: Allows editing customer details like name, address, etc.
   - **6. Exit**: Exits the program.

3. **Room Booking**
   - Store customer details such as:
     - Room number
     - Name
     - Address
     - Phone number
     - Nationality
     - Email
     - Period of stay
     - Arrival date
   - Saves these details in a file (`add.txt`).

4. **View Customer Records**
   - Displays a list of all current customer records from the file, showing details such as room number, name, and more.

5. **Delete Customer Record**
   - Deletes a customer’s record by room number, updating the file to reflect the changes.

6. **Search Customer Record**
   - Allows the user to search for a customer record by room number and displays the result if found.

7. **Edit Customer Record**
   - Allows users to modify an existing record by entering the room number. Users can edit details like name, address, etc.

## Requirements

- **Operating System**: Windows (due to the use of `windows.h` for console manipulation)
- **Compiler**: Any C compiler that supports standard libraries (`stdio.h`, `conio.h`, `stdlib.h`, `time.h`), and Windows-specific functions.
- **Libraries**:
  - `stdio.h`: For input/output operations
  - `conio.h`: For console input/output (e.g., `getch()`)
  - `stdlib.h`: For general utility functions (e.g., file handling)
  - `windows.h`: For Windows console functions (text color)
  - `time.h`: For displaying the current date and time

## Installation

1. Clone this repository to your local machine:
   ```bash
   git clone https://github.com/yourusername/hotel-management-system.git
