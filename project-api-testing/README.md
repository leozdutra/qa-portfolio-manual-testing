# API Testing Project

This project simulates backend API testing for an ecommerce system.

## Objective
Demonstrate API request validation and response analysis skills.

## Endpoints Simulated

### POST /login

Request:
{
 "email": "user@test.com",
 "password": "123456"
}

Expected Response:
200 OK returns auth token.

---

### GET /products

Expected Response:
Returns list of products.

---

### POST /checkout

Expected Behavior:
User must be authenticated.
Stock validation performed.
Price calculation validated.
