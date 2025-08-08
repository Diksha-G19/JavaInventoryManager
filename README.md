A Java-based desktop application designed to manage inventory efficiently using JFrames and developed in NetBeans IDE.
This system allows users to add, update, delete, and view inventory items, making stock management easy and streamlined.

**Features**
- User Authentication – Secure login system for authorized access.
- Category Management – Add, edit, and remove product categories.
- Product Management – Manage product details with ease.
- Customer Management – Store and update customer records.
- Order Management – Create and manage orders.
- View Orders – Check past orders and order history.
- User Management – Manage system users and their access rights.

**Project Structure**
| File Name                       | Description                      |
| ------------------------------- | -------------------------------- |
| `Login.java` / `.form`          | Login screen for authentication  |
| `Home.java` / `.form`           | Main dashboard after login       |
| `ManageCategory.java` / `.form` | Category management UI and logic |
| `ManageProduct.java` / `.form`  | Product management UI and logic  |
| `ManageCustomer.java` / `.form` | Customer management UI and logic |
| `ManageOrder.java` / `.form`    | Order creation and handling      |
| `ViewOrders.java` / `.form`     | Display order history            |
| `ManageUser.java` / `.form`     | Manage application users         |

**Technologies Used**
- Java (Swing & AWT) – For GUI development
- NetBeans IDE – For application development
- MySQL – For database storage and management
- JDBC – For database connectivity

**Prerequisites**
1. Install Java JDK (version 8 or higher)
2. Install NetBeans IDE
3. Install MySQL Server and MySQL Workbench

**Installation & Setup**
1. Clone the repository:
git clone https://github.com/yourusername/inventory-management-system.git
2. Open the project in NetBeans.
3. Import the SQL database script from the database folder into MySQL.
4. Update database credentials in the code (inside JDBC connection file).
5. Run the project.
