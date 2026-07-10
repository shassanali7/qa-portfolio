# Bug: Input Validation Missing Across Multiple Modules

## Module
- Login  
- Sign Up  
- Forgot Password  
- Contact Us  
- Vendor Profile  

## Platform
- Mobile App

## Description
Input field validation is missing or inconsistent across multiple modules. Fields accept invalid or empty data without proper validation or error messages.

## Steps to Reproduce
1. Navigate to any listed module  
2. Enter invalid or empty input  
3. Submit the form  

## Expected Result
- Required field validation should be enforced  
- Proper format validation (email, phone, etc.)  
- Clear error messages should be shown  

## Actual Result
- Invalid/empty inputs are accepted  
- No validation or feedback is provided  

## Severity
Medium

## Priority
Medium

## Impact
- Data integrity issues  
- Poor user experience  
- Risk of invalid data in system  

## Notes
Validation rules are either missing or not consistently implemented
