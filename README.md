# Cricket Stats Analyzer

A Python CLI tool that loads, cleans, and analyzes cricket player statistics using Pandas and NumPy.

## What it does

- Loads raw player stats from CSV (with realistic missing data)
- Cleans missing values using column means (and zero-fill where appropriate)
- Answers key questions from the data:
  - Best batting average
  - Team with the most combined runs
  - Best strike rate among players with 40+ matches
  - Average centuries across all players
  - Full player ranking by runs
- Cross-verifies Pandas aggregations against NumPy calculations

## Tech stack

- Python
- Pandas
- NumPy

## Final output: 

```notebook-python
=== Cricket Stats Report ===
Best average: Virat
Team with most runs: India
Best strike rate (40+ matches): Warner
Average number of centuries: 3.67
      player    runs
0      Virat  2400.0
1      Rohit  2100.0
2      Babar  2050.0
3     Warner  1900.0
4       Root  1850.0
8    Buttler  1798.0
11  Mitchell  1798.0
6      Smith  1780.0
5       Kane  1700.0
9      Rahul  1600.0
7     Rizwan  1500.0
10    Bavuma  1100.0
```
