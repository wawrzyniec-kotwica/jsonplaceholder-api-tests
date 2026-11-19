# JSONPlaceholder API Testing – Postman

## Project Overview

This project demonstrates basic API testing using Postman and JavaScript assertions.

The tests were created for the public JSONPlaceholder REST API.

## Tools and Technologies

- Postman
- JavaScript
- REST API
- JSON
- GitHub

## Test Coverage

| Method | Test Scenario | Expected HTTP Status |
|---|---|---|
| GET | Retrieve a post | 200 |
| POST | Create a post | 201 |
| POST | Submit a request without a title | 201 |
| PUT | Update an entire post | 200 |
| PATCH | Update a post title | 200 |
| DELETE | Delete a post | 200 |

## Automated Tests

The collection includes assertions checking HTTP status codes, response data and JSON properties.

## Test Execution Results

**Execution date:** November 19, 2026

- Total requests: 6
- Passed tests: 6
- Failed tests: 0
- Execution tool: Postman Collection Runner

## How to Run

1. Import the Postman collection JSON file.
2. Create a Postman environment.
3. Add the variable `baseUrl` with the value `https://jsonplaceholder.typicode.com`.
4. Select the environment.
5. Run the collection using Postman Collection Runner.

## Notes

JSONPlaceholder is a demonstration API. POST, PUT, PATCH and DELETE requests simulate changes without permanently modifying server data.

The missing-title scenario verifies the observed API response rather than asserting a production business validation requirement.
