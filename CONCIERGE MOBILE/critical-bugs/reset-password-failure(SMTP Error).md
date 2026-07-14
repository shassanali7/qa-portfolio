## Bug: Reset Password Failure (SMTP Error)

# Module
Authentication → Reset Password

# Platform
iOS

# Description
Users are unable to reset their password due to an SMTP authentication error (535). The reset email is not sent, blocking users from recovering their accounts.

# Steps to Reproduce
1. Open the app
2. Click on “Forgot Password”
3. Enter a valid email address
4. Submit the request

# Expected Result
* Password reset email should be sent successfully
* User should be able to proceed with password recovery

# Actual Result
* Error occurs: SMTP authentication failure (535)
* No reset email received

# Severity
Critical

# Priority
High

# Impact
* Users are completely locked out of their accounts
* High risk of user frustration and churn

# Notes
Likely backend email configuration issue → escalate to backend team