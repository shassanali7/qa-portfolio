# Bug: Phone Number Gets Reset Repeatedly in Profile

## Module
Profile

## Platform
- Android

## Description
The phone number field in the user profile is being cleared/reset repeatedly. Users are required to re-enter their phone number every time they access or update their profile.

## Steps to Reproduce
1. Login to the app  
2. Navigate to Profile  
3. Enter phone number and save  
4. Revisit Profile screen  

## Expected Result
- Phone number should remain saved  
- User should not need to re-enter it  

## Actual Result
- Phone number is cleared/reset  
- User must enter it again  

## Severity
High

## Priority
High

## Impact
- Poor user experience  
- Data persistence issue  
- Reduces user trust  

## Notes
Possible issue with data saving or API response handling
