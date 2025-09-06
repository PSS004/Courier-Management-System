

# 📦 Courier Management System – Java & MySQL Project

This project is a **Courier Management System** built using **Java Swing** with **MySQL** database connectivity. It allows users to manage courier bookings, track deliveries, and view records efficiently through a GUI interface.

---

## ✅ Features

* ➕ **Add Courier** – Add new courier details (sender, receiver, package info, date, etc.).
* 📨 **Update Courier** – Modify courier details before dispatch.
* 📦 **Track Courier** – Search and view courier status using tracking ID.
* ❌ **Delete Courier** – Remove courier record from the system.
* 📜 **View All Couriers** – Display all courier records in a table format.
* 🔍 **Filter/Search** – Filter courier records by sender, receiver, or date.
* 🖥️ **GUI Interface** – User-friendly Java Swing interface for easy interaction.
* 💾 **Database Integration** – MySQL database for storing courier information.

---

## 🧠 Data Structures & Java Concepts Used

| Data Structure / Concept     | Use Case                                                     |
| ---------------------------- | ------------------------------------------------------------ |
| `ArrayList` / `Vector`       | Store courier objects temporarily before saving to DB        |
| `HashMap` / `Hashtable`      | Fast lookup of courier info (optional)                       |
| `Java Swing Components`      | GUI elements: `JTable`, `JTextField`, `JButton`, `JComboBox` |
| `JDBC` / `PreparedStatement` | Database connection, CRUD operations                         |
| `Comparator` & `Iterator`    | Sorting and iterating through collections                    |

---

## 📂 File Structure

```
CourierManagementSystem/
├── src/
│   ├── Main.java            # Launches the GUI
│   ├── DBConnection.java    # Database connectivity
│   ├── Courier.java         # Courier model class
│   ├── CourierDAO.java      # Database operations (CRUD)
│   └── GUI/
│       ├── MainFrame.java   # Main window
│       ├── AddCourierPanel.java
│       ├── ViewCourierPanel.java
│       └── UpdateCourierPanel.java
├── README.md
└── database/
    └── courierDB.sql        # MySQL DB setup script
```

---

## 🔧 Prerequisites

* Java 8 or higher installed
* MySQL server installed
* IDE (IntelliJ, Eclipse, NetBeans) or terminal
* MySQL database configured (`courierDB`)

---

## 🚀 Setup & Running

1. **Clone the Repository:**

```bash
git clone https://github.com/PSS004/Courier-Management-System.git
cd Courier-Management-System
```

2. **Import Database:**

* Open MySQL Workbench or phpMyAdmin
* Run `database/courierDB.sql` to create the database and tables

3. **Run the Project:**

* Open in your IDE and run `Main.java`, or compile & run from terminal:

```bash
javac src/*.java
java -cp src Main
```

4. **Using the App:**

* Use the GUI to add, view, update, or delete courier records.
* Couriers can be searched using sender/receiver names or tracking IDs.

---

## 📸 Sample Screenshots

*(Add screenshots of your Swing GUI here)*

* **Main Dashboard**
* **Add Courier Form**
* **View Courier Table**

---

## 🧪 Concepts Practiced

* Java Swing GUI programming
* JDBC for database operations
* Object-Oriented Programming (OOP)
* CRUD operations with MySQL
* Java Collections (`ArrayList`, `HashMap`)
* Comparator & Iterator usage

---

## ✅ Improvements You Can Add

* 🌐 Web version using JSP/Servlets or Spring Boot
* 📄 Export courier data to CSV or PDF
* 🔔 Email/SMS notifications for courier updates
* 📱 Mobile app interface for tracking
* 🔒 User authentication & roles (admin/user)

---

## Author

**Prasad S Sannamani**
Java Developer | Computer Science Student

---

I can also **add the screenshots and GIF workflow of your GUI** into the README for a fully professional GitHub presentation if you provide them.

Do you want me to do that next?
