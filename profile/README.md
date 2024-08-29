# Expleo Group E-Learning Platform

Welcome to the Expleo Group E-Learning Platform GitHub organization! This repository hosts the development of an internal platform designed to facilitate training and skill development for Expleo Group employees.

## Project Overview

The Expleo Group E-Learning Platform is a comprehensive system aimed at enhancing the learning experience within our organization. It provides a structured environment for course management, user management, certificate management, authentication service and learning progress tracking.

### Key Features

- **Course Management:** Allows administrators to create, update, and manage courses. Courses can be categorized, and multimedia content can be included to enrich the learning experience.
- **User Management:** Facilitates the creation and management of user accounts. Users are assigned specific roles that dictate their access levels within the platform.
- **Role-Based Access Control:** Ensures secure and appropriate access to different sections of the platform. The roles include:
  - **Master:** Full access, including user and course management.
  - **Admin:** Access to course management and administrative functions.
  - **User:** Access to view courses and submitting their certificates.

## Repository Structure

This GitHub organization contains multiple repositories, each dedicated to a specific microservice or component of the platform:
- **Auth Service:** Handles authentication and authorization, including JWT management.
- **Course Service:** Manages the creation, updating, and deletion of courses.
- **User Service:** Manages user accounts and their respective roles.
- **Certificate Service:** Manages the creation of certificates, this service communicates with User service asynchronously and synchronously for different purposes.
- **API Gateway:** Serves as the entry point to the platform, routing requests to the appropriate services.
- **Discovery Service:** Implements service discovery using Netflix Eureka, enabling microservices to register themselves and discover other services.
- **UI/UX Frontend:** The Angular-based user interface for the platform with responsive design and a well done dashboard.

## Getting Started

To get started with developing or deploying this platform, follow the steps below:

### Prerequisites

- **Java 17** or later
- **Spring Boot 3.x**
- **Angular 17** or later
- **MongoDB** and **MySQL** for the database
- **Keycloak** for identity and access management
