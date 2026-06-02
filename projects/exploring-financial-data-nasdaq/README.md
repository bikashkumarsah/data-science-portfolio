# Exploring Financial Data with Nasdaq Data Link

This project pulls financial table data from the Nasdaq Data Link API and analyzes company reporting trends.

## Problem

Practice authenticated API access and use retrieved financial data for exploratory analysis.

## Methods

- Send API requests with query parameters
- Parse JSON responses into tabular data
- Clean and inspect returned financial records
- Build time-series views of financial metrics
- Handle credentials without committing secrets

## Skills Demonstrated

- REST API requests
- JSON parsing
- Pandas dataframes
- Time-series visualization
- Safe API credential handling

## Dataset

- Data is retrieved live from Nasdaq Data Link.

## API Credentials

- Set `NASDAQ_API_KEY` in the environment, or copy `config.example.py` to `config.py` locally.
- `config.py` is ignored by Git so API keys are not committed.

## Files

- [analysis.ipynb](analysis.ipynb): full notebook analysis

## What This Shows

This project demonstrates working with an external data source and keeping credential handling separate from portfolio code.
