# Week  10 — Data Loading Test Development

## Objective
Create assert statements to test a CSV financial data loading function.

## User Prompt
"Create assert statements to test my data loading function with:
- Valid CSV data
- CSV with dollar signs in amounts
- Missing values and invalid data
- Empty files and corrupted data
Verify that cleaning works correctly and errors are handled gracefully."

## Work Completed
- Built tests for valid CSV loading
- Added tests for dollar-sign cleaning
- Added malformed data validation
- Tested empty file handling
- Verified graceful error handling

## Key Learnings
- CSV parsing can fail due to malformed formatting
- Financial systems require strict validation
- User-friendly errors improve usability

## Challenges
- Handling commas inside currency values
- Preventing crashes from corrupted files

## Solution
Used:
```python
pd.to_numeric(errors="coerce")
```

to safely convert invalid values into NaN.