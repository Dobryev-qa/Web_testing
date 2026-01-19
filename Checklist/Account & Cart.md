# Checklist – Account and Cart
> Module: User Account and Shopping Cart  
> Application: OpenCart Demo Web Shop

---

## Registration

| ID | Check Item | Expected Result | Priority | Status | Remarks |
|----|-----------|-----------------|----------|--------|---------|
| REG-01 | Navigate to Registration page from Account dropdown | Redirects to the "Register Account" page | High | Passed | |
| REG-02 | Verify required fields are displayed | First Name, Last Name, Email, Password, Confirm Password fields are visible | High | Failed | Confirm Password field is missing. Bug #3 |
| REG-03 | Enter valid First Name | Field accepts input without validation error | Medium | Passed | |
| REG-04 | Enter valid Last Name | Field accepts input without validation error | Medium | Passed | |
| REG-05 | Enter valid Email | Field accepts input without validation error | Medium | Passed | |
| REG-06 | Enter valid Password | Field accepts input without validation error | Medium | Passed | |
| REG-07 | Enter valid Confirm Password | Field accepts input without validation error | Medium | Passed | |
| REG-08 | Accept Privacy Policy | Privacy Policy checkbox/toggle is enabled | High | Passed | |
| REG-09 | Click Continue with all required fields filled | Redirects to "Your Account Has Been Created!" page | High | Passed | |
| REG-10 | Leave First Name empty and click Continue | Validation error message is displayed | High | Passed | |
| REG-11 | Leave Last Name empty and click Continue | Validation error message is displayed | High | Passed | |
| REG-12 | Leave Email empty and click Continue | Validation error message is displayed | High | Passed | |
| REG-13 | Leave Password empty and click Continue | Validation error message is displayed | High | Passed | |
| REG-14 | Leave Confirm Password empty and click Continue | Validation error message is displayed | High | Blocked | Blocked by Bug #3 |
| REG-15 | Click Continue with empty required fields | Required fields are highlighted and marked with a red asterisk (*) | High | Passed | |
| REG-16 | Do not accept Privacy Policy and click Continue | Validation error message is displayed | High | Passed | |
| REG-17 | First Name boundary values (1–32 characters) | Input from 1 to 32 characters is accepted; more than 32 shows validation error | Medium | Passed | |
| REG-18 | Last Name boundary values (1–32 characters) | Input from 1 to 32 characters is accepted; more than 32 shows validation error | Medium | Passed | |
| REG-19 | Enter email without "@" symbol | Validation error message is displayed | High | Passed | |
| REG-20 | Enter email without domain | Validation error message is displayed | High | Passed | |
| REG-21 | Enter completely invalid email | Validation error message is displayed | High | Passed | |
| REG-22 | Enter password shorter than minimum length | Validation error message is displayed | High | Passed | |
| REG-23 | Enter password longer than maximum length | Validation error message is displayed | High | Failed | Password longer than allowed is accepted. Bug #4 |
| REG-24 | Confirm Password does not match Password | Validation error message is displayed | High | Passed | |

---

## Login

| ID | Check Item | Expected Result | Priority | Status | Remarks |
|----|-----------|-----------------|----------|--------|---------|
| LOG-01 | Navigate to Login page from Account dropdown | Redirects to the "Login" page | High | Passed | |
| LOG-02 | Verify Email and Password fields are displayed | Both Email and Password fields are visible | High | Passed | |
| LOG-03 | Enter valid Email | Field accepts input without validation error | Medium | Passed | |
| LOG-04 | Enter valid Password | Field accepts input without validation error | Medium | Passed | |
| LOG-05 | Click Login with valid credentials | Redirects to the user account page | High | Passed | |
| LOG-06 | Click "Forgotten Password?" link | Redirects to password recovery page | Medium | Passed | |
| LOG-07 | Leave Email empty and click Login | Validation error message is displayed | High | Passed | |
| LOG-08 | Leave Password empty and click Login | Validation error message is displayed | High | Passed | |
| LOG-09 | Enter invalid Email format | Validation error message is displayed | High | Passed | |
| LOG-10 | Enter incorrect Email or Password | Validation error message is displayed | High | Passed | |
| LOG-11 | Click Login without filling any fields | Validation errors are displayed for required fields | High | Passed | |
| LOG-12 | Click "Continue" in New Customer section | Redirects to the "Register Account" page | Medium | Passed | |

---

## Shopping Cart

| ID | Check Item | Expected Result | Priority | Status | Remarks |
|----|-----------|-----------------|----------|--------|---------|
| CART-01 | Navigate to Cart page from Header | Redirects to the Shopping Cart page | High | Passed | |
| CART-02 | Verify product list is displayed | All added items are displayed with image, name, price, quantity, and total | High | Passed | |
| CART-03 | Verify product image is clickable | Clicking image redirects to product details page | Medium | Passed | |
| CART-04 | Verify product name is clickable | Clicking product name redirects to product details page | Medium | Passed | |
| CART-05 | Remove product from cart | Product is removed; cart is updated; confirmation message is displayed | High | Passed | |
| CART-06 | Click "Continue Shopping" | Redirects to the previously viewed category or Home page | Medium | Passed | |
| CART-07 | Click "Checkout" | Redirects to the Checkout page | High | Passed | |
| CART-08 | Apply valid coupon code | Discount is applied correctly and total amount is updated | High | Untested | |
| CART-09 | Apply invalid coupon code | Error message is displayed | Medium | Untested | |
| CART-10 | Verify cart totals calculation | Subtotal, tax, shipping, and total are calculated correctly | High | Passed | |
| CART-11 | Verify empty cart message | If cart is empty, message "Your shopping cart is empty" is displayed | High | Passed | |
| CART-12 | Verify cart persistence | Items remain in the cart after page reload or navigation | High | Passed | |
