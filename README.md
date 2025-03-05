## MUDApp: The Moving App
![](https://imgur.com/MiDuWQ5.png)

MUDApp is a web application designed to revolutionize the moving and parcel transportation industry. Inspired by platforms like Uber, MUDApp connects users who need to transport goods with transporters who have the appropriate vehicles for the job. This project was developed as part of the Factoria F5 bootcamp, fulfilling all the requirements outlined in the project brief.

---

## Table of Contents
1. [Introduction](#introduction)
2. [Features](#features)
3. [Functional Requirements](#functional-requirements)
4. [Technical Requirements](#technical-requirements)
5. [Technologies Used](#technologies-used)
6. [Installation](#installation)
7. [API Documentation](#api-documentation)
8. [Team](#team)
9. [License](#license)

---

## Introduction

MUDApp is a RESTful API backend developed for a startup aiming to streamline the moving and parcel transportation industry. The application connects clients who need transportation services with transporters who have the appropriate vehicles. This project was developed in two sprints, each lasting one week, and meets all the functional and technical requirements outlined by the client.

---

## Features

- **User Roles**:
  - Unregistered Client
  - Registered Client
  - Unregistered Transporter
  - Registered Transporter
  - Application Administrator
  - System

- **Core Functionality**:
  - Clients can request transportation services.
  - Transporters can offer their services and manage orders.
  - Administrators can manage users and monitor system activity.

---

## Functional Requirements

The application supports the following user roles and functionalities:

1. **Unregistered Client**:
   - Browse transportation services.
   - Register as a client.

2. **Registered Client**:
   - Request transportation services.
   - Track ongoing orders.
   - Manage profile and payment information.

3. **Unregistered Transporter**:
   - Browse available jobs.
   - Register as a transporter.

4. **Registered Transporter**:
   - Accept or reject transportation requests.
   - Manage ongoing orders.
   - Update vehicle and profile information.

5. **Administrator**:
   - Manage users (clients and transporters).
   - Monitor system activity and resolve issues.

6. **System**:
   - Handle notifications and emails.
   - Manage payment processing.

---

## Technical Requirements

The project meets the following technical requirements:

- **Linting**: ESLint and Prettier were used to ensure code quality and consistency.
- **Testing**: Unit tests and integration tests were implemented for all endpoints.
- **API Documentation**: OpenAPI (Swagger) was used to document the API.
- **Deployment**: The application was deployed to a production environment.

---

## Technologies Used

- **Backend**: Node.js, Express.js
- **Database**: MongoDB
- **API Documentation**: Swagger (OpenAPI)
- **Linting**: ESLint, Prettier

---

## Installation

To run the project locally, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/MUDApp-backend.git
2. Navigate to the project directory:
   ```bash
   cd MUDApp-backend
3. Install dependencies:
   ```bash
   pnpm install
4. Set up environment variables:
   - Create a .env file in the root directory.
   - Add the required variables (e.g., MONGO_URI, JWT_SECRET).
5. Start the server:
   ```bash
   pnpm start
5. Access the API:
   Visit http://localhost:3000 in your browser.

## API Documentation
The API is documented using Swagger (OpenAPI). To access the documentation:
- Run the server.
- Visit http://localhost:3000/api-docs in your browser.

#Team
This project was developed by the following Factoria F5 students:

- Karyoli Nieves
- Ana Maria Herrera
- Isadora Matias
- Jose Perez

#License
This project is licensed under the MIT License. See the LICENSE file for details.

Thank you for checking out MUDApp! We hope it makes moving and transportation easier for everyone. 🚚✨
