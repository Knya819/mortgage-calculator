# Mortgage Calculator

## Overview

This Java application calculates the monthly mortgage payment based on user input for principal amount, annual interest rate, and loan period. It uses a standard formula to compute the mortgage payment and formats the result as currency.

## Features

- **Principal Input**: Enter the total loan amount.
- **Interest Rate Input**: Enter the annual interest rate (as a percentage).
- **Period Input**: Enter the loan term in years.
- **Mortgage Calculation**: Computes the monthly mortgage payment based on the entered values.
- **Formatted Output**: Displays the mortgage payment formatted as currency.

## How to Use

1. **Run the Application**: Execute the `Main` class in a Java runtime environment.
2. **Enter the Principal**: Input the amount of the loan.
3. **Enter the Annual Interest Rate**: Provide the annual interest rate (e.g., 5.5 for 5.5%).
4. **Enter the Period**: Specify the number of years for the loan.
5. **View the Result**: The application will calculate and display the monthly mortgage payment.

## Code Explanation

- **Imports**: Utilizes `java.text.NumberFormat` for currency formatting and `java.util.Scanner` for user input.
- **Constants**: Defines constants for the number of months in a year and percentage conversion.
- **Input Handling**: Collects user input for principal, annual interest rate, and loan period.
- **Calculation**: Computes the monthly mortgage payment using the formula:

  \[
  \text{Mortgage} = \frac{\text{Principal} \times \text{Monthly Interest} \times (1 + \text{Monthly Interest})^{\text{Number of Payments}}}{(1 + \text{Monthly Interest})^{\text{Number of Payments}} - 1}
  \]

- **Output**: Formats and prints the result as a currency string.

## Example

```bash
Principal: 200000
Annual Interest Rate: 5.5
Period: 30
Mortgage: $1132.26
