# Test Cases

---

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

---

## TC-003 – Discount Not Applied Correctly

Precondition:
Product has discount campaign active

Steps:
1. Add product to cart
2. Open checkout
3. Verify final price

Expected Result:
Discount is applied correctly and visible to user.

---

## TC-004 – Add Product Without Internet Connection

Precondition:
User loses connection

Steps:
1. Disable internet
2. Try to add product to cart

Expected Result:
System shows proper error message and no data loss.
