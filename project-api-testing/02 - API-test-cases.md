# API Test Cases – Ecommerce Project

## API-001 – Login Success
**Endpoint:** POST /login  
**Scenario:** Valid credentials  
**Expected Result:** 200 OK and auth token returned

## API-002 – Login Invalid Password
**Endpoint:** POST /login  
**Scenario:** Incorrect password  
**Expected Result:** 401 Unauthorized error returned

## API-003 – Access Products Without Authentication
**Endpoint:** GET /products  
**Scenario:** No authentication token  
**Expected Result:** 403 Forbidden error

## API-004 – Checkout Without Stock
**Endpoint:** POST /checkout  
**Scenario:** Product out of stock  
**Expected Result:** 400 Bad Request with stock alert message

Expected Result:
400 Bad Request with stock alert message.
