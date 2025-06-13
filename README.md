<h1 align="center">NODEJS-HW-04</h1>

<p align="center">REST API for Contact Management with Advanced Validation</p>

<p align="center">
  <img src="https://img.shields.io/github/last-commit/emrealtnts0/nodejs-hw-04?color=blue&label=last%20commit" alt="Last Commit">
  <img src="https://img.shields.io/github/languages/top/emrealtnts0/nodejs-hw-04?color=orange&label=JavaScript" alt="JavaScript Percentage">
  <img src="https://img.shields.io/github/languages/count/emrealtnts0/nodejs-hw-04?color=green&label=languages" alt="Languages Count">
</p>

<p align="center">Built with:</p>
<p align="center">
  <img src="https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=node.js&logoColor=white" alt="Node.js">
  <img src="https://img.shields.io/badge/Express.js-000000?style=for-the-badge&logo=express&logoColor=white" alt="Express.js">
  <img src="https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white" alt="MongoDB">
  <img src="https://img.shields.io/badge/Joi-E43B3D?style=for-the-badge&logo=joi&logoColor=white" alt="Joi">
  <img src="https://img.shields.io/badge/ESLint-4B32C3?style=for-the-badge&logo=eslint&logoColor=white" alt="ESLint">
  <img src="https://img.shields.io/badge/.env-ECD53F?style=for-the-badge&logo=dot-env&logoColor=black" alt=".env">
</p>

## Project Overview

A RESTful API for managing a contact book. This project demonstrates advanced request validation using Joi, robust error handling, and a clean project structure. It is designed for learning and practicing backend fundamentals with Node.js, Express, and MongoDB.

## Features

- CRUD operations for contacts (Create, Read, Update, Delete)
- Advanced validation for request bodies, params, and queries
- Centralized error handling
- Modular architecture
- Environment-based configuration

## Installation

1. **Clone the project:**
    ```bash
    git clone <repository-url>
    cd nodejs-hw-04
    ```
2. **Install dependencies:**
    ```bash
    npm install
    ```
3. **Configure environment variables:**
    - Copy `.env.example` to `.env` and set your MongoDB URI and other settings.
4. **Start the application:**
    ```bash
    npm start
    ```

## API Endpoints

- `GET /api/contacts` — List all contacts
- `GET /api/contacts/:contactId` — Get a contact by ID
- `POST /api/contacts` — Add a new contact (with validation)
- `DELETE /api/contacts/:contactId` — Remove a contact
- `PUT /api/contacts/:contactId` — Update a contact (with validation)
- `PATCH /api/contacts/:contactId/favorite` — Update contact's favorite status

## Validation

All input data is validated using Joi schemas. Invalid requests return descriptive error messages and appropriate HTTP status codes.

## License

This project is licensed under the MIT License. See the LICENSE file for details. 