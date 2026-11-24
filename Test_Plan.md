# Test Plan

## Scope
Authentication, catalog, cart, coupons, checkout, mock payments, tracking and cancellation.

## Fictional requirements
- REQ-01: Authentication must behave according to the expected outcomes in Test_Cases.csv.
- REQ-02: Product Search must behave according to the expected outcomes in Test_Cases.csv.
- REQ-03: Cart and Coupons must behave according to the expected outcomes in Test_Cases.csv.
- REQ-04: Checkout and Payment must behave according to the expected outcomes in Test_Cases.csv.
- REQ-05: Order Tracking and Cancellation must behave according to the expected outcomes in Test_Cases.csv.

## Business rules
Quantity 1–10; SAVE10 gives 10% off subtotal of at least 200; delivery fee 30; cancellation allowed before dispatch; prepaid cancellation starts refund. Postal code must have six digits. Only order owner may access order.

## Strategy
Positive, negative, boundary, smoke and regression testing. Use synthetic accounts and mock payments only. Entry: approved requirements and available test environment. Exit: critical tests pass and defects reviewed. No execution has occurred.
