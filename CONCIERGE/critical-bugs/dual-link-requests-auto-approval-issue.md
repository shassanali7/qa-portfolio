## Bug: Dual Link Requests Auto-Approval Issue

# Module
Account Linking / Admin Approval

# Platform
Web

# Description
When two users send linking requests to each other, approving one request automatically approves the reverse request without explicit admin action.

# Steps to Reproduce
1. User A sends request to User B
2. User B sends request to User A
3. Admin approves A → B request
4. Check B → A request

# Expected Result
Each request should require independent approval

# Actual Result
Reverse request is automatically approved

# Severity
Critical

# Priority
High

# Impact
Breaks approval workflow
Security & permission risk

# Notes
Backend logic flaw in relationship handling