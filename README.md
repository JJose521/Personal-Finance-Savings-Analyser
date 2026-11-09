# Personal Finance & Savings Analyser

## Project Overview

A MATLAB-based financial analysis tool designed to analyse monthly income, expenses and savings, forecast savings growth, and compare different financial scenarios.

This project demonstrates fundamental programming, data analysis, financial modelling and data visualisation skills using MATLAB.

The program uses fictional financial data stored in an external CSV file.

## Key Features

- **CSV Data Import:** Reads financial information from an external CSV file using `readtable()`.
- **Data Validation:** Checks for invalid financial inputs, including negative values, missing data and mismatched array lengths.
- **Financial Analysis:** Calculates total income, total expenses, total savings, average monthly savings and savings rates.
- **Data Visualisation:** Generates graphs showing monthly income, expenses and cumulative savings.
- **Savings Forecasting:** Estimates how many months are required to reach a specified savings goal.
- **Scenario Analysis:** Compares conservative, average and optimistic monthly savings strategies.

## Technologies Used

- MATLAB
- MATLAB Online
- CSV files
- MATLAB tables
- Data visualisation and financial modelling

## Example Results

Using six months of fictional financial data:

| Financial Metric | Result |
|---|---|
| Total Income | £6,200 |
| Total Expenses | £3,600 |
| Total Savings | £2,600 |
| Average Monthly Savings | £433.33 |
| Overall Savings Rate | 41.94% |
| Savings Goal | £5,000 |

### Savings Scenario Comparison

| Scenario | Monthly Savings | Months to Goal |
|---|---|---|
| Conservative | £300 | 8 |
| Current Average | £433.33 | 6 |
| Optimistic | £600 | 4 |

These forecasts assume constant monthly savings and exclude interest, inflation and unexpected expenses.

## How to Run

1. Download the MATLAB script and sample CSV file.
2. Place both files in the same project folder.
3. Open the MATLAB script in MATLAB or MATLAB Online.
4. Configure the CSV file path if required.
5. Run the script to generate financial calculations, tables and graphs.

## Skills Demonstrated

- MATLAB programming
- Data importing and processing
- Input validation
- Numerical calculations
- Data visualisation
- Financial forecasting
- Scenario modelling
- Problem-solving and debugging

## Future Improvements

- User-defined financial inputs
- Automated financial reporting
- Additional financial forecasting models
- Interactive user interface
- More advanced financial data analysis

## Disclaimer

This project is intended for educational and portfolio purposes. All financial data is fictional and does not constitute financial advice.