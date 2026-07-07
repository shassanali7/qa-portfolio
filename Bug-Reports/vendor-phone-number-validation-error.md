# Bug: Incorrect Phone Number Validation for Selected Country

## Module
Vendor Profile

## Platform
- Android

## Description
The phone number field intermittently shows an error: "Invalid phone number for the selected country" even when a valid number is entered.

## Steps to Reproduce
1. Navigate to Vendor Profile  
2. Enter a valid phone number based on selected country  
3. Observe validation message  

## Expected Result
- Valid phone numbers should be accepted  

## Actual Result
- Incorrect validation error is displayed  

## Severity
High

## Priority
High

## Impact
- Blocks user progress  
- Causes frustration  
- Affects onboarding and profile updates  

## Notes
Possible issue with country code validation logic or regex mismatch
