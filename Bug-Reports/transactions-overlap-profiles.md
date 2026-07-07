# Bug: Transactions Overlapping Between Overall Profile and Subprofiles

## Module
Concierge Mobile Application

## Platforms
- Android (v1.0.1)
- iOS (v1.4)

## Description
Transactions created under the overall profile and subprofiles are being displayed across both, causing unintended data overlap. This results in incorrect transaction visibility between profiles.

## Steps to Reproduce
1. Create transactions under the overall profile
2. Create separate transactions under one or more subprofiles
3. Navigate to the transaction history of the overall profile
4. Navigate to the transaction history of any subprofile

## Expected Result
- The overall profile should display only its own transactions  
- Each subprofile should display only its respective transactions  
- No overlap should occur between profiles  

## Actual Result
- Transactions are displayed in both the overall profile and subprofiles  
- Data overlap occurs across profiles  

## Severity
High

## Priority
High

## Impact
- Causes user confusion  
- Leads to inaccurate financial tracking  
- Affects data integrity across profiles  

## Notes
Possible issue with data filtering or profile-based transaction mapping
