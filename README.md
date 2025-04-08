# 🛒 Management Supermarket System

## 📌 Introduction
**Management Supermarket System** is a web-based application designed to help manage supermarket operations, including product management, order processing, and customer payments. The system includes roles for admin, cashier, and customer with a user-friendly interface.

## ✅ Key Features

### 🔐 Admin
- Login
- Manage product information
- Import goods
- Manage customer orders
- View statistical reports
- Process in-store payments

### 💰 Cashier
- Login
- Process in-store payments

### 🛍️ Customer
- View product catalog
- Manage shopping cart
- Place online orders
- Make online payments via **MoMo**<img src="https://upload.wikimedia.org/wikipedia/vi/f/fe/MoMo_Logo.png" alt="MoMo Logo" width="20"/>

## 📹 Demo Videos
- 🎥 [Customer functionalities demo](https://drive.google.com/file/d/1HKsTGpZzqZOg5_CfUwy0m3IPQYeCc6Mi/view?usp=drive_link)

## ⚙️ Technologies Used
- **Backend:**
  - Java 21
  - Spring Boot (Spring Web, Spring Data JPA, Spring Security)
  - Redis (for caching/session/token storage)
  - Apache Kafka (for asynchronous message handling)
  - WebSocket (for real-time communication)
  - Docker (containerization)

- **Database:**
  - MySQL

- **Frontend:**
  - Vue.js (Composition API, Vue Router, Pinia)

- **Payment Integration:**
  - MoMo (for online payments)


## 📦 System Requirements
- **JDK:** 21
- **Build Tool:** Maven
- **Database:** MySQL
- **Dependencies:**
  - Spring Boot: 3.3.1
  - Liquibase: 4.24.0
  - Lombok: 1.18.32
  - Jedis: 5.1.2
  - JJWT: 0.9.1
  - Spring Messaging: 6.1.11
  - WebSocket: 3.3.2

## 🚧 Limitations
- Some functionalities are not yet stable and may contain bugs.
- Limited test data.
