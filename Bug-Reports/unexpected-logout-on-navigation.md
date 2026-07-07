# Bug: User Gets Logged Out When Pressing Back from Dashboard

## Module
Authentication / Session Management

## Platform
- Mobile App

## Description
When the user presses the back button from the dashboard screen, the app logs the user out unexpectedly and redirects to the mobile homepage.

## Steps to Reproduce
1. Login to the application  
2. Navigate to Dashboard  
3. Press the back button  

## Expected Result
- User should remain logged in  
- App should navigate to previous screen or prompt confirmation  

## Actual Result
- User is logged out  
- Redirected to mobile homepage  
- App must be reopened  

## Severity
Critical

## Priority
High

## Impact
- Breaks user session unexpectedly  
- Causes major frustration  
- Interrupts app usage  

## Notes
Possible issue with session handling or back navigation logic
