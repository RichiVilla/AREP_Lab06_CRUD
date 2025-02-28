# Property Management CRUD Application

This project implements a simple **CRUD (Create, Read, Update, Delete)** system for managing real estate properties using **Spring Boot** for the backend.

## Features:
- **Create** a new property listing.
- **Read** all properties or a single property by its ID.
- **Update** an existing property.
- **Delete** a property by its ID.

## Endpoints:

### 1. Create a property
- **POST** `/properties`
- Request body:
  ```json
  {
    "address": "123 Main St",
    "price": 250000,
    "size": 1200,
    "description": "A beautiful family home."
  }



...

...
