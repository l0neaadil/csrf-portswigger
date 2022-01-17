## [Lab 6: CSRF where token is duplicated in cookie](https://portswigger.net/web-security/csrf/lab-token-duplicated-in-cookie)

**Key Points:**

Vulnerable parameter - email change functionality

Goal - exploit the CSRF vulnerability and change the email address

credentials - wiener:peter

**Analysis:**

In order for a CSRF attack to be possible:
- [x] A relevant action - email change functionality
- [x] Cookie based session handling - session cookie
- [x] No unpredictable request parameters - satisfied, csrf token and csrf key is present but not tied to user session. CSRF key is also injectable. We can use any value as the csrf token and csrf key.

