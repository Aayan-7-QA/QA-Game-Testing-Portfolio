# TC-02 — Login Negative

| Field | Details |
|-------|---------|
| **ID** | QBGT-N-2 |
| **Summary** | Login button becomes inactive if wrong password was entered in password field |
| **Pre-Condition** | - |
| **Status** | Pass |

## Steps
1. Boot the title on the build 1.22
2. Tap the login button
3. Enter the correct email in email field
4. Enter the wrong password in password field

## Actual Result
Login button become inactive and the red highlighting is presented with the error message - wrong password

## Expected Result
Login button stay inactive with the red highlighting and the error message shows wrong password

## Post-Conditions
User stays on the login page
