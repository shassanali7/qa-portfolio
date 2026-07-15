## Bug: Deleted User Cannot Re-signup (Email Already Exists)

# Module
Authentication / Signup

# Platforms
iOS

# Description
When a user deletes their account and tries to sign up again using the same email, the system incorrectly shows "Email already exists".

# Steps to Reproduce
1. Signup with a new email
2. Delete the account
3. Try to signup again using the same email

# Expected Result
- User should be able to register again after deletion

# Actual Result
- System blocks signup with "Email already exists"

# Severity
Critical

# Priority
High

# Impact
- Blocks user re-registration
- Causes major user frustration
- Impacts user retention

# Notes
Likely backend soft-delete or flag issue