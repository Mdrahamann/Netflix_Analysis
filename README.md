📌 Overview
This project explores the Netflix Movies & TV Shows dataset using Python in Google Colab.
The goal is to analyse content trends on Netflix, including the distribution of movies vs TV shows, top content‑producing countries, popular genres, release year patterns, and rating distributions.

📁 Dataset
The dataset contains information about titles available on Netflix, including:

Title

Type (Movie or TV Show)

Director & Cast

Country of production

Date added to Netflix

Release year

Rating

Duration

Genre (listed_in)

Description

🔍 Key Questions
This analysis answers several important questions:

How many Movies vs TV Shows are on Netflix?

Which countries produce the most content?

What are the most common genres?

How has Netflix content grown over the years?

What does the rating distribution look like?

📈 Analysis & Visualisations
The project includes:

Countplot of Movies vs TV Shows

Bar chart of top 10 content‑producing countries

Bar chart of most common genres

Line chart of release year trends

Rating distribution visualisation

All visualisations were created using Matplotlib and Seaborn.

🧹 Data Cleaning
Steps included:

Removing duplicates

Handling missing values

Stripping inconsistent date formats

Converting date_added to datetime

Basic text cleaning

🛠️ Tools & Technologies
Python

Google Colab

Pandas

NumPy

Matplotlib

Seaborn

📝 Summary of Insights
Netflix has more Movies than TV Shows.

The United States produces the most content.

Drama, International Movies, and Comedies are the most common genres.

Content production increased significantly after 2015.

Most titles are rated TV‑MA or TV‑14, indicating a focus on mature audiences.

📂 Project Structure
Code
Netflix-Analysis/
│── netflix_titles.csv
│── Netflix_Analysis.ipynb
│── README.md
