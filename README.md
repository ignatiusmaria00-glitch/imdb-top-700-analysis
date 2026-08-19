 IMDb Top 700 Movies: Exploratory Data Analysis & Trends

An end-to-end data analytics project exploring genre dynamics, audience engagement, and critical rating distributions across top-rated films on IMDb.

Project Overview
This project performs data cleaning, feature engineering, and exploratory data analysis (EDA) on an IMDb movie dataset of 700 top-rated films. The goal is to uncover structural patterns driving critical acclaim and audience engagement across different film eras.

Tools & Technologies
Language: Python 3.x
Libraries: Pandas, NumPy, Matplotlib, Seaborn
Environment: Jupyter Notebook / Anaconda
Version Control: Git & GitHub

Key Findings & Insights

Genre Dominance: Drama is by far the most represented genre, appearing in 473 out of 700 movies (67.5% of the entire dataset).
Critical Acclaim: Biography achieves the highest average IMDb rating (8.04), closely followed by Drama (8.03) and Animation (8.02).
Audience Engagement: Adventure leads in total audience votes, averaging 659,000 votes per movie, followed by Action (595,000 votes).
  Film Runtimes:The mean runtime across the top 700 movies is 127 minutes, ranging from 68 minutes to 321 minutes.

Visualizations

 1. Top 10 Genres by Movie Count
[Top 10 Genres](top_10_genres.png)

 2. Rating Distribution Across Decades
[Ratings Across Decades](ratings_by_decade.png)

Repository Structure

├── IMDb_Top_700_Movies_2026.xlsx  # Raw dataset
├── cleaned_imdb_movies.csv        # Cleaned & transformed dataset
├── imdb_top_700_analysis.ipynb    # EDA & Data Cleaning Notebook
├── top_10_genres.png              # Exported chart
├── ratings_by_decade.png          # Exported chart
└── README.md                      # Project documentation
