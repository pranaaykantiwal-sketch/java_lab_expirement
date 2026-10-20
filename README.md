# ☕ Advanced Java Laboratory — Experiments & Projects

<p align="center">
  <b>A Practical Journey Through Advanced Java Programming</b>
  <br>
  Desktop Applications • Database Connectivity • Networking • Distributed Computing • Web Development
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Language-Java-orange?style=for-the-badge&logo=openjdk&logoColor=white" alt="Java">
  <img src="https://img.shields.io/badge/Database-JDBC-blue?style=for-the-badge" alt="JDBC">
  <img src="https://img.shields.io/badge/Web-Servlets%20%7C%20Tomcat-green?style=for-the-badge" alt="Web Technologies">
  <img src="https://img.shields.io/badge/Project-Academic%20Learning-purple?style=for-the-badge" alt="Academic Project">
</p>

---

## 📖 About the Repository

Welcome to the **Advanced Java Laboratory** repository!

This repository brings together a collection of Java laboratory experiments and application development projects designed to explore important concepts in Java programming. It covers graphical user interface development, software architecture, database connectivity, client-server communication, distributed applications, web technologies, and e-commerce application development.

Each experiment focuses on a specific programming concept and provides an opportunity to understand how Java technologies can be used to solve practical problems.

The repository is organized into individual project directories to make the source code easier to explore, understand, test, and maintain.

### 🎯 What This Repository Covers

- Desktop application development using Java Swing.
- MVC architecture and separation of application responsibilities.
- Database operations using JDBC and SQL.
- Client-server communication using TCP sockets.
- Distributed computing using Java RMI.
- Server-side programming using Java Servlets.
- Java web server concepts and Apache Tomcat.
- Application structure, configuration, and build tools.
- Practical implementation of Java concepts through individual experiments.

## 📑 Table of Contents

