# Login Bug Reports

## BUG-001

**Title:** Error message overlaps login form on small screen

**Severity:** Medium

**Priority:** Medium

**Steps to Reproduce:**

1. Open login page
2. Enter invalid credentials
3. Reduce browser width

**Expected Result:**
Error message remains readable.

**Actual Result:**
Message overlaps form elements.

---

## BUG-002

**Title:** Password field accepts leading spaces

**Severity:** Low

**Priority:** Low

**Steps to Reproduce:**

1. Enter password with leading spaces
2. Submit login

**Expected Result:**
Leading spaces should be trimmed.

**Actual Result:**
System processes spaces as valid characters.
