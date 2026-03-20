# Product Management System

A full CRUD web application built with Spring MVC 4, Hibernate 4, and MySQL,
following a clean 3-layer architecture.

## Features
- Create, Read, Update, Delete products
- Image upload with form validation (Bean Validation API)
- Post-Redirect-Get pattern to prevent duplicate submissions
- C3P0 connection pooling and proper session management

## Architecture
Controller → Service → DAO (3-layer with dependency injection)

## Tech Stack
- Spring MVC 4
- Hibernate 4 (SessionFactory, Entity Mapping, Cascade)
- MySQL
- JSP / JSTL
- Maven
- Tomcat

## How to Run
1. Clone the repo
2. Configure `hibernate.cfg.xml` with your MySQL credentials
3. Run on Tomcat server
