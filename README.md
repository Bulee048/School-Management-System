# 🎓 Academix - Smart School Management System

![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![JSP](https://img.shields.io/badge/JSP-007396?style=for-the-badge&logo=java&logoColor=white)
![Servlet](https://img.shields.io/badge/Servlet-007396?style=for-the-badge&logo=java&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![Bootstrap](https://img.shields.io/badge/Bootstrap-7952B3?style=for-the-badge&logo=bootstrap&logoColor=white)

**Academix** is a comprehensive, OOP-based School Management System designed to streamline administrative tasks, enhance communication between teachers and students, and manage school finances efficiently. Built using Java web technologies, it offers a robust and scalable solution for modern educational institutions.

---

## 🚀 Key Features

### 👤 Admin Module
- **User Management**: Full CRUD (Create, Read, Update, Delete) operations for Admins, Teachers, and Students.
- **System Oversight**: Monitor and manage the entire school ecosystem from a centralized dashboard.
- **Data Integrity**: Ensure secure and organized storage of all school-related data.

### 👨‍🏫 Teacher Module
- **Classroom Management**: Manage student information and academic progress.
- **Notice Board**: Create and publish important announcements and updates.
- **Dashboards**: Access teacher-specific tools and statistics.

### 🎓 Student Module
- **Personal Dashboard**: View grades, announcements, and personal information.
- **Results Viewing**: Access exam results and academic performance history.
- **Profile Management**: Update personal details and track progress.

### 💰 Finance & Payments
- **Transaction Tracking**: Manage school income and expenses.
- **Payment Gateway**: Secure handling of student payments and card management.
- **Financial Reporting**: Generate statistics on school revenue and spending.

### 📋 Notice & Syllabus Management
- **Announcement System**: Real-time updates for school notices.
- **Curriculum Tracking**: Manage syllabi and collect ratings/feedback.

---

## 🛠️ Technology Stack

- **Backend**: Java (JSP & Servlets)
- **Frontend**: HTML5, CSS3, JavaScript, Bootstrap 5
- **Database**: MySQL
- **Tools**: JDBC (Java Database Connectivity), OOP Principles

---

## ⚙️ Installation & Setup

### Prerequisites
- **JDK 8 or higher**
- **Apache Tomcat 9.0+**
- **MySQL Server**
- **IDE** (Eclipse, IntelliJ, or VS Code with Java extensions)

### 1. Database Configuration
1. Open your MySQL client (Workbench or terminal).
2. Import the main database schema:
   ```sql
   source fullDB.sql
   ```
3. Import the finance-specific data:
   ```sql
   source database/finance.sql
   ```
4. Update the database credentials in `src/main/java/com/school/Utils/DBConnect.java` (or equivalent utility files).

### 2. Project Setup
1. Clone this repository:
   ```bash
   git clone https://github.com/Bulee048/School-Management-System.git
   ```
2. Import the project into your IDE as a **Dynamic Web Project**.
3. Add the **MySQL Connector JAR** to your project's build path/libraries.
4. Configure your Server (Tomcat) and add the project to the server deployment.

---

## 📂 Project Structure

```text
OOP2-main/
├── src/main/java/com/school/
│   ├── Controller/    # Servlets for handling requests
│   ├── Model/         # Data models and POJOs
│   └── Utils/         # Database connection and utility classes
├── src/main/webapp/
│   ├── css/           # Stylesheets for all modules
│   ├── images/        # Static assets and icons
│   ├── gift/          # Multimedia assets (Video backgrounds)
│   ├── WEB-INF/       # Web configuration (web.xml)
│   └── *.jsp          # Dynamic web pages (Login, Dashboards, etc.)
├── fullDB.sql         # Core database schema
└── database/          # Additional SQL scripts
```

---

## 🤝 Contributing

Contributions are welcome! Feel free to fork the repository and submit pull requests.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

---

## 📞 Contact

**Project Developer** - [Bulee048](https://github.com/Bulee048)  
Project Link: [https://github.com/Bulee048/School-Management-System](https://github.com/Bulee048/School-Management-System)

---
*Created with ❤️ for better school management.*
