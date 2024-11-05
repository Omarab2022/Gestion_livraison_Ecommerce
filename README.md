# Gestion de Livraison - Application de e-Commerce pour Livraison de Fleurs

<img width="1203" alt="Screen Shot 2024-11-05 at 11 59 06" src="https://github.com/user-attachments/assets/d3da9a75-604b-4edd-b762-2d6eec58ced6">


## Introduction
This project is a web application designed for ordering and delivering flowers online. It allows customers to place and track orders, while providing managers and delivery agents with tools to manage deliveries efficiently.

## Project Structure
- **Front-end**: Angular
- **Back-end**: Spring Boot
- **Database**: MySQL
- **Version Control**: GitHub
- **Task Management**: Jira
- **Modeling Tools**: Visual Paradigm
- **Containerization**: Docker

## Features
1. **Customer Interface**: Browse products, place orders, real-time order tracking.
2. **Delivery Agent Interface**: Manage and update delivery tasks.
3. **Admin & Manager Interface**: Product and order management, user control.
4. **Security**: Role-based access control with Spring Security.

## System Requirements
- **Angular**: 10 or later
- **Spring Boot**: 2.5 or later
- **MySQL**: 8.0 or later
- **Docker**: Latest version

## Installation

### Prerequisites
- [Node.js and npm](https://nodejs.org/)
- [Java 11](https://www.oracle.com/java/)
- [MySQL Server](https://dev.mysql.com/downloads/installer/)
- [Docker](https://www.docker.com/get-started)

### Steps

#### Back-end Setup (Spring Boot)
1. Navigate to the `backend` directory.
2. Run with Docker:
   ```bash
   docker-compose up --build
### Front-end Setup (Angular)
Navigate to the frontend directory.
Install dependencies:
npm install
Run the Angular app:
ng serve
Database Setup
Create a MySQL database as specified in application.properties.
Run SQL scripts from the database folder.
