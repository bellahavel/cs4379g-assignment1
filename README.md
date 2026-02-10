# CS4379G Assignment 1 — Bella Havel

This repository contains my Assignment 1 submission for CS4379G (Data Analysis & Visualization).
It demonstrates Git/GitHub workflow (branches + PRs) and includes a notebook-based data analysis.

GitHub repo: https://github.com/bellahavel/cs4379g-assignment1

## How to run

1. Create and activate a virtual environment, then install dependencies:
   - `python -m venv .venv`
   - `source .venv/bin/activate`
   - `pip install pandas numpy matplotlib`
2. Open the notebook `notebooks/analysis.ipynb` in Jupyter or VS Code.
3. Run all cells from top to bottom.

## Key findings

- Netflix titles added per year rise sharply starting around 2016, peaking around 2019, then declining somewhat in 2020–2021.
- Typical Movie durations are measured in minutes while TV Shows are measured in seasons; medians show most TV Shows are short (often 1 season).
- Movies and TV Shows have different rating distributions: Movies dominate PG-13/R while TV Shows dominate TV-Y/TV-Y7; both peak at TV-MA/TV-14.
