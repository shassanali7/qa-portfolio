## Bug: Profile Image Not Syncing Across Platforms

# Module
User Profile

# Platform
iOS, Web

# Description
Profile image uploaded via iOS app does not reflect on the web platform, causing inconsistency in user profile data.

# Steps to Reproduce
1. Login to iOS app
2. Upload a profile image
3. Login to web platform with same account
4. Check profile image

# Expected Result
* Profile image should sync across platforms

# Actual Result
* Image updates on mobile only
* Web still shows old/default image

# Severity
Major

# Priority
Medium

# Impact
* Data inconsistency
* Poor cross-platform user experience

# Notes
Possible issue with API sync or storage update