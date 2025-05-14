---
title: Java Spring API
publishDate: 2024-05-10 00:00:00
img: /assets/Java-Api.png
img_alt: Terminal and browser windows showing a Java Spring Boot API with JSON responses
description: |
  A RESTful API built with Java and Spring Boot to serve article, user, and comment data — complete with pagination, validation, and relational logic.
tags:
  - Java
  - Spring Boot
  - REST API
  - PostgreSQL
  - MVC
---

> A robust API built with Spring Boot — fast, clean, and fully documented.

This Java Spring API project was created as part of my ongoing self-directed learning with the **Codecademy Java & Spring Boot track**. It provides a full-featured, RESTful interface for managing news articles, comments, and users — built using **Java**, **Spring Boot**, and **PostgreSQL**.

The API follows **MVC architecture** and is designed for clarity, reliability, and scalability. It supports full CRUD operations, query filtering, pagination, and detailed error handling. I focused heavily on data validation, clean controller logic, and building out relational models between users, comments, and articles.

---

### Key Features

- RESTful endpoints for articles, comments, and users
- Pagination and filtering via query parameters
- Relational database schema (PostgreSQL)
- Data validation with custom error responses
- Modular MVC structure with separation of concerns

---

### Use Cases

This project mimics the kind of backend you might build for a blogging platform, forum, or editorial CMS. It serves well as both a technical showcase and a foundation for connecting to a React or mobile front end. The API is fully documented using Swagger and tested locally using Postman and integration test suites.

---

### Tech Highlights

- Built using **Java 17** and **Spring Boot 3**
- RESTful architecture with clear, consistent endpoints
- PostgreSQL integration with JPA and Hibernate
- Environment-based config (dev/test) using Spring profiles
- Structured for scalability and real-world project extension