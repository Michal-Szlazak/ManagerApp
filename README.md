# ManagerApp - Shop Management Application

## Overview

ManagerApp is a Java Spring Boot application designed to help shop managers efficiently manage their products, sales, orders, clients, and suppliers. It provides a user-friendly interface for creating, editing, and deleting various entities to streamline shop management tasks.

## Features

- **Product Management:**
  - Create new products with details such as name, description, price.
  - Update existing product information.

- **Client and Supplier Management:**
  - Create and maintain a list of clients and suppliers.
  - Store contact information, names, and other relevant details for each client or supplier.

- **Sale and Order Management:**
  - Create new sales and orders with details like date, products, quantities and Client or Supplier.
  - Edit existing sale and order information.
  - Delete sales and orders.
  - creating those automatically updates the stock.

## Prerequisites

Before running ManagerApp, ensure you have the following software installed:

- Java 11 or higher
- Maven 3.8.2 or higher
- Your preferred IDE (e.g., IntelliJ IDEA, Eclipse)

## Getting Started

1. Clone this repository:

   ```bash
   git clone https://github.com/Michal-Szlazak/ManagerApp.git
   ```
2. Open the project in your IDE.
3. Build the project using Maven:
   
    ```bash
    mvn clean install
    ```
4. Run the application
   
   ```bash
   mvn spring-boot:run
   ```
5. Access the application in your web browser at http://localhost:8080.

## Usage
1. Visit the application in your browser.
2. Use the user-friendly interface to manage products, sales, orders, clients, and suppliers.
3. Click on the respective sections to create, edit, or delete entities.
   
## Technologies Used
Spring Boot
Spring Data JPA
Thymeleaf (for HTML templates)
Spring Web
H2 Database (for easy development and testing)
