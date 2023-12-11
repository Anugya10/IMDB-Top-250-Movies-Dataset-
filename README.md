# IMDB-Top-250-Movies-Dataset

🎬 Introduction

This project focuses on exploring and analyzing IMDB (Internet Movie Database) databases for movies and television shows, providing comprehensive information about movies, including ratings and reviews from its vast user base. The dataset, obtained from Kaggle, provides information about movies name, ratings, certificate provided by the Board, budget, box office, and year of the released.

🎬 Data Loading and Overview

The project begins by loading the dataset using the Pandas library. The dataset stored in a CSV file and for the quick overview of the dataset I have used "head" and "tail" function and get top and bottom 5 rows of the dataset.

🎬 Dataset Shape

The shape of the dataset is examined to understand the number of rows and columns. In this case, there are 250 rows and 13 columns.

🎬 Dataset Information

A detailed information summary of the dataset is provided, including the count of non-null values, data types of each column, and memory usage. This information is crucial for understanding the structure of the dataset. Additionally, columns with less relevance, such as 'casts', 'directors', 'writers', and 'tagline'.

🎬 Exploratory Data Analysis

📀 Average Rating of the Movies

The analysis starts by identifying the displaying the average rating of 250 movies provided by the users. After using the "Mean" method and get the result is 8.3072 is the average rating of the Top 250 movies from 1922 to 2022.

📀 Most common Genre of the Movies

Another exploration focuses on showcasing the most common genre of the movies which comes under the Top 250 movies. After the exploring and sorting the dataset "Drama" is the highest rated genre watched by the audience.

📀 Movies name released in the year

For further analysis, I have used the "def" a function to extract all the movies name released in the particular year and with the help of "value_counts" function I extracted the total count of movies in the particular year.

📀 Most common certificate given by the Board

By analyzing categories of the certificate given by the Censor Board to the Movies, after exploring the dataset and with the help of "value_counts" and "idxmax()" functions, the most common certificate is "R" for Top 250 movies.

📀 Comparison of the budget and box office

For the final analysis, for the most common factor of the movie by comparing the budget and box office collection. After exploring the dataset and by using the "def" a function and "if and Else" function. I have extracted the data and adding a new column "MovieStatus" with the help of "apply" function. After adding the new column and count the  number of Blockbuster movies which is 145 out of 250.
