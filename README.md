# Simple Interest Calculator
 
A lightweight, terminal-based Bash script that computes simple interest based on user inputs for principal, annual rate of interest, and time period. 

This project was developed as part of a final practical assessment to demonstrate proficiency with GitHub UI workflows and Git CLI operations.

## Description

The script calculates simple interest using the standard formula:

$$A = P(1 + rt)$$

Where:
*   `P` = Principal amount
*   `r` = Annual interest rate (in decimal form)
*   `t` = Time period (in years)

## Features

*   **Interactive CLI:** Prompts the user directly for necessary financial inputs.
*   **Instant Calculation:** Outputs the calculated total simple interest and total final balance dynamically.
*   **Bash Native:** Runs directly in any standard Unix/Linux terminal environment without external dependencies.

## Inputs

The calculator requires the following parameters:
1.  **Principal:** The initial amount of money loaned or invested.
2.  **Rate of Interest:** The annual interest percentage (e.g., enter `5` for 5%).
3.  **Time Period:** The duration of the loan or investment in years.

## Usage

Ensure the script has executable permissions before running it:

```bash
chmod +x simple-interest.sh
./simple-interest.sh
