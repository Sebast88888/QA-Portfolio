# API Bug Reports

## BUG-001

Title: Missing required field validation

Severity: High

Priority: High

Steps:

1. Send POST request without title field.
2. Submit request.

Expected Result:
API rejects invalid request.

Actual Result:
API accepts incomplete payload.

---

## BUG-002

Title: Endpoint returns inconsistent response structure

Severity: Medium

Priority: Medium

Steps:

1. Execute GET request.
2. Compare response fields.

Expected Result:
Consistent JSON structure.

Actual Result:
Unexpected field format detected.
