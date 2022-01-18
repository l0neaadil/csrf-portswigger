## [Lab 8: CSRF with broken Referer validation](https://portswigger.net/web-security/csrf/lab-referer-validation-broken)

**Key Points:**

Vulnerable parameter - email change functionality

Goal - exploit the CSRF vulnerability and change the email address

credentials - wiener:peter

**Analysis:**

In order for a CSRF attack to be possible:
- [x] A relevant action - email change functionality
- [x] Cookie based session handling - session cookie
- [x] No unpredictable request parameters - satisfied

