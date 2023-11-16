# DSA-MINI-Project_2023
# Hotel Management System 

# CONTRIBUTORS:

1) **PES2UG22CS093 - Areeb Ahmed**
2) **PES2UG22CS062 - Amogh P**
3) **PES2UG22CS107 - Ashhad Asif Sayyed**

# Hotel Management System Readme

## Overview
This C program serves as a comprehensive Hotel Management System, designed to efficiently manage customer information, room allocation, room services, and billing. The program employs a menu-driven interface, offering users an array of options to interact with the system seamlessly.

### Features

1. **Customer Management:**
    - Users can input and manage customer details, including name, mobile number, and stay duration.
    - The program utilizes a linked list of customer structures to dynamically handle customer data.

2. **Room Allocation:**
    - Customers can be allotted rooms based on room types, including Standard, Deluxe, Family, and Suite.
    - The system employs a linked list of room structures to track available rooms and their respective charges.

3. **Room Services:**
    - Users can request room services such as breakfast, lunch, and dinner, each with its associated charges.
    - Room services are tracked using a linked list of food structures within the customer structure.

4. **Party Hall Booking:**
    - Customers have the option to book the party hall, with a corresponding charge.
    - Party hall bookings are also managed through the linked list of food structures.

5. **Billing System:**
    - The program generates detailed bills for customers, including room charges, selected services, and the total amount.
    - Billing information is displayed in a structured format.

6. **Display Functionality:**
    - Users can display the list of all customers and available rooms, providing an overview of the current hotel status.

### Data Structures

- **Customer Structure:**
    - Contains information about each customer, including name, mobile number, stay duration, room details, total charges, and a linked list of ordered food items.

- **Room Structure:**
    - Represents the different types of rooms available, storing information such as room number and charge per day.

- **Food Structure:**
    - Holds details about food items ordered by customers, including the type of food and associated charges.

### Program Execution Flow

1. **New Customer Entry:**
    - Users input customer information, creating a new customer structure.
    - The customer structure is added to the linked list of customers.

2. **Room Allocation:**
    - Users choose a room type for the customer, and the program assigns an available room of that type.
    - Room details and charges are updated in the customer structure.

3. **Room Services and Party Hall Booking:**
    - Customers can request additional services, such as room service or party hall booking.
    - Services are added to the linked list of food structures within the customer structure.

4. **Billing:**
    - The program calculates the total charges for the customer, including room charges and selected services.
    - A detailed bill is displayed for the user.

5. **Display Options:**
    - Users can choose to display the list of all customers and available rooms.

### Important Notes:
- The program provides a simulated hotel management experience and is designed for educational purposes.
- It uses linked lists to efficiently manage dynamic data such as customer information, room availability, and ordered food items.

Feel free to explore and modify the code according to educational or personal requirements. Keep in mind that this program is a basic simulation and may require additional enhancements for practical use in real-world scenarios.
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

## Closing Note

Explore the realms of hotel management in a dynamic, interactive environment with this C program. Immerse yourself in the intricacies of dynamic data structures and engaging features designed for educational exploration. This project invites you to delve into the fascinating world of computer science and programming, offering a hands-on experience in hotel management simulation. Happy coding!
