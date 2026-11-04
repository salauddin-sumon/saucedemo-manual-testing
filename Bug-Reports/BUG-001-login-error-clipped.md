# BUG-001: Login Error Message Appears Clipped

## Bug Information

- **Bug ID:** BUG-001
- **Title:** Login error message appears vertically clipped
- **Module:** Login
- **Severity:** Low (Provisional)
- **Priority:** Low (Provisional)
- **Status:** Needs Review
- **Testing Type:** UI Testing

## Environment

- **Application:** https://www.saucedemo.com/
- **Browser:** Not recorded
- **Operating System:** Not recorded
- **Browser Zoom:** Tested at 90%, 100%, 110%, and 120%

## Preconditions

- The SauceDemo login page is accessible.

## Steps to Reproduce

1. Open the SauceDemo login page.
2. Enter an invalid username and password.
3. Click the Login button.
4. Observe the error message displayed on the page.
5. Change browser zoom between 90%, 100%, 110%, and 120%.
6. Observe the error message at each zoom level.

## Expected Result

The login error message should be fully visible and readable without being clipped.

## Actual Result

The error message appears vertically clipped at the top and bottom. The message remains readable, but its full visual area is not displayed.

## Evidence

Screenshot: `BUG-001-login-error-clipped.png`

## Additional Notes

The issue was observed at multiple browser zoom levels. Further investigation is required to confirm whether this behavior violates the application's UI requirements.
