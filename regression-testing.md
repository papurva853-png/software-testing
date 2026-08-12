# Regression Testing 🔄

## What is Regression Testing?

Regression testing is performed to verify that existing features of an application continue to work correctly after new changes, enhancements, or bug fixes are introduced.

The main purpose is to make sure that a new change has not negatively affected previously working functionality.

## When is Regression Testing Performed?

Regression testing is commonly performed after:

- New features are added
- Existing features are modified
- Bugs are fixed
- Code changes are made
- Configuration changes are introduced
- A new software version is released

## Example

Consider an e-commerce application.

A developer fixes a bug in the **payment module**.

After the fix, the tester should not test only payment.

The tester should also verify important existing functionality such as:

1. Login
2. Product Search
3. Product Details
4. Add to Cart
5. Checkout
6. Payment
7. Order Confirmation
8. Logout

This ensures that the payment fix has not broken another part of the application.

## Example Regression Test Cases

| Test Case ID | Functionality       | Expected Result                    |
|--------------|---------------------|------------------------------------|
| RT01         | Login               | User should login successfully     |
| RT02         | Product Search      | Relevant products should be displayed |
| RT03         | Add to Cart         | Product should be added to cart    |
| RT04         | Cart Quantity       | Quantity should update correctly   |
| RT05         | Checkout            | Checkout page should work correctly |
| RT06         | Payment             | Payment should process correctly   |
| RT07         | Order Confirmation  | Order confirmation should be displayed |
| RT08         | Logout              | User should logout successfully    |

## Regression Testing vs Retesting

| Regression Testing                                      | Retesting                                      |
|---------------------------------------------------------|------------------------------------------------|
| Checks whether existing functionality is affected by a change | Checks whether a specific defect has been fixed |
| Can cover multiple features                             | Focuses on the previously failed test case    |
| Performed after changes or fixes                        | Performed after a defect is marked fixed      |
| Uses selected existing test cases                       | Uses the failed test case again               |

## Key Point

**Retesting checks whether the defect is fixed.**
**Regression testing checks whether the fix or change has affected existing functionality.**


## Regression Testing Process

```text
New Change / Bug Fix
        ↓
Identify Affected Areas
        ↓
Select Regression Test Cases
        ↓
Execute Test Cases
        ↓
Compare Expected & Actual Results
        ↓
Report Defects
        ↓
Retest
        ↓
Regression Testing Complete
