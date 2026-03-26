# 🚀 Spring Boot CRUD App

Simple CRUD application built using Spring Boot, MySQL, and REST API.

## 📌 Description

This project demonstrates basic backend development using Spring Boot.
It allows managing products and categories with full CRUD operations.

## 🛠️ Technologies Used

- Java 21
- Spring Boot
- Spring Data JPA
- MySQL (Docker)
- Lombok
- Maven

## ⚙️ Features

### 📦 Product
- Create product
- Get all products
- Get product by ID
- Update product
- Delete product

### 📁 Category
- Create category
- Get all categories
- Get category by ID
- Update category
- Delete category

## 🔗 API Endpoints

### Category

| Method | Endpoint | Description |
|-------|--------|------------|
| GET | /categories | Get all categories |
| GET | /categories/{id} | Get category by ID |
| POST | /categories | Create category |
| PUT | /categories/{id} | Update category |
| DELETE | /categories/{id} | Delete category |

### Product

| Method | Endpoint | Description |
|-------|--------|------------|
| GET | /products | Get all products |
| GET | /products/{id} | Get product by ID |
| POST | /products | Create product |
| PUT | /products/{id} | Update product |
| DELETE | /products/{id} | Delete product |

