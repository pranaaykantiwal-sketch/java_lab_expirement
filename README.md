☕ Advanced Java Programming Laboratory

A Practical journey Through Advance Java Programming , Database connectivity , Networking and Enterprice Web Devlopment

Overview * Experiments * Tech Stack * Setup * Author 

📌 Overview

Welcome to my Advanced Java Programming Laboratory repository.

This repository contains Java laboratory experiments, practical implementations, and academic projects developed as part of the B.Tech Computer Science and Engineering curriculum.

The collection covers essential Advanced Java concepts, including desktop GUI development, software architecture, TCP socket programming, database integration, distributed computing, and Java web application development.

The objective is to strengthen practical programming skills by implementing real-world concepts through structured laboratory experiments.

🎯 Objectives

- Develop interactive desktop applications using Java Swing and AWT.
- Understand the Model-View-Controller (MVC) design pattern.
- Implement client-server communication using TCP sockets.
- Perform database operations using JDBC and MySQL.
- Integrate graphical interfaces with relational databases.
- Explore distributed computing using Java RMI.
- Configure and deploy Java web applications using Apache Tomcat.
- Understand Servlets, HTTP sessions, filters, and listeners.
- Apply Advanced Java concepts in a full-stack e-commerce project.

📋 Table of Contents

1. "Experiments Index" (#-experiments-index)
2. "Prerequisites" (#️-prerequisites)
3. "Technology Stack" (#-technology-stack)
4. "Repository Structure" (#-repository-structure)
5. "Installation and Setup" (#-installation-and-setup)
6. "Experiment Details" (#-experiment-details)
7. "Learning Outcomes" (#-learning-outcomes)
8. "Author" (#-author)

---

📚 Experiments Index

No.| Experiment| Core Technologies| Directory
01| Student Registration GUI Form| Java Swing, AWT, Event Handling| "exp1/"
02| MVC Calculator Application| Java Swing, MVC Architecture| "calc/"
03| TCP Client-Server Communication| Java Networking, Sockets, I/O| "server-client/"
04| JDBC Database Connectivity and SQL Operations| JDBC, MySQL| "jdbc/"
05| Database-Integrated Registration GUI| Swing, JDBC, MySQL| "strjdbc/"
06| Distributed Computing| Java RMI, Remote Interfaces| "Remote-Method-Invocation/"
07| Web Server Setup and Deployment| Apache Tomcat 9| "apache-tomcat-9.0.121/"
08| Java Web Application Development| Servlets, Filters, Listeners| "servent/"
09| Cycling E-Commerce Capstone Project| Java, Web Technologies, Database| "BikeIsNice/"

Note: Directory names and implementation details should match the actual files present in the repository.

🛠️ Prerequisites

Install the following tools before running the experiments.

Requirement| Recommended Version| Purpose
Java JDK| 17 or compatible project version| Compilation and execution
MySQL Server| 8.0+| Database experiments
Apache Maven| 3.8+| Building Maven projects
Apache Tomcat| 9.0.x for compatible Servlet applications| Web deployment
IDE| IntelliJ IDEA or VS Code| Development
Git| Latest stable version| Version control

Verify your Java installation:

java -version
javac -version

For Maven-based projects:

mvn -version

💻 Technology Stack

Programming and Application Development

- Java
- Object-Oriented Programming
- Java Swing and AWT
- Event Handling
- MVC Architecture

Database Technologies

- MySQL
- JDBC
- SQL CRUD Operations
- PreparedStatement
- ResultSet

Networking and Distributed Computing

- TCP Sockets
- Client-Server Architecture
- Java RMI
- Remote Interfaces
- RMI Registry

Web Development

- Java Servlets
- HTTP Session Management
- Filters and Listeners
- Apache Tomcat
- Maven

Development Tools

- Visual Studio Code
- IntelliJ IDEA
- Git
- GitHub

📂 Repository Structure

java_lab_expirement/
│
├── .idea/
├── .vscode/
│
├── exp1/
│   └── StudentRegistration.java
│
├── calc/
│   ├── ModelsCalculator.java
│   ├── ViewsCalculator.java
│   ├── ControllerCalculator.java
│   └── Runmain.java
│
├── jdbc/
│
├── strjdbc/
│
├── Remote-Method-Invocation/
│
├── server/
├── server-client/
│
├── apache-tomcat-9.0.121/
│
├── servent/
│
├── BikeIsNice/
│
├── adj.iml
└── README.md

The tree is illustrative. Some directories may have additional files or different internal structures.

🚀 Installation and Setup

Step 1: Clone the repository

git clone https://github.com/pranaaykantiwal-sketch/java_lab_expirement.git

Step 2: Open the project directory

cd java_lab_expirement

Step 3: Open in your IDE

Open the project folder in Visual Studio Code or IntelliJ IDEA and configure the required JDK.

Step 4: Configure dependencies

For database experiments, install MySQL and add the appropriate MySQL Connector/J library.

For web experiments, configure a compatible Apache Tomcat server and Maven where required.

Step 5: Compile and run

Follow the experiment-specific instructions below. Database and web applications may require additional configuration.

---

🧪 Experiment Details

Experiment 01 — Student Registration GUI

Objective: Build an interactive student registration form using Java Swing.

Concepts covered:

- JFrame and JLabel
- JTextField and JRadioButton
- JCheckBox and JButton
- Event handling using ActionListener
- Form validation and dialog messages

Execution:

cd exp1
javac StudentRegistration.java
java StudentRegistration

Experiment 02 — MVC Calculator Application

Objective: Implement a calculator using the Model-View-Controller design pattern.

Concepts covered:

- Separation of application logic and UI
- Model for arithmetic operations
- View for the calculator interface
- Controller for user interaction
- Exception and division-by-zero handling

Execution:

cd calc
javac *.java
java Runmain

Experiment 03 — TCP Client-Server Communication

Objective: Establish communication between a Java client and server using TCP sockets.

Concepts covered:

- ServerSocket and Socket
- Input and output streams
- Client-server messaging
- TCP communication
- Connection management

Execution:

cd server-client
javac server.java client.java

Run the server first:

java server

Open another terminal in the same directory and run:

java client

Experiment 04 — JDBC Database Operations

Objective: Connect a Java application to MySQL and execute SQL operations using JDBC.

Concepts covered:

- DriverManager and Connection
- PreparedStatement
- Statement and ResultSet
- SQL queries and CRUD operations
- Database connection management

Before execution: Configure the database name, username, password, JDBC driver, and table schema according to the source code.

Experiment 05 — Swing and JDBC Integration

Objective: Develop a desktop registration application that stores user data in a MySQL database.

Concepts covered:

- Swing GUI components
- JDBC integration
- Form validation
- Database persistence
- PreparedStatement and SQL INSERT operations

Before execution: Ensure that MySQL is running, the required table exists, and the JDBC driver is available.

Experiment 06 — Java RMI

Objective: Implement distributed method calls between a Java client and a remote server.

Concepts covered:

- Remote interfaces
- UnicastRemoteObject
- RMI Registry
- Remote object binding and lookup
- RemoteException

Execution:

cd Remote-Method-Invocation
javac *.java

Start the RMI registry and server using the commands appropriate to your environment, then run the client in a separate terminal.

Experiment 07 — Apache Tomcat Deployment

Objective: Understand Java web server configuration and application deployment.

Concepts covered:

- Tomcat directory structure
- Server configuration
- Web application deployment
- WAR files
- Server startup and shutdown

For Windows, use the applicable scripts in the Tomcat "bin" directory, such as "startup.bat" and "shutdown.bat".

Experiment 08 — Servlets, Filters and Listeners

Objective: Develop a dynamic Java web application using Servlet API features.

Concepts covered:

- HTTP request and response handling
- Servlet mappings
- Session management
- Request filtering
- Application lifecycle listeners
- Maven packaging and deployment

Build command for a Maven project:

cd servent
mvn clean package

Deploy the generated WAR file to a compatible servlet container after confirming the project's Servlet API version.

Experiment 09 — Cycling E-Commerce Capstone

Objective: Apply Advanced Java concepts in an integrated e-commerce application.

Potential areas covered, depending on the actual implementation:

- Product catalogue and shopping cart
- User registration and authentication
- Database-backed product and order management
- Java web application architecture
- Administrative interfaces
- Networking and distributed services

Refer to the "BikeIsNice/" directory for the capstone's actual source code and project-specific setup instructions.

---

📈 Learning Outcomes

Through these laboratory experiments, I aim to develop practical knowledge of:

- Java application development and object-oriented programming.
- GUI design and event-driven programming.
- Software architecture and code organization.
- Relational database design and JDBC integration.
- TCP networking and distributed applications.
- Servlet-based web development.
- Application server configuration and deployment.
- Debugging, testing, and version control.

👨‍💻 Author

Pranaay Kantiwal

B.Tech — Computer Science and Engineering
Global Institute of Technology (GIT), Jaipur, Rajasthan, India

- GitHub Profile: "@pranaaykantiwal-sketch" (https://github.com/pranaaykantiwal-sketch)
- Project Repository: "java_lab_expirement" (https://github.com/pranaaykantiwal-sketch/java_lab_expirement)

🎓 Academic Purpose

This repository is maintained for academic learning, laboratory practice, and documenting the practical implementation of Advanced Java programming concepts.

The experiments are intended to support conceptual understanding and hands-on development.

---

<p align="center">
  <b>Developed with ☕ Java</b><br>
  <sub>Advanced Java Programming Laboratory | B.Tech CSE</sub>
</p>
