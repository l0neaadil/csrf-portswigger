## [Lab 4: CSRF where token is not tied to user session](https://portswigger.net/web-security/csrf/lab-token-not-tied-to-user-session)

**Key Points:**

Vulnerable parameter - email change functionality

Goal - exploit the CSRF vulnerability and change the email address

credentials - wiener:peter & carlos:montoya

**Analysis:**

In order for a CSRF attack to be possible:
- [x] A relevant action - email change functionality
- [x] Cookie based session handling - session cookie
- [x] No unpredictable request parameters - satisfied, csrf token is present but not tied to user session. As a result we can use other users unused csrf token.

