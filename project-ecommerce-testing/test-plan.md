# Test Plan – Login Feature

Scope:
Authentication, invalid login, password recovery

Out of Scope:
Payment, delivery

Test Types:
Functional, negative, validation

Environment:
Web and mobile browsers

Entry Criteria:
Login feature deployed

Exit Criteria:
All test cases executed and critical bugs fixed

---

## Risk Areas

- Price calculation
- Payment gateway
- Inventory sync
- Discount rules
- User sessions

## Mitigation Strategy

High risk areas will receive priority test coverage.

---

## TC-004 – Add Product Without Internet Connection

Precondition:
User loses connection

Steps:
1. Disable internet
2. Try to add product to cart

Expected Result:
System shows proper error message and no data loss.
