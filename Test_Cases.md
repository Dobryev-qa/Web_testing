# Test Cases – WebShop Demo OpenCart

## Overview

All test cases for this project were **designed and executed in TestRail**.  
This document contains a structured overview of the test cases migrated to GitHub for portfolio demonstration purposes.

---

## Table of Contents

### Registration
- [C2397 – New user registration with valid data](#c2397--new-user-registration-with-valid-data)
- [C2398 – Validation of all required data on Register Account page](#c2398--validation-of-all-required-data-on-register-account-page)
- [C2399 – Register with already used email](#c2399--register-with-already-used-email)

### Authentication
- [C2400 – Login with valid user](#c2400--login-with-valid-user)
- [C2401 – Login with invalid user data](#c2401--login-with-invalid-user-data)
- [C2402 – Reset Forgotten Password](#c2402--reset-forgotten-password)

### Shopping Cart
- [C2403 – Add product to Shopping Cart](#c2403--add-product-to-shopping-cart)
- [C2404 – Remove product from Shopping Cart](#c2404--remove-product-from-shopping-cart)

### Checkout
- [C2405 – Complete product order](#c2405--complete-product-order)
- [C2406 – Place order with missing shipping address](#c2406--place-order-with-missing-shipping-address)

---

## C2397 – New user registration with valid data

**Type:** Functional  
**Priority:** High  
**Tool:** TestRail  

### Preconditions
- User is not registered in the system

### Test Steps
1. Open WebShop OpenCart website  
2. Navigate to the Register Account page  
3. Fill all required fields with valid data  
4. Accept Privacy Policy  
5. Click **Continue**

### Expected Result
- Register Account page opens  
- All fields accept valid input  
- User is redirected to **"Your Account Has Been Created!"** page  

---

## C2398 – Validation of all required data on Register Account page

**Type:** Functional  
**Priority:** High  
**Tool:** TestRail  

### Preconditions
- Register Account page is open

### Description
Validation of required fields when submitting an empty registration form.

### Expected Result
- First Name field shows validation error  
- Last Name field shows validation error  
- Email field shows validation error  
- Password field shows validation error  
- Warning message displayed: *"You must agree to the Privacy Policy!"*  
- User remains on Register Account page  

---

## C2399 – Register with already used email

**Type:** Functional  
**Priority:** High  
**Tool:** TestRail  

### Preconditions
- Register Account page is open  
- User already exists with provided email

### Description
Verify that registration is blocked when using an already registered email.

### Expected Result
- Warning message displayed: *"E-Mail Address is already registered!"*  
- User remains on Register Account page  

---

## C2400 – Login with valid user

**Type:** Functional  
**Priority:** High  
**Tool:** TestRail  

### Preconditions
- User account already exists

### Description
Verify successful login with valid credentials.

### Expected Result
- Login page opens  
- User is authenticated  
- User is redirected to **My Account** page  

---

## C2401 – Login with invalid user data

**Type:** Functional  
**Priority:** High  
**Tool:** TestRail  

### Preconditions
- Login page is open

### Description
Verify validation when incorrect credentials are used.

### Expected Result
- Warning message displayed: *"No match for E-Mail Address and/or Password"*  
- User is not logged in  
- User remains on Login page  

---

## C2402 – Reset Forgotten Password

**Type:** Functional  
**Priority:** High  
**Tool:** TestRail  

### Preconditions
- User account exists  
- User has access to registered email

### Description
Verify password recovery via Forgotten Password functionality.

### Expected Result
- Password reset page opens  
- Email field accepts valid input  
- Success message displayed  
- Password reset email is sent  

---

## C2403 – Add product to Shopping Cart

**Type:** Functional  
**Priority:** High  
**Tool:** TestRail  

### Preconditions
- User is logged in

### Description
Verify adding a product to the shopping cart.

### Expected Result
- Product added to cart  
- Shopping Cart page displays correct product details  
- Cart total updated correctly  

---

## C2404 – Remove product from Shopping Cart

**Type:** Functional  
**Priority:** Medium  
**Tool:** TestRail  

### Preconditions
- Product added to Shopping Cart

### Description
Verify removing product from cart.

### Expected Result
- Product removed  
- Cart total updated  
- Empty cart message displayed if no items remain  

---

## C2405 – Complete product order

**Type:** Functional  
**Priority:** Critical  
**Tool:** TestRail  

### Preconditions
- User logged in  
- Products added to cart

### Description
Verify full checkout flow with valid data.

### Expected Result
- Checkout page opens  
- Order placed successfully  
- Confirmation message displayed  
- Order appears in order history  

---

## C2406 – Place order with missing shipping address

**Type:** Functional  
**Priority:** High  
**Tool:** TestRail  

### Preconditions
- User logged in  
- Product added to cart

### Description
Verify validation when shipping address is missing.

### Expected Result
- Validation message displayed  
- Order not confirmed  
- User remains on Checkout page  

---
