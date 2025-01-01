# IDS-DETECTION
This project focuses on securing web applications by detecting and mitigating SQL Injection and Cross-Site Scripting (XSS) attacks. It logs detected threats, sends real-time email alerts to administrators, and ensures enhanced application protection.

Features
SQL Injection Detection: Identifies and mitigates malicious SQL queries in user inputs.
XSS Attack Detection: Detects scripts or code injected into form inputs to prevent unauthorized actions or data breaches.
Logging and Alert System: Logs all detected attacks in a database and sends real-time email notifications to administrators.
User Authentication: Secure login mechanism with attack detection during authentication.
Extensibility: Modular structure to add more attack detection mechanisms.
Technologies Used
Java: Core programming language.
Spring Boot: Framework for building the application.
JPA (Hibernate): Database interaction and ORM.
MySQL: Database for logging detected attacks.
Jakarta Servlet API: For handling HTTP requests.
Thymeleaf: Front-end rendering engine for login and dashboard pages.
Installation and Setup
Clone the repository:

bash
Copy code
git clone https://github.com/your-username/web-security-detection.git
cd web-security-detection
Configure the database:

Update the application.properties file with your MySQL database credentials.
Run the application:

bash
Copy code
./mvnw spring-boot:run
Access the application at:

Login page: http://localhost:8080/http-request/login
Dashboard: http://localhost:8080/http-request/dashboard
Testing the System
Use tools like Postman to send SQL injection or XSS payloads to test the detection mechanism.
Examples of payloads:
SQL Injection: ' OR '1'='1
XSS: <script>alert('XSS')</script>
Contributing
Contributions are welcome! Feel free to submit issues or pull requests to enhance functionality or add features.
