# Expleo Group E-Learning Platform

Welcome to the Expleo Group E-Learning Platform GitHub organization! This repository hosts the development of an internal platform designed to facilitate training and skill development for Expleo Group employees.

## Project Overview

The Expleo Group E-Learning Platform is a comprehensive system aimed at enhancing the learning experience within our organization. It provides a structured environment for course management, user management, and learning progress tracking.

### Key Features

- **Course Management:** Allows administrators to create, update, and manage courses. Courses can be categorized, and multimedia content can be included to enrich the learning experience.
- **User Management:** Facilitates the creation and management of user accounts. Users are assigned specific roles that dictate their access levels within the platform.
- **Role-Based Access Control:** Ensures secure and appropriate access to different sections of the platform. The roles include:
  - **Master:** Full access, including user and course management.
  - **Admin:** Access to course management and administrative functions.
  - **User:** Access to view and enroll in courses.

## Repository Structure

This GitHub organization contains multiple repositories, each dedicated to a specific microservice or component of the platform:
- **Auth Service:** Handles authentication and authorization, including JWT management.
- **Course Service:** Manages the creation, updating, and deletion of courses.
- **User Service:** Manages user accounts and their respective roles.
- **API Gateway:** Serves as the entry point to the platform, routing requests to the appropriate services.
- **UI/UX Frontend:** The Angular-based user interface for the platform.

## Getting Started

To get started with developing or deploying this platform, follow the steps below:

### Prerequisites

- **Java 17** or later
- **Spring Boot 3.x**
- **Angular 17** or later
- **MongoDB** for the database
- **Docker** for containerization (optional)
- **Keycloak** for identity and access management

### Installation

1. Clone the relevant repository:
   ```bash
   git clone https://github.com/Expleo-group-elearn/frontend.git
