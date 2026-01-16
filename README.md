# Big-data-analysis

*COMPANY*:CODTECH IT SOLUTIONS

*NAME*:RICHA KUMARI

*INTERN ID*:CTISAK17

*DOMAIN*:DATA ANALYST

*DURATION*:4 WEEKS

*MENTOR*:NEELA SANTOSH

# Big Data Analysis using PySpark – MovieLens 25M Dataset

## Overview
This project performs big data analysis on the MovieLens 25M dataset using PySpark. The dataset contains over 25 million movie ratings, making it suitable for demonstrating scalable and distributed data processing.

This project is submitted as part of the CodTech Internship Big Data Analysis task.

---

## Dataset
- Name: MovieLens 25M Dataset
- Source: Kaggle
- Size: 25+ million records

### Files Used
- ratings.csv (userId, movieId, rating, timestamp)
- movies.csv (movieId, title, genres)

---

## Technologies Used
- Python
- PySpark
- Apache Spark
- Google Colab

---

## Steps Performed
1. Installed and configured PySpark in Google Colab
2. Loaded large CSV files using Spark DataFrames
3. Cleaned data by removing null values
4. Joined ratings and movies datasets using movieId
5. Performed aggregation and group-based analysis
6. Derived meaningful insights from the data
7. Explained scalability of PySpark processing

---

## Analysis Performed
- Total number of movie ratings
- Top 10 most-rated movies
- Average rating per movie
- Most active users
- Genre-wise average ratings

---

## Key Insights
- The dataset contains over 25 million ratings, demonstrating large-scale data processing.
- A small number of movies receive the majority of ratings.
- Drama and Documentary genres tend to have higher average ratings.
- User activity is highly skewed, with a few users contributing many ratings.
- PySpark efficiently handles large datasets using distributed processing.

---

## Scalability
PySpark processes data in a distributed manner, allowing the same code to scale to much larger datasets by increasing computational resources without changing the logic.

---

## How to Run
1. Open the project in Google Colab
2. Install PySpark:
   pip install pyspark
3. Upload ratings.csv and movies.csv
4. Run all cells sequentially

---

## Conclusion
This project demonstrates the use of PySpark for efficient big data analysis and highlights the benefits of distributed computing for handling large datasets.
