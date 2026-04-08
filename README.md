# IMDb "Golden Age" TV Analysis

Data cleaning and empirical analysis of 85,579 IMDb records to test the claim that 1999–2015 represents a "Golden Age" of television. Uses rating distributions and vote counts to determine whether this era stands out statistically.

**Portfolio write-up:** [Does IMDb Agree with the 'Golden Age'? Ratings vs. Votes Analysis](https://viet-in-tech.github.io/basic-python-imdb-analysis.html)

**TripleTen Data Science Program · Sprint 3 — Basic Python**

---

## What's in This Repo

| File | Description |
|------|-------------|
| `imdb_analysis.ipynb` | Full analysis notebook — data cleaning, EDA, and conclusions |

## Dataset

- **Size:** 85,579 IMDb title records
- **Key columns:** title, year, genre, average rating, vote count
- **Source:** Publicly available IMDb datasets

## Overview

The "Golden Age of Television" is a widely cited claim in media criticism, typically referring to the prestige TV era from the late 1990s through the mid-2010s. This project asks: does the data back it up?

Using IMDb ratings as a proxy for quality and vote counts as a proxy for cultural impact, the analysis compares shows released during 1999–2015 against the full historical dataset.

## Key Questions

1. Do shows from 1999–2015 have higher average ratings than shows from other eras?
2. Does the volume of votes (audience engagement) follow the same pattern?
3. Are there genres that drive the effect?

## Tech Stack

- Python 3 · pandas
- matplotlib
- Jupyter Notebook

## Project Status

✅ Approved — TripleTen Data Science Program, Sprint 3
