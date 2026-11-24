# Illustrative Bug Reports

Hypothetical examples only; not observed defects.

## BUG-001 — Coupon accepted below minimum
Test: TC-030. Steps: add items worth 199; apply SAVE10. Expected: rejected. Hypothetical actual: discount applied. Severity: Medium. Status: Example only.

## BUG-002 — Duplicate order
Test: TC-039. Steps: submit checkout twice rapidly. Expected: one order. Hypothetical actual: two orders. Severity: High. Status: Example only.

## BUG-003 — Unauthorized order access
Test: TC-050. Steps: sign in as another synthetic user; request order details. Expected: access denied. Hypothetical actual: details displayed. Severity: High. Status: Example only.
