# Bug: Incorrect Redirection After User Signup

## Module
Authentication / Signup

## Platform
- iOS

## Description
After successful signup, users are redirected to the Profile page instead of the Dashboard. Additionally, a Logout button is displayed unexpectedly.

## Steps to Reproduce
1. Open the app  
2. Navigate to Signup  
3. Register with valid details  
4. Complete signup  

## Expected Result
- User should be redirected to the Dashboard  

## Actual Result
- User is redirected to the Profile page  
- The logout button appears unexpectedly  

## Severity
High

## Priority
High

## Impact
- Breaks expected user flow  
- Creates confusion for new users  

## Notes
Navigation flow or post-auth routing issue suspected
