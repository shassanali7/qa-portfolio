## Bug: Country Flag Missing / Incorrect in Phone Number Field

## Module
Profile Page

## Platform
- Android
- iOS

## Description
The country flag associated with the phone number field is inconsistent across platforms.

## Steps to Reproduce
1. Login as Personal User
2. Navigate to Profile Page
3. Check phone number section
4. Go to Edit Profile
5. Change country flag
6. Save changes and return

## Expected Result
- Correct selected country flag should be displayed consistently on all platforms

## Actual Result
- Android: No country flag displayed
- iOS: Incorrect (US) flag shown even after updating

## Severity
Major

## Priority
High

## Impact
- Incorrect localization information
- Confusing user experience

## Notes
Possible issue with country code mapping or UI rendering inconsistency