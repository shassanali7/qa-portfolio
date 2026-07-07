# Bug: Account Cannot Be Recreated After Deletion

## Module
Authentication / Personal Profile

## Platform
- Android

## Description
After deleting an account, attempting to recreate it using the same email results in an "account already exists" error.

## Steps to Reproduce
1. Delete an existing account  
2. Attempt to sign up again using same email  
3. Submit registration  

## Expected Result
- Account should be recreated successfully  

## Actual Result
- System shows "account already exists" error  

## Severity
Critical

## Priority
High

## Impact
- Blocks returning users  
- Causes frustration and user drop-off  

## Notes
Account deletion may not be properly handled in backend (soft delete vs hard delete issue)
