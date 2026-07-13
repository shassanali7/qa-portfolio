## Bug: Profile Page Flicker Showing Incorrect User Data

## Module
Profile / Edit Profile

## Platform
- Android

## Description
While navigating to the Edit Profile screen or cancelling/updating changes, the Profile page briefly flickers and displays another user's (Moid’s) name and email.

## Steps to Reproduce
1. Login as any user
2. Navigate to Profile Page
3. Tap on Edit Profile
4. Cancel or update profile
5. Observe transition

## Expected Result
- No flicker should occur
- Only logged-in user’s data should be displayed

## Actual Result
- Brief flicker shows another user's (Moid’s) name and email

## Severity
Minor

## Priority
Medium

## Impact
- Potential data privacy concern
- Reduces trust in application

## Notes
Possible issue with cached state or improper data binding during screen transition