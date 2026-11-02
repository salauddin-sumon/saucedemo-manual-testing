# TC-001: Empty Login Validation

- **Module:** Login
- **Test Type:** Functional Testing
- **Priority:** High
- **Precondition:** The SauceDemo login page is open.

## Test Steps

1. Leave the Username field empty.
2. Leave the Password field empty.
3. Click the Login button.

## Expected Result

The application should prevent login and display a validation message indicating that a username is required.

## Actual Result

The application displayed: `Epic sadface: Username is required`

## Status

**PASS**
