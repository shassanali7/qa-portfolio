# Bug: Vendor ID Does Not Accept Valid Pakistani Phone Number

## Module
Signup - Vendor

## Platform
- Android

## Description
The Vendor ID field does not accept valid Pakistani phone numbers during signup. Even correctly formatted numbers are rejected with a validation error.

## Steps to Reproduce
1. Open the app on Android  
2. Select Vendor Signup  
3. Enter a valid Pakistani phone number (e.g., 03XXXXXXXXX or +923XXXXXXXXX)  
4. Submit the form  

## Expected Result
- The system should accept valid Pakistani phone number formats  

## Actual Result
- A validation error is shown  
- Valid numbers are rejected  

## Severity
High

## Priority
High

## Repro Rate
Always

## Impact
- Blocks vendor registration  
- Prevents onboarding  

## Notes
Validation rules for accepted phone number formats are unclear or incorrectly implemented
