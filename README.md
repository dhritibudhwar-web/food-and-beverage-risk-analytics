# Food & Beverage Risk Snapshot

This project is a lightweight financial risk review tool based on SEC filing data for food and beverage companies.

It is designed to turn a set of filing-based financial data points into a simple company snapshot that is easier to read than raw statements alone.

## Project Files

- `index.html`: the main page that displays the company list, financial metrics, and risk signals
- `food-beverage-dataset.json`: the underlying dataset used by the page

## How The Risk View Works

The project reads the financial data from the JSON file and shows a simple review for each company.

The signals are based on a small set of core checks:

- liquidity
- leverage
- equity position
- profitability
- filing context

## Risk Strategy

The risk view is meant to act as a quick screening layer rather than a full credit model or investment opinion.

The page highlights companies where the financial statements suggest:

- weak short-term balance sheet coverage
- high leverage
- negative equity
- weak or negative profit margin
- limited context from quarterly rather than full-year figures

## What The Output Is Meant To Do

The purpose of the output is to make it easier to review a company quickly, compare companies within the same industry group, and identify areas that may deserve deeper analysis.

## Note

This project is a simplified analytical tool built from selected financial statement items. The signals should be treated as a starting point for review, not a final conclusion.
