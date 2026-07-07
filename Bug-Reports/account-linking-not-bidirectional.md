# Bug: Account Linking Not Working Bidirectionally Between Users

## Module
Account Sharing / Linked Accounts

## Platforms
- Android
- iOS

## Description
When User A shares their account with User B, User B is unable to link their account back to User A. This breaks the expected bidirectional account linking functionality.

## Steps to Reproduce
1. Login as User A  
2. Share account with User B  
3. Login as User B  
4. Attempt to link account with User A  

## Expected Result
- User B should be able to link their account with User A  
- Account linking should work bidirectionally between users  

## Actual Result
- User B cannot link their account with User A  
- Linking works only in one direction  

## Severity
High

## Priority
High

## Impact
- Breaks core account sharing functionality  
- Causes confusion in multi-user scenarios  
- Limits collaboration features  

## Notes
Possible issue with account linking logic, permissions, or backend validation for reciprocal linking
