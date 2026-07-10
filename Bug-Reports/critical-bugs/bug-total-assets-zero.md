# Bug: Total Assets Showing 0

## Module
Financial Report

## Platforms
Android
iOS

## Description

The Total Assets value is incorrectly displayed as 0 in the Financial Report, even though individual assets are listed with valid values below. This creates a mismatch between the summary and detailed data.

## Steps to Reproduce
- Open Financial Report
- Locate the Total Assets section
- Compare it with the asset list displayed below

## Expected Result
Total Assets should correctly sum and display the values of all listed assets
Summary and detailed asset data should be consistent

## Actual Result
Total Assets shows 0
Asset list below contains valid values

## Severity
Critical

## Priority
Critical

## Impact
Misleading financial summary shown to users
Loss of trust in financial accuracy
Can affect decision-making based on incorrect totals

## Notes
Possible issue with calculation logic or data aggregation in the summary section