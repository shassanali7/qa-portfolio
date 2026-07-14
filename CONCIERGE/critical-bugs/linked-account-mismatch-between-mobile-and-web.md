## Bug: Linked Account Mismatch Between Mobile and Web

# Module
User Profile / Switch User

# Platform
iOS, Web

# Description
The linked account displayed on mobile differs from the one shown on the web platform, causing inconsistency in user identity and associated data.

# Steps to Reproduce
1. Login on mobile app
2. Check linked account email
3. Login on web app with same user
4. Compare linked account details

# Expected Result
Same linked account should be displayed across all platforms

# Actual Result
Mobile shows: jugrafiyag@gmail.com
Web shows: Shah.quality.assurance@gmail.com

# Severity
Critical

# Priority
High

# Impact
Data inconsistency across platforms
Potential security and account confusion issues

# Notes
Possible session/token mismatch or incorrect account mapping logic