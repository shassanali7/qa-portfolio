## Bug: Missing Validation for SSN and Phone Number

# Module
User Profile

# Platform
Web

# Description
SSN and Phone Number fields accept invalid formats without any validation, allowing incorrect data to be saved.

# Steps to Reproduce
1. Login to application
2. Navigate to Profile Page
3. Enter invalid data in SSN and Phone fields
4. Save profile

# Expected Result
* SSN should:
1. Accept only numeric input
2. Follow valid format
3. Restrict incorrect length

* Phone number should:
1. Accept only numeric input
2. Enforce correct length
3. Validate format

# Actual Result
- Invalid inputs are accepted
- Profile updates successfully with incorrect data

# Severity
Medium

# Priority
Medium

# Impact
- Data integrity issues
- Invalid user information stored

# Notes
Validation missing on frontend and/or backend