## Bug: Duplicate Toast Message on Investor Creation

# Module
Project / Investor

# Platform
Web

# Description
A duplicate or incorrect toast message appears after refreshing the page when creating an investor.

# Steps to Reproduce
1. Create a new investor in a project
2. Refresh the page
3. Observe toast message

# Expected Result
- Toast message should reflect correct action
- No duplicate or misleading message should appear

# Actual Result
Toast shows incorrect or duplicate message like “User already exists in the project”

# Severity
Minor

# Priority
Medium

# Impact
- Misleading feedback to user
- Confusing UX

# Notes
Toast state not properly reset after action