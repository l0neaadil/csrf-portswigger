## [Lab 2: CSRF where token validation depends on request method](https://portswigger.net/web-security/csrf/lab-token-validation-depends-on-request-method)

**Key Points:**

Vulnerable parameter - email change functionality

Goal - exploit the CSRF vulnerability and change the email address

credentials - wiener:peter

**Analysis:**

In order for a CSRF attack to be possible:
- [x] A relevant action - email change functionality
- [x] Cookie based session handling - session cookie
- [x] No unpredictable request parameters - satisfied by changing Request method from POST to GET which does not require CSRF token

