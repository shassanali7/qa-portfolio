## Bug: Transaction Not Updating on Mobile

# Module
Transactions / Dashboard

# Platform
iOS

# Description
Transactions added to the system are not reflected in the iOS mobile application. Despite successful additions, the mobile app fails to display updated financial records, causing inconsistency between backend/web and mobile data.

# Steps to Reproduce
1. Login to the application
2. Add a transaction:
3. $16,800 on 08/10/2024
4. $5,555 on 12/02/2025
5. Open the iOS mobile app
6. Navigate to Transactions or Dashboard

# Expected Result
* Newly added transactions should appear immediately on the mobile app
* Data should remain consistent across platforms

# Actual Result
* Transactions are not visible on mobile
* Data mismatch between web/backend and iOS app

# Severity
Critical

# Priority
High

# Impact
* Financial data inconsistency
* Loss of user trust
* Potential reporting errors

# Notes
Possible API sync issue or caching delay on mobile side