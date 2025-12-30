# Email Sending Application - Java

## 📌 Project Overview
This project is a Spring Boot–based Email Sending Application that allows users to send emails programmatically using Gmail SMTP.
The application exposes REST APIs that accept email details and send messages securely using Spring’s mail support.

## 🛠 Technologies Used
- Backend: Java, Spring Boot
- Email Service: Gmail SMTP
- Mail Library: Spring Boot Starter Mail (JavaMailSender)
- Build Tool: Maven
- API Testing Tool: Postman
- Server: Embedded Tomcat

## 🧱 Project Architecture
- Controller Layer: Handles HTTP requests and accepts email data
- Service Layer: Contains business logic for email processing
- Mail Sender: Sends emails using Gmail SMTP configuration

## How the Application Works
1. Client sends an HTTP request with email details (to, subject, body)
2. The controller receives the request
3. Service layer processes the request
4. JavaMailSender sends the email via Gmail SMTP
5. Success or failure response is returned to the client