- [About the Repository](#-about-the-repository)
- [Learning Objectives](#-learning-objectives)
- [Experiment Index](#-experiment-index)
- [Detailed Project Explanations](#-detailed-project-explanations)
  - [01. Student Registration System](#01-student-registration-system)
  - [02. Calculator Using MVC](#02-calculator-using-mvc)
  - [03. TCP Client-Server Communication](#03-tcp-client-server-communication)
  - [04. JDBC Connectivity](#04-jdbc-connectivity)
  - [05. Swing and JDBC Integration](#05-swing-and-jdbc-integration)
  - [06. Java RMI](#06-java-rmi)
  - [07. Java Servlets](#07-java-servlets)
  - [08. E-commerce Application](#08-e-commerce-application)
  - [09. Apache Tomcat](#09-apache-tomcat)
- [Technologies Used](#-technologies-used)
- [Prerequisites](#-prerequisites)
- [Getting Started](#-getting-started)
- [Running the Projects](#-running-the-projects)
- [Learning Outcomes](#-learning-outcomes)
- [Author](#-author)
- [Academic Disclaimer](#-academic-disclaimer)

## 🎯 Learning Objectives

The primary objectives of these experiments are to:

1. Strengthen understanding of Java syntax, classes, objects, and object-oriented programming.
2. Build interactive desktop applications using Swing components and event handling.
3. Understand MVC architecture and modular software design.
4. Connect Java programs to relational databases using JDBC.
5. Execute SQL queries and understand database interaction from Java.
6. Implement communication between client and server applications.
7. Explore remote method invocation and distributed computing.
8. Understand the request-response lifecycle in Java web applications.
9. Learn the role of a web container in deploying Java Servlets.
10. Apply programming concepts to practical application development.

## 🧪 Experiment Index

| No. | Project / Experiment | Main Concepts | Directory |
|:---:|---|---|---|
| 01 | Student Registration System | Swing, GUI, Event Handling | [`StudentRegistration`](./StudentRegistration/) |
| 02 | Calculator Using MVC | Java, MVC Architecture | [`CalculatorMVC`](./CalculatorMVC/) |
| 03 | TCP Client-Server Communication | Networking, TCP Sockets | [`TCPClientServer`](./TCPClientServer/) |
| 04 | JDBC Connectivity | JDBC, SQL, Database Access | [`JDBCConnectivity`](./JDBCConnectivity/) |
| 05 | Swing and JDBC Integration | GUI, JDBC | [`SwingJDBCIntegration`](./SwingJDBCIntegration/) |
| 06 | Remote Method Invocation | Java RMI, Distributed Computing | [`JavaRMI`](./JavaRMI/) |
| 07 | Java Servlet Experiments | Servlets, HTTP, Web Applications | [`JavaServelets`](./JavaServelets/) |
| 08 | E-commerce Application | Java, Maven, SQL | [`EcommerceApplication`](./EcommerceApplication/) |
| 09 | Apache Tomcat Environment | Web Container, Deployment | [`apache-tomcat-9.0.121`](./apache-tomcat-9.0.121/) |

> **Note:** The descriptions below explain the general purpose of each project based on its name and the discussed repository structure. Exact functionality depends on the implementation in the corresponding source files.

## 📂 Detailed Project Explanations

### 01. Student Registration System

**Directory:** [`StudentRegistration/`](./StudentRegistration/)

**Overview**

The Student Registration System is a desktop application concept for collecting and displaying student information through a graphical user interface. It demonstrates how Java Swing can be used to build forms and handle user interactions.

**Key Concepts**

- Java Swing components and layouts.
- Text fields, labels, buttons, and form controls.
- Event handling for user actions.
- Input collection and basic validation.
- Organizing GUI code into manageable components.

**Expected Learning**

This experiment helps demonstrate the fundamentals of building interactive desktop applications and processing information entered by a user.

**Technologies:** Java, Swing, AWT.

### 02. Calculator Using MVC

**Directory:** [`CalculatorMVC/`](./CalculatorMVC/)

**Overview**

This project demonstrates a calculator organized around the Model-View-Controller (MVC) architectural pattern. MVC separates application logic, user interface, and interaction handling into distinct responsibilities.

**Architecture**

- **Model:** Contains the calculation logic and application data.
- **View:** Displays the calculator interface and results.
- **Controller:** Handles user actions and coordinates the model and view.

**Key Concepts**

- MVC architecture.
- Separation of concerns.
- Java classes and object-oriented design.
- GUI event handling.
- Connecting user actions to application logic.

**Expected Learning**

The project illustrates how separating responsibilities can improve code readability, testing, and maintainability compared with placing all functionality in one class.

**Technologies:** Java, Java Swing, MVC.

### 03. TCP Client-Server Communication

**Directory:** [`TCPClientServer/`](./TCPClientServer/)

**Overview**

This experiment explores communication between two programs over a network using Transmission Control Protocol (TCP) sockets. A typical client connects to a server, exchanges data, and receives a response.

**Key Concepts**

- Client-server architecture.
- Socket and server socket programming.
- Host addresses and port numbers.
- Establishing and closing network connections.
- Sending and receiving data through input and output streams.
- Handling connection and communication errors.

**Typical Communication Flow**

1. The server starts and listens on a configured port.
2. The client establishes a connection to the server.
3. The client and server exchange messages.
4. The connection is closed when communication is complete.

**Expected Learning**

This experiment introduces network programming fundamentals and explains how independent Java applications can communicate.

**Technologies:** Java Networking, TCP Sockets, Input/Output Streams.

### 04. JDBC Connectivity

**Directory:** [`JDBCConnectivity/`](./JDBCConnectivity/)

**Overview**

This experiment demonstrates Java Database Connectivity (JDBC), the standard Java API for communicating with relational databases. JDBC enables Java programs to connect to a database, execute SQL statements, and process query results.

**Key Concepts**

- JDBC drivers and database connection URLs.
- Establishing database connections.
- Creating and executing SQL statements.
- Reading query results using `ResultSet`.
- Handling SQL exceptions.
- Managing database resources.

**Typical Workflow**

1. Configure the required JDBC driver.
2. Establish a database connection.
3. Prepare and execute an SQL query.
4. Process the returned result.
5. Close database resources properly.

**Expected Learning**

This experiment provides a foundation for integrating database operations into Java applications.

**Technologies:** Java, JDBC, SQL, Relational Databases.

### 05. Swing and JDBC Integration

**Directory:** [`SwingJDBCIntegration/`](./SwingJDBCIntegration/)

**Overview**

This project explores the integration of a Java Swing graphical interface with JDBC database operations. It demonstrates how a desktop interface can be connected to a database-backed application.

**Key Concepts**

- Building forms using Swing.
- Capturing user input.
- Connecting GUI actions to database operations.
- Executing SQL queries through JDBC.
- Displaying database results in the interface.
- Handling validation and database errors.

**Typical Application Flow**

1. The user interacts with the graphical interface.
2. The application validates the supplied information.
3. JDBC communicates with the configured database.
4. The application processes the database response.
5. Relevant information or status messages are displayed.

**Expected Learning**

This experiment combines user-interface development with database programming and illustrates how desktop applications can interact with persistent data.

**Technologies:** Java, Swing, JDBC, SQL.

### 06. Java Remote Method Invocation (RMI)

**Directory:** [`JavaRMI/`](./JavaRMI/)

**Overview**

Java RMI is a mechanism that allows a Java application to invoke methods on an object running in another Java Virtual Machine. It provides a way to build distributed applications using Java objects.

**Key Concepts**

- Remote interfaces and remote methods.
- Remote object implementations.
- RMI registry and service lookup.
- Client-server communication.
- Remote exceptions and network-related errors.
- Distributed application architecture.

**Typical RMI Workflow**

1. Define a remote interface.
2. Implement the remote service.
3. Start or configure the RMI registry.
4. Register the remote object.
5. Allow a client to look up and invoke the remote service.

**Expected Learning**

This experiment introduces distributed computing and demonstrates how Java applications can access services hosted by another process.

**Technologies:** Java RMI, Remote Interfaces, RMI Registry.

### 07. Java Servlet Experiments

**Directory:** [`JavaServelets/`](./JavaServelets/)

**Overview**

Java Servlets are server-side Java components used to handle web requests and generate responses. Servlets commonly run inside a servlet container such as Apache Tomcat.

**Key Concepts**

- HTTP request and response handling.
- Servlet lifecycle.
- Processing request parameters.
- Generating dynamic responses.
- Servlet configuration and URL mapping.
- Deploying web applications to a servlet container.

**Typical Request Flow**

1. A browser or client sends an HTTP request.
2. The servlet container routes the request to the appropriate servlet.
3. The servlet processes the request.
4. A response is generated and returned to the client.

**Expected Learning**

This experiment introduces the foundations of server-side Java web development and explains how Java code can respond to browser requests.

**Technologies:** Java Servlets, HTTP, Apache Tomcat.

### 08. E-commerce Application

**Directory:** [`EcommerceApplication/`](./EcommerceApplication/)

**Overview**

The E-commerce Application is a larger application-development project intended to bring together concepts such as Java programming, project organization, database integration, and web application development.

The directory includes a Maven project file (`pom.xml`), a project README, an SQL script named `shoppsphere.sql`, and a networking test script. These files suggest a project with build configuration and database-related resources.

**Key Areas to Explore**

- Application source code and package organization.
- Maven configuration and dependencies.
- Database schema and SQL scripts.
- Application configuration and runtime requirements.
- Networking or integration tests, where applicable.
- Build and deployment instructions.

**Working with the Project**

1. Review the project's `README.md`.
2. Inspect `pom.xml` to understand its dependencies and build configuration.
3. Review `shoppsphere.sql` before setting up or modifying a database.
4. Configure any required environment variables or database credentials.
5. Follow the project-specific build and run instructions.

**Expected Learning**

This project provides an opportunity to study how multiple application components and development tools can be organized into a larger software project.

**Technologies:** Java, Maven, SQL, and the frameworks or libraries configured in the project.

> The exact e-commerce features, such as authentication, product management, cart operations, or order processing, should be documented after confirming that they are implemented in the source code.

### 09. Apache Tomcat Environment

**Directory:** [`apache-tomcat-9.0.121/`](./apache-tomcat-9.0.121/)

**Overview**

Apache Tomcat is a Java web server and servlet container used to run Java web applications based on Servlet and related web specifications.

This directory appears to contain a Tomcat distribution or environment associated with the laboratory work.

**Key Concepts**

- The role of a servlet container.
- Starting and stopping a Tomcat server.
- HTTP ports and server configuration.
- Deploying Java web applications.
- Understanding application deployment directories.
- Reading server logs and diagnosing startup issues.

**Expected Learning**

This environment helps demonstrate how Java web applications are hosted and executed within a servlet container.

**Technologies:** Apache Tomcat, Java, Servlets, HTTP.

> Keep server installation files and generated runtime directories separate from application source code when possible. Do not rename the Tomcat installation directory if scripts or configuration files depend on its current path.

## 🛠️ Technologies Used

| Technology | Purpose |
|---|---|
| Java | Main programming language |
| Java Swing / AWT | Desktop graphical user interfaces |
| MVC | Application architecture |
| JDBC | Database connectivity |
| SQL | Database queries and schema management |
| TCP Sockets | Network communication |
| Java RMI | Distributed Java applications |
| Java Servlets | Server-side web programming |
| Apache Tomcat | Servlet container and web application deployment |
| Apache Maven | Build automation and dependency management |
| Visual Studio Code | Development environment |

The exact versions and dependencies may vary between individual projects.

## ⚙️ Prerequisites

Install the tools required by the experiment you want to run:

- Java Development Kit (JDK).
- Visual Studio Code or another Java-compatible IDE.
- Java Extension Pack or equivalent Java development support.
- Apache Maven for Maven-based projects.
- Apache Tomcat for servlet-based experiments.
- A compatible database server and JDBC driver for database-dependent projects.

Verify Java is installed:

```bash
java -version
javac -version
```

Verify Maven if required:

```bash
mvn -version
```

## 🚀 Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/pranaaykantiwal-sketch/java_lab_expirement.git
```

### 2. Enter the Project Directory

```bash
cd java_lab_expirement
```

### 3. Open the Repository in VS Code

```bash
code .
```

### 4. Choose an Experiment

Open the corresponding directory and review its source files, dependencies, and project-specific documentation.

## ▶️ Running the Projects

### Standalone Java Programs

For a simple Java class without external dependencies:

```bash
javac Main.java
java Main
```

Replace `Main.java` and `Main` with the actual filename and class name. Packaged applications and programs with multiple dependencies may require a different compilation command.

### Maven-Based Project

For the e-commerce project:

```bash
cd EcommerceApplication
mvn clean package
```

Review the project's documentation and `pom.xml` for the correct build and execution procedure. Building the project does not automatically configure a database or deploy the application.

### Database-Dependent Projects

Before running JDBC-based applications:

1. Identify the database system and required schema.
2. Configure connection details according to the project.
3. Ensure the required JDBC driver is available.
4. Review any SQL scripts before execution.
5. Avoid committing database passwords or private credentials to GitHub.

### Networking and RMI Projects

For socket and RMI experiments:

1. Check the configured host and port.
2. Start the server or registry where required.
3. Run the client using the correct configuration.
4. Check firewall settings and server logs if connections fail.

## 💡 Key Learning Outcomes

After exploring these experiments, students can develop practical familiarity with:

- Object-oriented Java programming.
- GUI design and event-driven development.
- MVC architecture and separation of concerns.
- Database connections, SQL queries, and JDBC resource management.
- Client-server communication and network sockets.
- Distributed computing using Java RMI.
- Server-side Java programming with Servlets.
- Web application containers and deployment.
- Maven build configuration and dependency management.
- Project organization, debugging, and documentation.

## 👨‍💻 Author

**Pranaay Kantiwal**

- **Course:** B.Tech — Computer Science and Engineering
- **Institution:** Global Institute of Technology, Jaipur, Rajasthan, India
- **GitHub:** [pranaaykantiwal-sketch](https://github.com/pranaaykantiwal-sketch)
- **Repository:** [java_lab_expirement](https://github.com/pranaaykantiwal-sketch/java_lab_expirement)

## 🎓 Academic Disclaimer

This repository is intended for educational purposes, laboratory practice, and learning Java technologies.

Project descriptions explain the concepts associated with each experiment. Refer to the actual source code to confirm implemented functionality and execution requirements. Any external source material used in a project should be acknowledged appropriately, and contributions should be described accurately.

---

<p align="center">
  <b>☕ Learn. Build. Experiment. Improve.</b>
  <br>
  <i>Advancing Java skills through practical implementation.</i>
</p>
