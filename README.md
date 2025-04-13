# Spotify Top 50 Songs Analysis (2020)

This project explores the **Top 50 most popular Spotify songs of 2020**, focusing on their audio features using pandas in Python. 
The analysis was done using Jupyter Notebook and Google Colab, without any visualizations — the focus was on understanding 
the data through code, filtering, grouping, and correlation.

## Project Goals:
* Analyze audio features such as danceability, energy, loudness, acousticness, etc.
* Compare genres to understand which musical characteristics are most common in the Top 50.
* Identify correlations between features (e.g., energy and loudness).
* Practice real-world data analysis using pandas.

## Key Insights:
* **Pop** is the most frequent genre in the Top 50, followed by **Hip-Hop/Rap**.
* **Dance/Electronic and Hip-Hop/Rap** songs have the highest danceability scores.
* **Energy and loudness** show a strong positive correlation (0.79), while **energy and acousticness** are strongly negatively correlated (-0.68).
* Most other features have weak or no correlation, suggesting they vary independently.

## Tools Used:
* Python & pandas
* Jupyter Notebook / Google Colab
* Dataset: [Kaggle - Top 50 Spotify Songs of 2020](https://www.kaggle.com/datasets/atillacolak/top-50-spotify-tracks-2020)
