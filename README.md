# CS4379 Assignment 1

**Student:** Rudy Rutiaga  
**Course:** CS4379G: Data Analysis & Visualization

## Overview

This repository contains my first assignment for CS4379G, demonstrating Git/GitHub workflows and Python data analysis skills. The project includes an analysis of the Netflix titles dataset, exploring trends in content types, ratings, and release patterns over time.

## Contents

- `notebooks/analysis.ipynb` - Main analysis notebook with visualizations
- `data/` - Dataset folder (Netflix titles CSV)
- `README.md` - This file

## How to Run

1. Clone this repository
2. Install required packages: `pip install pandas numpy matplotlib seaborn jupyter`
3. Open the notebook: `jupyter notebook notebooks/analysis.ipynb`
4. Run all cells

## Key Findings

- Movies outnumber TV Shows roughly 2:1 on Netflix
- TV-MA is the dominant rating for both content types
- Netflix content grew rapidly from 2015-2019 then declined in 2020
- R-rated content is almost exclusively Movies

## Step 3: Create .gitignore

Create a `.gitignore` file:
```
# Jupyter Notebook checkpoints
.ipynb_checkpoints/
*/.ipynb_checkpoints/*

# Python
__pycache__/
*.py[cod]
*$py.class
*.so
.Python

# Virtual environments
venv/
env/
ENV/

# OS files
.DS_Store
Thumbs.db

# Data files (if large)
*.csv
!data/netflix_titles.csv
