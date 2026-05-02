# Dataquest Guided Projects

This repository is a portfolio-style collection of guided and coursework-style data science projects, including the Dataquest Data Scientist in Python path. It highlights hands-on practice in cleaning datasets, exploring questions with Python, building charts, working with APIs, and communicating findings clearly in notebooks.

## What This Repository Shows

- End-to-end notebook workflow: inspect, clean, analyze, visualize, and summarize
- Practice with survey data, app market data, school performance data, traffic data, Stack Overflow text data, movie ratings, NLP (SMS spam), trivia text data, and SQL analysis
- Growing comfort with Python, Pandas, Matplotlib, Jupyter Notebook, REST APIs, and SQL
- Consistent project organization with one folder per project and a shared raw data directory

## Tech Stack

- Python
- Pandas
- NumPy
- Matplotlib
- Jupyter Notebook
- SQL
- PostgreSQL

## Project Portfolio

| Project | Focus | Skills Highlighted |
| --- | --- | --- |
| [App Analysis](projects/app-analysis/) | Identify app profiles that are most likely to attract users in the free mobile app market | Python, CSV handling, exploratory analysis |
| [Hacker News Posts](projects/hacker-news-posts/) | Compare Ask HN and Show HN posts and find the best posting times for comments | Python, datetime analysis, aggregation |
| [eBay Car Listings](projects/ebay-car-listings/) | Clean used-car listing data and explore price patterns across brands and mileage | Pandas, data cleaning, grouped analysis |
| [Traffic Volume Analysis](projects/traffic-volume-analysis/) | Explore when highway traffic is heaviest and how time and weather affect it | Pandas, time series analysis, visualization |
| [Star Wars Survey](projects/star-wars-survey/) | Analyze survey responses to compare film rankings and viewing patterns | Pandas, survey cleaning, bar charts |
| [SAT Score Analysis](projects/sat-score-analysis/) | Combine multiple NYC school datasets to study relationships with SAT performance | Data cleaning, joins, correlation analysis |
| [Employee Exit Surveys](projects/employee-exit-surveys/) | Combine exit surveys to examine dissatisfaction by years of service | Pandas, feature engineering, pivot tables |
| [Exchange Rate Visualization](projects/exchange-rate-visualization/) | Use time-series charts to tell a story about euro-dollar exchange rates | Matplotlib, rolling averages, data storytelling |
| [SQL Window Functions](projects/sql-window-functions/) | Practice analytical SQL queries on the Northwind database using window functions | SQL, PostgreSQL, window functions |
| [Finding the Best Markets to Advertise](projects/finding-best-markets-to-advertise/) | Use the freeCodeCamp new coders survey to recommend the best countries to advertise in | Pandas, survey analysis, market prioritization |
| [Investigating Fandango Ratings](projects/investigating-fandango-ratings/) | Compare Fandango scores with other rating sites across two time periods | Pandas, comparative analysis, data storytelling |
| [Popular Data Science on Stack Overflow](projects/popular-data-science-stack-overflow/) | Explore which data science topics drive the most Stack Overflow questions | Pandas, datetime analysis, tag frequency |
| [Winning Jeopardy](projects/winning-jeopardy/) | Analyze Jeopardy clues to study word overlap and high-value vs. low-value questions | Text cleaning, Pandas, chi-square thinking |
| [Spam Filter (Naive Bayes)](projects/spam-filter-naive-bayes/) | Build a multinomial Naive Bayes classifier for SMS spam | NLP basics, train/test split, probability |
| [Lottery Addiction Mobile App](projects/lottery-addiction-mobile-app/) | Use lottery draw history to illustrate probabilities for a responsible gambling awareness angle | Probability, combinatorics, Pandas |
| [Exploring Financial Data (Nasdaq)](projects/exploring-financial-data-nasdaq/) | Pull financial table data from Nasdaq Data Link and visualize trends | REST APIs, JSON, Pandas, time series plots |

## Repository Structure

- `projects/`: one folder per guided project
- `dataset/`: shared raw datasets used by the notebooks

## API keys and secrets

- The Nasdaq Data Link project reads `NASDAQ_API_KEY` from the environment, or optionally a local `config.py` copied from `config.example.py`.
- `config.py` is listed in `.gitignore` so API keys are not committed to GitHub.

## Guided Project Note

- Many of these projects were completed as part of the Dataquest curriculum or similar guided coursework.
- I organized them into a single repository so they are easier to review as a learning portfolio.
- The goal of this repo is to show consistent practice, clean organization, and clear communication while I build stronger independent projects.
