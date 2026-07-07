# Bug: Newly Signed-Up User Can View Other Users' Reports

## Module
Reports

## Platform
- Android

## Description
A newly registered user is able to view reports created by other users, leading to unauthorized data exposure.

## Steps to Reproduce
1. Sign up as a new Personal Profile user  
2. Navigate to the Reports page  

## Expected Result
- User should only see their own reports  
- If no reports exist, show an empty state  

## Actual Result
- Reports created by other users are visible  

## Severity
Critical

## Priority
High

## Repro Rate
Always

## Impact
- Data privacy violation  
- Sensitive information exposure  
- Security risk  

## Notes
Access control or API filtering issue suspected
