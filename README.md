# ☕ Advanced Java Programming Laboratory (ADJ Lab)

<p align="center">
  <img src="https://img.shields.io/badge/Java-17%2B-orange?style=for-the-badge&logo=openjdk" alt="Java">
  <img src="https://img.shields.io/badge/Database-MySQL-blue?style=for-the-badge&logo=mysql" alt="MySQL">
  <img src="https://img.shields.io/badge/Web-Servlets-green?style=for-the-badge" alt="Servlets">
  <img src="https://img.shields.io/badge/Server-Apache%20Tomcat-yellow?style=for-the-badge&logo=apachetomcat" alt="Tomcat">
</p>

<p align="center">
  <b>A comprehensive collection of Advanced Java laboratory experiments, practical implementations, and academic projects.</b>
</p>

---

## 📌 Overview

This repository contains practical implementations of Advanced Java concepts developed as part of the B.Tech Computer Science and Engineering curriculum.

The experiments cover GUI development, MVC architecture, TCP socket programming, JDBC database connectivity, distributed computing, and Java web application development.

## 📋 Table of Contents

- [Overview](#overview)
- [Objectives](#objectives)
- [Index of Experiments](#index-of-experiments)
- [Prerequisites and System Setup](#prerequisites-and-system-setup)
- [Experiment 1: Student Registration GUI](#experiment-1-student-registration-gui-form)
- [Experiment 2: MVC Calculator](#experiment-2-mvc-calculator-application)
- [Experiment 3: TCP Socket Programming](#experiment-3-tcp-socket-client-server-communication)
- [Experiment 4: JDBC Database Connectivity](#experiment-4-jdbc-database-connectivity)
- [Experiment 5: Swing and JDBC Integration](#experiment-5-swing-and-jdbc-integration)
- [Experiment 6: Java RMI](#experiment-6-java-rmi)
- [Experiment 7: Apache Tomcat](#experiment-7-apache-tomcat-deployment)
- [Experiment 8: Servlets, Filters and Listeners](#experiment-8-servlets-filters-and-listeners)
- [Experiment 9: BikeIsNice Capstone](#experiment-9-bikeisnice-capstone-project)
- [Getting Started](#getting-started)
- [Learning Outcomes](#learning-outcomes)
- [Author](#author)

---

## 🎯 Objectives

- Develop GUI applications using Java Swing and AWT.
- Understand the Model-View-Controller design pattern.
- Implement client-server communication using TCP sockets.
- Perform database operations using JDBC and MySQL.
- Integrate GUI applications with relational databases.
- Explore distributed computing using Java RMI.
- Deploy Java web applications using Apache Tomcat.
- Understand Servlets, sessions, filters, and listeners.

---

## 📑 Index of Experiments

| No. | Experiment Title | Core Technologies | Directory |
|:---:|---|---|---|
| 01 | Student Registration GUI Form | Swing, AWT, Event Handling | `exp1/` |
| 02 | MVC Calculator Application | Java Swing, MVC | `calc/` |
| 03 | TCP Client-Server Communication | Java Networking, Sockets | `server-client/` |
| 04 | JDBC Database Connectivity | JDBC, MySQL, SQL | `jdbc/` |
| 05 | Database-Integrated GUI | Swing, JDBC, MySQL | `strjdbc/` |
| 06 | Distributed Computing | Java RMI | `Remote-Method-Invocation/` |
| 07 | Web Server Setup and Deployment | Apache Tomcat | `apache-tomcat-9.0.121/` |
| 08 | Java Web Development | Servlets, Filters, Listeners | `servent/` |
| 09 | Cycling E-Commerce Capstone | Java, Web Technologies | `BikeIsNice/` |

*Verify directory names against the actual repository before running commands.*

---

## 🛠️ Prerequisites and System Setup

| Requirement | Recommended Version |
|---|---|
| Java Development Kit | JDK 17 or compatible |
| MySQL Server | 8.0+ |
| Apache Maven | 3.8+ |
| Apache Tomcat | Compatible version |
| IDE | IntelliJ IDEA or VS Code |
| Version Control | Git and GitHub |

Verify Java:

```bash
java -version
javac -version
```

Verify Maven:

```bash
mvn -version
```

---

## 🧪 Experiment 1: Student Registration GUI Form

### Aim
To create a student registration form using Java Swing and AWT.

### Concepts
- JFrame, JLabel and JTextField
- JRadioButton and JCheckBox
- JButton and ActionListener
- Input validation and JOptionPane

### Execution

```bash
cd exp1
javac StudentRegistration.java
java StudentRegistration
```

---

## 🧪 Experiment 2: MVC Calculator Application

### Aim
To implement a calculator using the Model-View-Controller architecture.

### Concepts
- Model: Arithmetic operations
- View: Calculator GUI
- Controller: Event handling
- Input validation and error handling

### Execution

```bash
cd calc
javac *.java
java Runmain
```

---

## 🧪 Experiment 3: TCP Socket Client-Server Communication

### Aim
To establish communication between a Java client and server using TCP sockets.

### Concepts
- ServerSocket and Socket
- Input and output streams
- Client-server communication
- Connection handling

### Execution

```bash
cd server-client
javac server.java client.java
```

Start the server in the first terminal:

```bash
java server
```

Run the client in another terminal:

```bash
java client
```

---

## 🧪 Experiment 4: JDBC Database Connectivity

### Aim
To connect Java applications to MySQL and perform database operations using JDBC.

### Concepts
- DriverManager and Connection
- PreparedStatement
- SQL queries
- ResultSet and database retrieval

### Example Database Setup

```sql
CREATE DATABASE IF NOT EXISTS college_db;
USE college_db;

CREATE TABLE IF NOT EXISTS Student (
    id INT PRIMARY KEY,
    name VARCHAR(100),
    branch VARCHAR(50)
);
```

Configure the JDBC driver, database URL, username and password according to the source code.

---

## 🧪 Experiment 5: Swing and JDBC Integration

### Aim
To develop a registration GUI that stores student details in a MySQL database.

### Concepts
- Swing form components
- JDBC connectivity
- SQL INSERT operations
- PreparedStatement and validation

Compile using the actual source and JDBC driver paths. Configure MySQL before executing the application.

---

## 🧪 Experiment 6: Java RMI

### Aim
To implement remote method invocation between Java client and server applications.

### Concepts
- Remote interfaces
- RemoteException
- RMI Registry
- Remote method invocation

### Execution

```bash
cd Remote-Method-Invocation
javac *.java
```

Start the RMI registry if required, then run the server and client in separate terminals using their actual class names.

---

## 🧪 Experiment 7: Apache Tomcat Deployment

### Aim
To understand web server configuration and Java web application deployment.

### Concepts
- Tomcat directory structure
- Server startup and shutdown
- WAR deployment
- Server configuration

### Windows

```powershell
cd apache-tomcat-9.0.121\bin
.\startup.bat
```

Open `http://localhost:8080/` in your browser.

To stop Tomcat:

```powershell
.\shutdown.bat
```

---

## 🧪 Experiment 8: Servlets, Filters and Listeners

### Aim
To develop a Java web application using Servlet API features.

### Concepts
- HTTP request and response handling
- Servlet mappings
- Session management
- Request filters
- Application lifecycle listeners
- Maven packaging

### Build

```bash
cd servent
mvn clean package
```

Deploy the generated WAR to a compatible Tomcat server. The application URL depends on its deployed context path.

---

## 🧪 Experiment 9: BikeIsNice Capstone Project

### Aim
To apply Advanced Java concepts in an integrated e-commerce project.

### Areas Covered
- Java application development
- Web application architecture
- Database integration
- Product and order management concepts
- Modular application design

### Build

```bash
cd BikeIsNice
mvn clean package
```

Check the project's own README and configuration for database setup and the correct startup procedure.

---

## 🚀 Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/pranaaykantiwal-sketch/java_lab_expirement.git
```

### 2. Navigate to the Project

```bash
cd java_lab_expirement
```

### 3. Open in Your IDE

Open the project in IntelliJ IDEA or Visual Studio Code.

### 4. Configure Dependencies

Install the required JDK, configure MySQL if needed, and set up the JDBC driver, Maven and Tomcat where applicable.

### 5. Run an Experiment

Navigate to the appropriate directory and follow its compilation and execution instructions.

---

## 🎓 Learning Outcomes

- Java GUI development using Swing and AWT.
- MVC architecture and code organization.
- TCP networking and client-server communication.
- JDBC and relational database operations.
- Distributed computing with Java RMI.
- Servlet-based web application development.
- Application deployment and configuration.
- Debugging and version control.

---

## 👨‍💻 Author

**Pranay Kantiwal**

- **Course:** B.Tech, Computer Science and Engineering
- **College:** Global Institute of Technology (GIT), Jaipur
- **GitHub:** [@pranaaykantiwal-sketch](https://github.com/pranaaykantiwal-sketch)
- **Repository:** [java_lab_expirement](https://github.com/pranaaykantiwal-sketch/java_lab_expirement)

---

## 🎓 Academic Purpose

This repository is maintained for educational purposes, laboratory practice, and learning Advanced Java programming concepts.

*Verify source filenames, directory paths, database configuration and dependencies before executing commands.*

<p align="center">
  <b>Built with Java ☕</b><br>
  <sub>Advanced Java Programming Laboratory</sub>
</p>
