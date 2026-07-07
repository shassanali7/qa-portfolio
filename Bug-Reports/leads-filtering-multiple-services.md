# Bug: Leads Filtering Incorrect When Multiple Services Selected

## Module
Vendor Profile → Leads

## Platform
- Mobile App

## Description
When multiple services are selected in Vendor Profile, the Leads page does not correctly filter results. Leads with only one service are also displayed.

## Steps to Reproduce
1. Navigate to Vendor Profile → Edit Profile  
2. Select multiple services (e.g., Financial + Real Estate)  
3. Go to Leads page  

## Expected Result
- Only leads matching ALL selected services should be shown  

## Actual Result
- Leads with partial match are displayed  
- Filtering behaves inconsistently  

## Severity
High

## Priority
High

## Impact
- Incorrect data visibility  
- Affects vendor decision-making  
- Reduces trust in system  

## Notes
Filtering logic likely using OR instead of AND condition
