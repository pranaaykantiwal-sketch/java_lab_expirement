☕ Advanced Java Programming Laboratory (ADJ Lab)


  A comprehensive collection of Advanced Java laboratory experiments, practical implementations, and academic projects for B.Tech Computer Science and Engineering students.
📌 Overview

Welcome to my Advanced Java Programming Laboratory repository.

This repository contains practical implementations of Advanced Java concepts, including desktop GUI development, MVC architecture, TCP socket programming, database connectivity, distributed computing, and Java web application development.

The experiments are organized to support hands-on learning and demonstrate the practical application of Java programming concepts as part of the B.Tech Computer Science and Engineering curriculum.

🎯 Objectives

- Develop desktop applications using Java Swing and AWT.
- Understand the Model-View-Controller (MVC) design pattern.
- Implement TCP-based client-server communication.
- Perform database operations using JDBC and MySQL.
- Integrate graphical user interfaces with relational databases.
- Explore distributed computing through Java RMI.
- Configure and deploy Java web applications using Apache Tomcat.
- Understand Servlets, session management, filters, and listeners.
- Apply Advanced Java concepts in an integrated project.

📋 Table of Contents

1. "Index of Experiments" (#-index-of-experiments)
2. "Prerequisites & System Setup" (#️-prerequisites--system-setup)
3. "Technology Stack" (#-technology-stack)
4. "Repository Structure" (#-repository-structure)
5. "Experiment 1: Java Swing GUI" (#-experiment-1-gui-form-development-using-java-swing)
6. "Experiment 2: MVC Calculator" (#-experiment-2-model-view-controller-mvc-architecture)
7. "Experiment 3: TCP Client-Server" (#-experiment-3-tcp-socket-programming)
8. "Experiment 4: JDBC Operations" (#-experiment-4-java-database-connectivity-jdbc)
9. "Experiment 5: Database-Integrated GUI" (#-experiment-5-swing--jdbc-integration)
10. "Experiment 6: Java RMI" (#-experiment-6-remote-method-invocation)
11. "Experiment 7: Apache Tomcat" (#-experiment-7-web-server-setup--deployment)
12. "Experiment 8: Servlets, Filters & Listeners" (#-experiment-8-java-web-development)
13. "Experiment 9: Capstone Project" (#-experiment-9-capstone-project)
14. "Getting Started" (#-getting-started)
15. "Learning Outcomes" (#-learning-outcomes)
16. "Author" (#-author)

---

📑 Index of Experiments

Exp. No.| Experiment Title| Core Technologies| Directory
01| Student Registration GUI Form| Java Swing, AWT, Event Handling| "exp1/"
02| MVC Pattern Calculator Application| Java Swing, MVC| "calc/"
03| TCP Socket Client-Server Communication| Java Networking, Sockets, I/O Streams| Check actual source folder
04| Database Connectivity and SQL Operations| JDBC, MySQL, PreparedStatement| "jdbc/"
05| Database-Integrated Registration GUI| Swing, JDBC, MySQL| Check actual source folder
06| Distributed Computing using Java RMI| Remote Interfaces, RMI Registry| "Remote-Method-Invocation/"
07| Web Server Setup and Deployment| Apache Tomcat, WAR Deployment| "apache-tomcat-9.0.121/"
08| Java Web Development| Servlets, Filters, Listeners| "servent/"
09| Cycling E-Commerce Capstone Project| Java, Web Technologies, Database| "BikeIsNice/"

Note: Confirm the directory names and experiment descriptions against the actual files in this repository before submitting.

---

🛠️ Prerequisites & System Setup

Ensure the following tools are installed on your workstation.

Requirement| Recommended Version| Purpose
Java Development Kit| JDK 17 or compatible| Compile and run Java programs
MySQL Server| 8.0+| Database operations
Apache Maven| 3.8+| Build Maven-based applications
Apache Tomcat| Compatible version| Deploy Servlet applications
IDE| VS Code or IntelliJ IDEA| Development and debugging
Git| Current stable release| Version control

Verify Java Installation

java -version
javac -version

Verify Maven Installation

mvn -version

Verify MySQL Installation

mysql --version

---

💻 Technology Stack

Category| Technologies
Programming Language| Java
GUI Development| Swing, AWT
Architecture| Model-View-Controller (MVC)
Database| MySQL
Database Connectivity| JDBC
Networking| TCP Sockets
Distributed Computing| Java RMI
Web Development| Servlets, Filters, Listeners
Web Server| Apache Tomcat
Build Tool| Apache Maven
Version Control| Git and GitHub

---

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
├── Remote-Method-Invocation/
│
├── apache-tomcat-9.0.121/
│
├── servent/
│
├── BikeIsNice/
│
└── README.md

This is an indicative structure. Refer to the repository file listing for the exact files and subdirectories. Add any additional experiment directories that exist in your local copy.

---

🧪 Experiment 1: GUI Form Development Using Java Swing

🎯 Aim & Objective

To design and implement an interactive Student Registration Form using Java Swing components and event handling.

💡 Key Concepts

- "JFrame" for the application window.
- "JLabel" and "JTextField" for labels and input fields.
- "JRadioButton" and "ButtonGroup" for single-choice selection.
- "JCheckBox" for acceptance of terms.
- "JButton" and "ActionListener" for user interaction.
- Input validation and dialog messages using "JOptionPane".

🚀 Compilation & Execution

cd exp1
javac StudentRegistration.java
java StudentRegistration

Ensure the filename and class name match the actual source code.

---

🧪 Experiment 2: Model-View-Controller (MVC) Architecture

🎯 Aim & Objective

To implement a calculator application using the MVC design pattern, separating business logic, user interface, and event handling.

💡 Key Concepts

- Model: Performs arithmetic calculations.
- View: Displays the graphical user interface.
- Controller: Handles events and coordinates model-view interaction.
- Input parsing and validation.
- Handling arithmetic errors, including division by zero.

📂 Indicative File Structure

calc/
├── ModelsCalculator.java
├── ViewsCalculator.java
├── ControllerCalculator.java
└── Runmain.java

🚀 Compilation & Execution

cd calc
javac *.java
java Runmain

---

🧪 Experiment 3: TCP Socket Programming

🎯 Aim & Objective

To establish communication between a Java client and server using TCP sockets.

💡 Key Concepts

- "ServerSocket" for accepting connections.
- "Socket" for client-server communication.
- Input and output streams.
- Message exchange and response handling.
- Connection termination and error handling.

🚀 Compilation & Execution

Navigate to the directory containing the client and server Java files.

javac server.java client.java

Start the server in the first terminal:

java server

Start the client in a second terminal:

java client

The source filenames, class names, and port number must match your actual implementation.

---

🧪 Experiment 4: Java Database Connectivity (JDBC)

🎯 Aim & Objective

To connect a Java application to a MySQL database and perform SQL operations using JDBC.

💡 Key Concepts

- "DriverManager" and "Connection".
- JDBC driver configuration.
- "PreparedStatement" for parameterized SQL queries.
- "Statement" and "ResultSet" for data retrieval.
- CRUD operations: Create, Read, Update, and Delete.
- Database connection management.

🗄️ Example Database Setup

Use the following example only if it matches your program's schema:

CREATE DATABASE IF NOT EXISTS college_db;
USE college_db;

CREATE TABLE IF NOT EXISTS Student (
    id INT PRIMARY KEY,
    name VARCHAR(100),
    branch VARCHAR(50)
);

🚀 Execution

For a project that contains a "src/" directory and a "lib/" directory with the JDBC driver:

javac -cp "lib/*" -d bin src/Main.java

Run the program using the classpath and main class appropriate to your actual project.

Update the database name, table names, credentials, and paths according to your source code.

---

🧪 Experiment 5: Swing & JDBC Integration

🎯 Aim & Objective

To develop a desktop GUI application that stores registration data in a MySQL database.

💡 Key Concepts

- Swing components for form development.
- Form validation.
- JDBC connection management.
- "PreparedStatement" for inserting data.
- Database persistence.
- Handling database errors.

🚀 Execution

Open the experiment directory containing the source files and JDBC driver.

Compile the Java program using the correct source path and library classpath. Configure the MySQL database and credentials before running the application.

The exact directory and commands depend on the files present in your repository.

---

🧪 Experiment 6: Remote Method Invocation (Java RMI)

🎯 Aim & Objective

To implement distributed method calls between a Java client and a remote server.

💡 Key Concepts

- Remote interfaces extending "java.rmi.Remote".
- "RemoteException".
- "UnicastRemoteObject".
- RMI Registry and service binding.
- Remote lookup and method invocation.

📂 Indicative File Structure

Remote-Method-Invocation/
├── Calculator.java
├── CalculatorImpl.java
├── Server.java
└── client.java

🚀 Compilation & Execution

cd Remote-Method-Invocation
javac *.java

Start the RMI Registry if your server does not create it automatically, then start the server and run the client in separate terminals.

java Server

java client

Ensure the registry port, service name, and host configuration match the source code.

---

🧪 Experiment 7: Web Server Setup & Deployment

🎯 Aim & Objective

To understand Apache Tomcat configuration and the deployment of Java web applications.

💡 Key Concepts

- Tomcat directory structure.
- Configuration files and HTTP connectors.
- Web application deployment.
- WAR packaging.
- Server startup, shutdown, and logs.

🚀 Starting Tomcat on Windows

Open PowerShell or Command Prompt:

cd apache-tomcat-9.0.121\bin
.\startup.bat

To stop the server:

.\shutdown.bat

Open the following address in your browser after the server starts:

http://localhost:8080/

Use a compatible Tomcat version for the Servlet API required by your web application.

---

🧪 Experiment 8: Java Web Development

🎯 Aim & Objective

To develop a web application using Java Servlets and demonstrate request processing, session management, filters, and application listeners.

💡 Key Concepts

- HTTP request and response handling.
- Servlet URL mappings.
- Session management using "HttpSession".
- Authentication and request filters.
- Application lifecycle listeners.
- Maven build and WAR deployment.

🚀 Building with Maven

If the experiment contains a "pom.xml" file:

cd servent
mvn clean package

The generated WAR file is normally placed in the project's "target/" directory.

Deploy it to a compatible Tomcat server and open the application context URL shown by the deployment configuration.

Check the project's Servlet API dependency and Tomcat compatibility before deployment.

---

🧪 Experiment 9: Capstone Project — Cycling E-Commerce Platform

🎯 Aim & Objective

To apply Advanced Java concepts in an integrated e-commerce application.

💡 Areas of Implementation

Depending on the actual project source, this experiment may cover:

- Product catalogue and product details.
- User registration and authentication.
- Shopping cart and order management.
- JDBC database operations.
- Java web application architecture.
- Administrative interfaces.
- Networking and distributed services.

📂 Project Directory

BikeIsNice/

🚀 Getting Started

1. Open the capstone project directory.
2. Inspect its "README.md" and build configuration.
3. Configure the required JDK and dependencies.
4. Set up the database if the project requires one.
5. Build using the project's documented build commands.
6. Run or deploy the application according to its configuration.

Follow the project-specific instructions and verify that the described features are implemented in the actual source code.

---

🚀 Getting Started

1. Clone the Repository

git clone https://github.com/pranaaykantiwal-sketch/java_lab_expirement.git

2. Navigate to the Project

cd java_lab_expirement

3. Open in Your IDE

Open the repository folder in Visual Studio Code or IntelliJ IDEA.

4. Configure the Environment

- Configure a compatible JDK.
- Install MySQL if required by an experiment.
- Configure JDBC libraries and database credentials.
- Configure Apache Tomcat for web applications.
- Install Maven for projects that use a "pom.xml" file.

5. Run the Required Experiment

Navigate to the appropriate experiment directory and follow its compilation and execution instructions.

---

📈 Learning Outcomes

This laboratory provides opportunities to develop practical skills in:

- Object-oriented Java programming.
- GUI development and event-driven programming.
- MVC software architecture.
- Database connectivity and SQL operations.
- Network programming and distributed systems.
- Java web development and application deployment.
- Debugging, project organization, and version control.

👨‍💻 Author

Pranaay Kantiwal

B.Tech — Computer Science and Engineering
Global Institute of Technology (GIT), Jaipur, Rajasthan, India

- GitHub Profile: "@pranaaykantiwal-sketch" (https://github.com/pranaaykantiwal-sketch)
- Repository: "java_lab_expirement" (https://github.com/pranaaykantiwal-sketch/java_lab_expirement)

Original Source & Attribution

This repository includes code based on an existing Advanced Java Lab repository. Original authors and contributors should receive appropriate credit, and any changes or additional implementations should be identified accurately.

Reference repository: "Sahil1205-jat/adjrepo" (https://github.com/Sahil1205-jat/adjrepo)

---

<p align="center">
  <b>Advanced Java Programming Laboratory</b><br>
  <sub>Built for learning, experimentation, and academic practice.</sub>
</p>
