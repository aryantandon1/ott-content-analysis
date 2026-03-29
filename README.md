# 🎬 OTT Content Analysis — Netflix EDA

> Exploratory Data Analysis of Netflix's content library using Python, pandas, matplotlib, and seaborn.

---

## Overview

This project analyzes **8,800+ Netflix titles** to uncover patterns in their content strategy — from genre distribution and country representation to how their library has grown over time.

It is structured across three Jupyter notebooks:
- `01_data_cleaning.ipynb` — Load, inspect, and clean the raw data
- `02_eda.ipynb` — Explore and analyze the cleaned data
- `03_visualizations.ipynb` — Generate and export publication-ready charts

---

## Key Questions Answered

- What is the split between movies and TV shows?
- Which genres dominate Netflix's catalog?
- How has the content library grown year by year?
- Which countries produce the most Netflix content?
- What does the typical Netflix movie look like (duration, rating)?
- Which directors and actors appear most frequently?
- Are there seasonal patterns in when content is added?

---

## Tools & Libraries

| Tool | Purpose |
|------|---------|
| Python 3.x | Core language |
| pandas | Data loading, cleaning, manipulation |
| numpy | Numerical operations |
| matplotlib | Charts and visualizations |
| seaborn | Heatmaps and styled plots |
| Jupyter Notebook | Interactive analysis environment |

---

## Project Structure

```
ott-content-analysis/
├── data/
│   ├── raw/
│   └── processed/
├── notebooks/
│   ├── 01_data_cleaning.ipynb
│   ├── 02_eda.ipynb
│   └── 03_visualizations.ipynb
├── plots/
├── .gitignore
├── requirements.txt
└── README.md
```

---

## Key Findings

- **Content mix:** 69.7% movies, 30.3% TV shows across 8,797 titles
- **Top genre:** International Movies leads with 2,752 titles, followed by Dramas (2,427) and Comedies (1,674)
- **Growth:** Content additions peaked in **2019** with 2,016 titles added — growth was nearly flat before 2016
- **Geography:** United States dominates with 4,513 titles. India ranks #2 with 1,046 — reflecting Netflix's heavy investment in Indian content
- **Ratings:** TV-MA is the most common rating (3,209 titles), meaning the majority of Netflix content targets adult audiences
- **Movie length:** Average movie is **99 minutes**. 18.6% run over 2 hours
- **TV Shows:** 67.3% of shows have only 1 season — Netflix heavily favours limited series over long-running shows
- **Seasonal pattern:** July is the busiest month for new releases, February the quietest
- **Top actor:** Anupam Kher appears in 43 titles — the most of any cast member on the platform
- **Top director:** Rajiv Chilaka leads with 19 titles---

## Charts

| Chart | Description |
|-------|------------|
| `plots/01_content_type.png` | Movies vs TV Shows split |
| `plots/02_top_genres.png` | Top 12 genres by title count |
| `plots/03_content_over_time.png` | Yearly content additions |
| `plots/04_top_countries.png` | Top 10 content-producing countries |
| `plots/05_movie_durations.png` | Distribution of movie runtimes |
| `plots/06_ratings_heatmap.png` | Rating breakdown by content type |
| `plots/07_monthly_additions.png` | Seasonal content release patterns |



---

## Dataset

**Netflix Movies and TV Shows** by Shivam Bansal  
Source: [Kaggle](https://www.kaggle.com/datasets/shivamb/netflix-shows)  
Size: ~8,800 titles with 12 attributes  
Note: Raw data is not committed to this repository per Kaggle's terms of use.

---

## Author

[Aryan Tandon]
