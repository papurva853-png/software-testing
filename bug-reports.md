# Bug Reports 🐞

This document contains sample bug reports for a hypothetical e-commerce application.

## Bug Report 1 — Login Button Accepts Empty Credentials

| Field | Details |
|---|---|
| Bug ID | BUG-001 |
| Title | Login button allows submission with empty credentials |
| Module | Login |
| Severity | High |
| Priority | High |
| Environment | Web Application |
| Preconditions | User is on the Login page |
| Steps to Reproduce | 1. Open Login page<br>2. Leave username blank<br>3. Leave password blank<br>4. Click Login |
| Expected Result | Validation messages should be displayed for required fields |
| Actual Result | Login request is submitted without displaying proper validation |
| Status | Open |

---

## Bug Report 2 — Incorrect Search Results

| Field | Details |
|---|---|
| Bug ID | BUG-002 |
| Title | Search displays irrelevant products |
| Module | Product Search |
| Severity | Medium |
| Priority | Medium |
| Environment | Web Application |
| Preconditions | User is on the product search page |
| Steps to Reproduce | 1. Enter a product name<br>2. Click Search |
| Expected Result | Relevant products matching the search keyword should be displayed |
| Actual Result | Unrelated products are displayed |
| Status | Open |

---

## Bug Report 3 — Cart Quantity Allows Invalid Value

| Field | Details |
|---|---|
| Bug ID | BUG-003 |
| Title | Product quantity accepts zero or negative values |
| Module | Shopping Cart |
| Severity | High |
| Priority | High |
| Environment | Web Application |
| Preconditions | Product is added to cart |
| Steps to Reproduce | 1. Open Shopping Cart<br>2. Change product quantity to 0 or negative value |
| Expected Result | Quantity should not accept zero or negative values |
| Actual Result | System accepts the invalid quantity |
| Status | Open |

---

## Bug Report 4 — Logout Does Not Redirect to Login Page

| Field | Details |
|---|---|
| Bug ID | BUG-004 |
| Title | User remains on protected page after logout |
| Module | Logout |
| Severity | High |
| Priority | High |
| Environment | Web Application |
| Preconditions | User is logged in |
| Steps to Reproduce | 1. Login to the application<br>2. Open account page<br>3. Click Logout<br>4. Use browser back button |
| Expected Result | User should not be able to access protected pages after logout |
| Actual Result | Previously viewed account page is accessible |
| Status | Open |

---

## Bug Report 5 — Password Visible in Plain Text

| Field | Details |
|---|---|
| Bug ID | BUG-005 |
| Title | Password is visible while entering password |
| Module | Login |
| Severity | Medium |
| Priority | High |
| Environment | Web Application |
| Preconditions | User is on the Login page |
| Steps to Reproduce | 1. Open Login page<br>2. Enter password |
| Expected Result | Password should be masked |
| Actual Result | Password characters are visible |
| Status | Open |

---

## Bug Report Summary

| Bug ID | Module | Severity | Priority | Status |
|---|---|---|---|---|
| BUG-001 | Login | High | High | Open |
| BUG-002 | Search | Medium | Medium | Open |
| BUG-003 | Cart | High | High | Open |
| BUG-004 | Logout | High | High | Open |
| BUG-005 | Login | Medium | High | Open |

**Total Bugs:** 5

> Note: These are sample defects created for testing practice. They are not claims about a real application's behavior.
