# Bug: "Remember Me" Option Does Not Retain User Credentials

## Module
Login / Authentication

## Platform
- Mobile App

## Description
The "Remember Me" functionality does not retain user credentials after logout, even when the option is enabled.

## Steps to Reproduce
1. Navigate to Login Page  
2. Enter valid credentials  
3. Enable "Remember Me" checkbox  
4. Login successfully  
5. Logout from the application  
6. Revisit Login Page  

## Expected Result
- User credentials should persist  
- Email/username field should remain pre-filled  

## Actual Result
- Input fields are empty  
- Credentials are not retained  

## Severity
Medium

## Priority
Medium

## Impact
- Poor user experience  
- Inconvenience for returning users  

## Notes
Possible issue with local storage/session persistence handling
