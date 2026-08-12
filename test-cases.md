# Test Cases 🧪

This document contains detailed test cases for a sample e-commerce website.

## Login Test Cases

| Test Case ID | Test Scenario | Test Steps | Test Data | Expected Result | Status |
|---|---|---|---|---|---|
| TC01 | Login with valid credentials | Enter username → Enter password → Click Login | Valid username and password | User should login successfully | Pass |
| TC02 | Login with invalid password | Enter valid username → Enter wrong password → Click Login | Wrong password | Error message should be displayed | Pass |
| TC03 | Login with blank username | Leave username blank → Enter password → Click Login | Blank username | Username validation message should appear | Pass |
| TC04 | Login with blank password | Enter username → Leave password blank → Click Login | Blank password | Password validation message should appear | Pass |
| TC05 | Verify password masking | Enter password in password field | Password | Password should be hidden/masked | Pass |

## Registration Test Cases

| Test Case ID | Test Scenario | Test Steps | Test Data | Expected Result | Status |
|---|---|---|---|---|---|
| TC06 | Register with valid details | Enter all valid details → Click Register | Valid user details | Account should be created | Pass |
| TC07 | Register with invalid email | Enter invalid email → Submit form | `abc@` | Email validation message should appear | Pass |
| TC08 | Register with blank mandatory fields | Leave required fields blank → Submit | Blank fields | Required field messages should appear | Pass |

## Product Search Test Cases

| Test Case ID | Test Scenario | Test Steps | Test Data | Expected Result | Status |
|---|---|---|---|---|---|
| TC09 | Search existing product | Enter product name → Click Search | Laptop | Relevant products should be displayed | Pass |
| TC10 | Search non-existing product | Enter unavailable product → Click Search | XYZ123 | No product found message should appear | Pass |
| TC11 | Search with blank input | Leave search box blank → Click Search | Blank | Appropriate validation or default result should appear | Pass |

## Shopping Cart Test Cases

| Test Case ID | Test Scenario | Test Steps | Test Data | Expected Result | Status |
|---|---|---|---|---|---|
| TC12 | Add product to cart | Open product → Click Add to Cart | Laptop | Product should be added to cart | Pass |
| TC13 | Remove product from cart | Open cart → Click Remove | Laptop | Product should be removed | Pass |
| TC14 | Increase quantity | Open cart → Increase quantity | Quantity = 2 | Product quantity should increase | Pass |
| TC15 | Verify cart total | Add product → Open cart | Product price | Total should be calculated correctly | Pass |

## Checkout Test Cases

| Test Case ID | Test Scenario | Test Steps | Test Data | Expected Result | Status |
|---|---|---|---|---|---|
| TC16 | Proceed to checkout | Add product → Open cart → Click Checkout | Valid product | Checkout page should open | Pass |
| TC17 | Verify shipping address | Enter valid address → Continue | Valid address | Address should be accepted | Pass |
| TC18 | Verify order summary | Complete checkout details | Valid order | Correct product, quantity and price should be displayed | Pass |

## Payment Test Cases

| Test Case ID | Test Scenario | Test Steps | Test Data | Expected Result | Status |
|---|---|---|---|---|---|
| TC19 | Successful payment | Enter valid payment details → Pay | Valid payment details | Payment should be successful | Pass |
| TC20 | Invalid payment details | Enter invalid payment details → Pay | Invalid card details | Payment error should be displayed | Pass |
| TC21 | Verify order after payment | Complete successful payment | Valid payment | Order confirmation should be displayed | Pass |

## Logout Test Cases

| Test Case ID | Test Scenario | Test Steps | Test Data | Expected Result | Status |
|---|---|---|---|---|---|
| TC22 | Logout successfully | Login → Click Logout | Valid user | User should be logged out | Pass |
| TC23 | Access protected page after logout | Logout → Try to access account page | Logged-out user | User should be redirected to login page | Pass |

## Test Case Summary

Total Test Cases: **23**

The test cases cover:

- Login
- Registration
- Product Search
- Shopping Cart
- Checkout
- Payment
- Logout
