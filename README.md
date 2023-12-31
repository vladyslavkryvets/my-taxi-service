﻿<img src="https://static.vecteezy.com/system/resources/previews/021/839/176/original/yellow-taxi-car-service-transport-png.png" style="width: 250px; height: 200px;" /> 

# Taxi-service app
This is a simple web application for registration drivers in taxi service and managements cars, manufacturers, drivers. The project is according to the requirements of SOLID principles for easy reading, testing, and extension. This project used N-tier architecture, the principle of dependency injection and users authentication.

### Architecture layers

- DAO - It communicates with the Database and handles the persisting of our data.
- Service - The program's business logic executed here.
- Controller - This is where we handle all the incoming requests to our application and return a response.

### Technologies Used

- Java 11
- Maven 3.1.1
- Apache Tomcat
- Java Servlet API
- JSP
- JSTL
- Logger
- JDBC
- MySQL

### Setup

1. Clone the project into your local directory and then open it in an IDE.
2. Create MySQL database, and the necessary tables using resources/init_db.sql.
3. Fill in the fields(URL, USERNAME, PASSWORD) in the "ConnectionUtil" class in the "taxi.util" package. If you use another database you need to change field "JDBC_DRIVER" and dependencies in web.xml.
4. Before running the app you should configure Apache Tomcat.
5. Run the program and create a new driver by filling out the form.
