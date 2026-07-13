# Bug: Radio Buttons Linked Incorrectly Between Two Questions

## Module
Personal Profile → Site Development

## Platform
- Mobile App

## Description
Two independent questions are incorrectly linked. Selecting an option (Yes/No) in one question automatically changes the selection in the other.

## Affected Questions
- Is your location a functioning Retail Unit?  
- Is Site at intersection?  

## Steps to Reproduce
1. Navigate to Site Development section  
2. Select Yes/No for first question  
3. Observe second question  

## Expected Result
- Each question should work independently  

## Actual Result
- Selecting one option updates both questions  

## Severity
Medium

## Priority
Medium

## Impact
- Incorrect data captured  
- Breaks business logic  
- Leads to invalid reports  

## Notes
Possible shared state or incorrect binding between radio inputs
