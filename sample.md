# My API Documentation

## Introduction
Welcome to the API documentation for My API. This documentation provides details about the available endpoints, request parameters, response formats, and more.

## Authentication
Before you can access the API endpoints, you need to authenticate using an API key.

## Endpoints

### Get User Profile
Retrieve information about a user.

- **URL:** `/api/users/{user_id}`
- **Method:** `GET`
- **Parameters:**
  - `user_id` (integer, required) - The ID of the user.
- **Response:**
  ```json
  {
    "id": 123,
    "name": "John Doe",
    "email": "john@example.com"
  }
