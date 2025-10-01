📦 Courier Management System – Java Swing Application

This project simulates a courier management system using Java Swing with MySQL database connectivity. Users can manage courier bookings, track deliveries, update details, and view records through a user-friendly GUI interface.

✅ Features

➕ Add Courier – Add a new courier with sender, receiver, package info, date, and status.
✏️ Update Courier – Update details of an existing courier.
🚚 Track Courier – Track the courier status using tracking ID.
❌ Delete Courier – Remove a courier record from the system.
📜 View All Couriers – Display all courier records in a table format.
🔍 Filter/Search Couriers – Filter courier records by sender, receiver, or date.

🧠 Data Structures Used
Data Structure	Use Case
ArrayList	Store and manage courier records
HashMap	Quick lookup of couriers by ID or name
JTable / Swing Components	Display courier records in GUI
📂 File Structure
CourierManagementSystem/
├── Courier.java           # Courier model class
├── CourierManager.java    # Business logic and data handling
├── DatabaseConnection.java # MySQL DB connection setup
└── Main.java              # GUI interface and event handling

🔧 Prerequisites

Java 8 or higher installed

MySQL server running

IDE (VS Code, IntelliJ, Eclipse) or terminal

🚀 Steps to Run

Open the project folder in your IDE.

Configure MySQL connection in DatabaseConnection.java (update username, password, database name).

Run the SQL script (courier_db.sql) to create necessary tables.

Compile and run Main.java.

📸 Sample Run

Add Courier:

Enter sender: John
Enter receiver: Alice
Enter package info: Books
Enter date: 2025-10-01
Courier added successfully!


View All Couriers:

ID: 1, Sender: John, Receiver: Alice, Package: Books, Date: 2025-10-01, Status: Pending


Track Courier:

Enter courier ID: 1
Courier Status: Pending

📄 Concepts Practiced

Object-Oriented Programming (OOP)

Java Swing GUI development

MySQL database integration

CRUD operations (Create, Read, Update, Delete)

Event-driven programming

✅ Improvements You Can Add

GUI enhancements with JavaFX

File or database persistence for history logs

Email/SMS notifications for courier status

Multi-user authentication and role-based access

Reports generation (daily, weekly, monthly)

Author

Prasad S Sannamani
Java Developer | Computer Science Student
