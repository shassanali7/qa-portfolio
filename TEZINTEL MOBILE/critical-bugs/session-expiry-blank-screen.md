# Bug: Blank Screen Displayed on Session Expiry

## Module
Session Management / Entire App

## Platform
- Mobile App

## Description
When the user session expires, the application displays a blank white screen without any message or redirection, leaving the user stuck.

## Steps to Reproduce
1. Login to the app  
2. Wait until session expires  
3. Return to app or perform any action  

## Expected Result
- User should be redirected to login screen  
- Proper message like “Session expired. Please login again.” should be displayed  

## Actual Result
- Blank white screen appears  
- No message or guidance  
- On refresh → user gets logged out with toast  

## Severity
Critical

## Priority
Critical

## Impact
- Completely breaks app usability  
- Confuses users  
- Poor session handling experience  

## Notes
Session timeout handling or navigation fallback is missing
