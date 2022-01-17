## [Lab 5: CSRF where token is tied to non-session cookie](https://portswigger.net/web-security/csrf/lab-token-tied-to-non-session-cookie)

**Key Points:**

Vulnerable parameter - email change functionality

Goal - exploit the CSRF vulnerability and change the email address

credentials - wiener:peter & carlos:montoya

**Analysis:**

In order for a CSRF attack to be possible:
- [x] A relevant action - email change functionality
- [x] Cookie based session handling - session cookie
- [x] No unpredictable request parameters - satisfied, csrf token and csrf key is present but not tied to user session. CSRF key is also injectable. As a result we can use other users csrf token and csrf key.

