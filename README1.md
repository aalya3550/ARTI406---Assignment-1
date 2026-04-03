# ARTI406 - Assignment 1: Exploratory Data Analysis (EDA)
# Netflix Movies and TV Shows 

## 1. Dataset Source
- **Source:** Kaggle (Netflix Movies and TV Shows dataset)
- **Link:** https://www.kaggle.com/datasets/shivamb/netflix-shows


## 2. Project Overview
This project performs a comprehensive Exploratory Data Analysis on the Netflix Movies and TV Shows dataset to uncover insights about global content trends.


## 3. Purpose of Using this Dataset
The purpose is to analyze Netflix’s content library to find trends in production over time, identify the most popular genres, and understand the distribution of content across different countries to provide insights into streaming strategies.


## 4. Dataset Information
- **Original Size:** 998 rows and 12 columns.
- **Key Features:** `show_id`, `type`, `title`, `director`, `cast`, `country`, `date_added`, `release_year`, `rating`, `duration`, `listed_in`, `description`.


## 5. Description of Features (Columns)
1. **show_id:** Unique ID for every movie/show.
2. **type:** Category of the content (Movie or TV Show).
3. **title:** Name of the movie/show.
4. **director:** Director of the movie/show.
5. **cast:** Actors involved in the movie/show.
6. **country:** Country where the content was produced.
7. **date_added:** Date it was added on Netflix.
8. **release_year:** Actual release year of the movie/show.
9. **rating:** TV Rating of the movie/show (e.g., PG, TV-MA).
10. **duration:** Total duration (minutes or number of seasons).
11. **listed_in:** Genre/Category.
12. **description:** Brief summary of the content.


## 6. Data Preprocessing & Cleaning
To ensure high-quality analysis, the following steps were taken:
- **Missing Value Analysis:** Identified significant gaps in 'director' and 'cast' columns using `isnull().sum()`.
- **Data Cleaning:** Removed rows with null values to maintain a consistent dataset for visualization.
- **Verification:** Confirmed zero null values using a Heatmap and summary statistics.

## 7. Visualizations & Insights
The analysis includes 10 professional visualizations covering:
- Content distribution (Movies vs TV Shows).
- Top producing countries (USA, India, UK, etc.).
- Rating distributions (Target audience analysis).
- Content growth trends from 1925 to 2021.
- Genre popularity and Director contributions.

## 8. Tools Used
- **Language:** Python
- **Libraries:** Pandas, Matplotlib, Seaborn, numpy
- **Environment:** Google Colab / VS Code