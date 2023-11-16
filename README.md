# DSA-MINI-Project
# Hotel Management System Readme

## Overview
This C program simulates a basic Hotel Management System. It provides users with the ability to manage customer information, allocate rooms, request room services, and generate bills. The program features a menu-driven interface with various options to interact with the system.

## How to Run the Code

1. **Compile the Code:**
    - Open a terminal or command prompt.
    - Navigate to the directory containing the source code file (`hotel_management.c`).
    - Compile the code using a C compiler. For example, using `gcc`:

        ```bash
        gcc hotel_management.c -o hotel_management
        ```

2. **Run the Executable:**
    - After a successful compilation, an executable file (`hotel_management` or `hotel_management.exe` on Windows) will be created.
    - Run the executable:

        ```bash
        ./hotel_management    # On Linux or macOS
        ```

        ```bash
        hotel_management.exe   # On Windows
        ```

3. **Interacting with the Program:**
    - Upon running the executable, the program will display a menu with several options.
    - Users can navigate through the features by entering the corresponding numbers as per the menu.

## Menu Options
1. **New Customer:**
    - Users can input details for a new customer, such as name, mobile number, and stay duration.

2. **Old Customer/Search:**
    - Allows searching for an existing customer based on their mobile number.

3. **Allot Room:**
    - Users can assign a room to a customer from available room types (Standard, Deluxe, Family, Suite).

4. **Room Service:**
    - Offers room service options, including breakfast, lunch, and dinner, with associated charges.

5. **Party Hall:**
    - Enables users to book the party hall or cancel a booking.

6. **CheckOut and Billing:**
    - Generates a detailed bill for the customer, including room charges and any additional services.

7. **Display:**
    - Shows a list of all customers and available rooms.

8. **Exit:**
    - Terminates the program.

## Example Usage:
1. **New Customer:**
    - Enter customer information, including name, mobile number, and stay duration.

2. **Allot Room:**
    - Choose a room type (Standard, Deluxe, Family, Suite) for the customer.

3. **Room Service:**
    - Add optional room services like breakfast, lunch, or dinner.

4. **Party Hall:**
    - Book the party hall or cancel the booking.

5. **CheckOut and Billing:**
    - Generate the bill, displaying room charges, selected services, and the total amount.

6. **Display:**
    - View a list of all customers and available rooms.

## Important Notes:
- Room charges and types are predefined in the code.
- The program utilizes linked lists for managing customer and room data.
- It uses basic console input/output and may not have a graphical interface.

## User Expectations:
- The program aims to provide a simple hotel management experience, allowing users to perform basic operations.
- Users can interact with the system to manage customer stays, allocate rooms, and request additional services.

Feel free to explore and modify the code according to educational or personal requirements. Keep in mind that this program is a basic simulation and may require additional enhancements for practical use in real-world scenarios.
