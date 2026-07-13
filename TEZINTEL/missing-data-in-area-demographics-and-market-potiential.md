# Bug: Missing Data in Area Demographics & Market Potential (Report PDF)

## Module
Reports → Generated PDF → Area Demographics & Market Potential

## Platform
- Web (PDF Export)

## Description
The generated PDF report fails to display data in the Area Demographics & Market Potential section. Multiple pages (23–28) contain missing or empty values for key demographic and financial metrics, resulting in an incomplete and unreliable report.

## Steps to Reproduce
1. Generate a report using valid site selection inputs
2. Wait for the report generation process to complete
3. Download or open the generated PDF
4.  Navigate to pages 23–28

## Expected Result
- All demographic and financial data should be displayed correctly across pages 23–28
- No fields should appear empty

## Actual Result
- Page 23:
Monthly Income → Missing
Homeownership Percentage → Missing
- Page 24:
Total Population → Missing
Workers in Area → Missing
Household Population → Missing
Population Density → Missing
- Page 25:
Average Home Value → Missing
% Income for Mortgage → Missing
Households by Income Base → Missing
Median Household Income → Missing
- Pages 26–28:
Additional demographic and market data missing
Entire section shows empty/null values

## Severity
Critical

## Priority
High

## Impact
- Report becomes unreliable for decision-making
- Affects business credibility and client trust

## Notes
Possible issue with backend data mapping or API response not being rendered in PDF