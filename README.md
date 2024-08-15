# 💻 Digital Banking Application

This project is a digital banking application developed using **Spring Boot** for the backend and **Angular** for the frontend. It allows for managing bank accounts, including current and savings accounts, and provides functionalities for handling various operations such as debit and credit transactions.

## 📑 Table of Contents

- [✨ Features](#-features)
- [🚀 Backend Setup](#-backend-setup)
- [🎨 Frontend Setup](#-frontend-setup)
- [🔐 Security](#-security)
- [📊 Dashboard](#-dashboard)
- [🛠️ Technologies Used](#-technologies-used)
- [📚 Resources](#-resources)

## ✨ Features

- **Customer Management:** Add, edit, delete, and search for customers.
- **Account Management:** Create, manage, and search for bank accounts (current and savings).
- **Operations Management:** Record debit and credit operations on accounts.
- **User Authentication:** Secure login and session management using **Spring Security** and **JSON Web Token (JWT)**.
- **Audit Trail:** Track which authenticated user performed operations.
- **Password Management:** Allow users to change their passwords.
- **Dashboard:** Visualize account statistics using **ChartJS (ng-chart)**.

## 🚀 Backend Setup

1. **Clone the Repository:**

   ```bash
   git clone https://github.com/yourusername/digital-banking-app.git
   cd digital-banking-app/backend
   ```

2. **Create a Spring Boot Project:**  
   Set up the backend project using Spring Boot.

3. **Define JPA Entities:**  
   - `Customer`
   - `BankAccount`
   - `SavingAccount`
   - `CurrentAccount`
   - `AccountOperation`

4. **Create JPA Repositories:**  
   Implement interfaces based on Spring Data JPA.

5. **Service Layer and DTOs:**  
   Develop the service layer and data transfer objects (DTOs).

6. **REST Controllers:**  
   Create RESTful web services to interact with the frontend.

7. **Testing:**  
   Test the DAO layer and the RESTful web services.

8. **API Documentation:**  
   Use Swagger with the following dependency in Spring Boot 3:

   ```xml
   <dependency> 
      <groupId>org.springdoc</groupId> 
      <artifactId>springdoc-openapi-starter-webmvc-ui</artifactId> 
      <version>2.1.0</version> 
   </dependency>
   ```

## 🎨 Frontend Setup

1. **Navigate to the Frontend Directory:**

   ```bash
   cd ../frontend
   ```

2. **Install Dependencies:**

   ```bash
   npm install
   ```

3. **Run the Angular App:**

   ```bash
   ng serve
   ```

4. **Video Tutorials:**  
   Follow [this tutorial](https://www.youtube.com/watch?v=bOoPKctcE0s) for setting up the Angular client.

## 🔐 Security

The application uses **Spring Security** combined with **JWT** for secure authentication and authorization. Refer to [this tutorial](https://www.youtube.com/watch?v=n65zFfl9dqA&authuser=0) for implementation details.

## 📊 Dashboard

Implement the dashboard using **ChartJS (ng-chart)** to display useful graphs and statistics for decision-making.

## 🛠️ Technologies Used

- **Backend:** Spring Boot, Spring Data JPA, Spring Security, JWT, Swagger
- **Frontend:** Angular, ChartJS (ng-chart)
- **Database:** H2 (or your choice of database)
- **Tools:** Maven, npm, Swagger

## 📚 Resources

- [Backend Tutorial Part 1](https://www.youtube.com/watch?v=muuFQWnCQd0&authuser=0)
- [Backend Tutorial Part 2](https://www.youtube.com/watch?v=PTI8cniOXLc&authuser=0)
- [Frontend Tutorial](https://www.youtube.com/watch?v=bOoPKctcE0s)
- [Security Tutorial](https://www.youtube.com/watch?v=n65zFfl9dqA&authuser=0)
