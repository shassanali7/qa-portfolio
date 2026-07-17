## Bug: Switch Account Shows Unauthorized Accounts

# Module
Account Switching

# Platform
Web

# Description
Unapproved linked accounts are visible in the “Switch Account” dropdown even though they are not accessible due to missing admin approval.

# Steps to Reproduce
1. User A sends account linking request to User B
2. Admin does not approve the request
3. Login as User A
4. Open “Switch Account” dropdown

# Expected Result
- Only approved linked accounts should be visible in the dropdown

# Actual Result
- Unapproved linked accounts are visible
- User cannot switch to those accounts

# Severity
Medium

# Priority
Medium

# Impact
- Confusing user experience
- Misleading account visibility

# Notes
If visibility is intentional, consider adding a “Pending Approval” label to differentiate status