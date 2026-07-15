## Bug: Reports Search Filter Logs Out User

# Module
Reports

# Platforms
iOS

# Description
Opening the search filter shows an invalid error, and tapping OK logs the user out.

# Steps to Reproduce
1. Login as personal user
2. Go to Reports page
3. Tap Search filter
4. Tap OK on error

# Expected Result
Search filter should open normally

# Actual Result
User is logged out

# Severity
Critical

# Priority
High

# Impact
- Breaks core feature
- Causes unexpected session loss

# Notes
Possible session/token handling issue