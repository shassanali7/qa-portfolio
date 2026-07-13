# Bug: Inconsistent Vendor Onboarding Flow Between Android and iOS

## Module

Vendor Signup / Onboarding / Dashboard

## Platform

- Android
- iOS

## Description

There is an inconsistency in the vendor onboarding experience between Android and iOS platforms after first login.

- On Android: User is shown only the vendor form on first login.
- On iOS: User is shown the vendor form along with navigation tabs. The Leads tab displays an onboarding screen ("Hang on tight..."), while the Dashboard shows leads and services count as 0.

This results in different user experiences and unclear onboarding flow across platforms.

## Steps to Reproduce

1. Login as a new Vendor user (first-time login)
2. Observe the initial screen and navigation behavior

## Expected Result

* Both Android and iOS should follow the same onboarding flow
* User should either:

  - Only see the vendor form until completion, OR
  - See a consistent UI with restricted access and onboarding messaging
* Navigation tabs behavior should be consistent across platforms

## Actual Result

* Android:

  - Only vendor form is displayed
  - No navigation tabs visible

* iOS:

  - Vendor form is displayed along with navigation tabs
  - Leads tab shows onboarding screen ("Hang on tight...")
  - Dashboard shows leads and services count as 0

## Severity

Major

## Priority

High

## Impact

* Confusing and inconsistent user experience across platforms
* Misleading data visibility (Dashboard showing 0 values before approval)
* Breaks expected onboarding flow logic

## Notes
Possible mismatch in platform-specific UI implementation or conditional rendering logic for onboarding state
