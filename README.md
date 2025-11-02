# 🎬 IMDB Movie Ratings Analysis

**Exploratory analysis and interactive dashboard for IMDB movie ratings using Python (Pandas, Seaborn, Matplotlib, Streamlit).**

## 🔎 Project Overview
This project performs end-to-end Exploratory Data Analysis (EDA) on a movie ratings dataset (IMDB). It includes data cleaning, summary statistics (mean/median/mode), visualizations (histogram, boxplot, bar charts, correlation heatmap), identification of top-rated movies and genres, and a simple interactive dashboard built with Streamlit.

## ✅ Features
- Clean and preprocess movie dataset (remove duplicates, convert data types, parse runtime/genre)
- Compute summary statistics: mean, median, mode of ratings
- Visualizations:
  - Ratings distribution (histogram + KDE)
  - Rating boxplot
  - Top genres by count
  - Average rating by genre
  - Correlation heatmap (rating, votes, year, runtime)
- Identify top-rated movies and popular genres
- Mini dashboard in the notebook + Streamlit app for interactive exploration
- Deliverables: Jupyter Notebook, PDF report, PPT slides, Streamlit app

## 📁 Repository Structure
movie-ratings-analysis-imdb/
├── data/
│ └── movies.csv # raw dataset (or link)
├── notebook/
│ └── eda_final.ipynb # final notebook with EDA & dashboard cells
├── app/
│ └── streamlit_app.py # simple Streamlit explorer
├── presentation/
│ └── Movie_Ratings_Presentation.pptx
├── report/
│ └── Movie_Ratings_Project_Report.pdf
├── README.md
└── LICENSE
