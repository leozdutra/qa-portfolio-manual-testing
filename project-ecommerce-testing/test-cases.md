# Test Cases

## TC-001 – Add Product to Cart

Precondition:
User is on product page

Steps:
1. Select a product
2. Click on Add to Cart
3. Open shopping cart

Expected Result:
Product is added correctly with correct price and quantity.

---

## TC-002 – Quantity Greater Than Stock

Precondition:
Product has limited stock

Steps:
1. Increase quantity beyond available stock
2. Try to add product to cart

Expected Result:
System blocks the action and shows error message.
