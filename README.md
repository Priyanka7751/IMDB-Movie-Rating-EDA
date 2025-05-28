# IMDB-Movie-Rating-EDA
🔍 Project Overview

This project presents an Exploratory Data Analysis (EDA) on the IMDb movie dataset using Python. The goal is to uncover meaningful insights about movies released between 2006 and 2016 by analyzing genres, directors, actors, revenues, and ratings. Visualizations and statistical summaries were used to identify trends in movie performance and audience reception.

📁 Dataset Information

**Source**: [IMDb Dataset on Kaggle](https://www.kaggle.com/datasets/PromptCloudHQ/imdb-data)
**Dataset Name**: IMDB-Movie-Data.csv
**Rows**: 1000 movies
**Columns**: 12 features including Title, Genre, Director, Actors, Year, Runtime, Rating, Votes, Revenue, Metascore

🛠️ Tools & Libraries Used
1. Python
2. Pandas
3. NumPy
4. Matplotlib
5. Seaborn
6. Jupyter Notebook

📈 Key Analysis Performed
1. Dropped missing/null values (mainly from Revenue column)
2. Verified column data types and checked for duplicates
3. Identified movies with longest runtimes (≥180 min)
4. Found the year with highest:
                                 4.1 Average voting
                                 4.2    Average revenue
Average movie rating
Top 10:
Lengthiest movies
Highest-rated movies and their directors
Highest revenue-generating movies
Most popular actor across movies
Most common genres and genre-wise revenue/rating analysis
Categorized movies into Excellent, Good, and Average based on ratings
Visualized relationships between:
Rating vs Revenue
Number of movies released per year
Revenue and rating distribution
