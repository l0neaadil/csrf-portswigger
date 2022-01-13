## CSRF vulnerability with no defenses [Lab 1](https://portswigger.net/web-security/csrf/lab-no-defenses)

**Key Points:**

Vulnerable parameter - email change functionality

Goal - exploit the CSRF vulnerability and change the email address

credentials - wiener:peter

Analysis:

In order for a CSRF attack to be possible:
- [x] A relevant action - email change functionality
- [x] Cookie based session handling - session cookie
- [ ] No unpredictable request parameters - satisfied

