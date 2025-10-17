# 🎬 Netflix Exploratory Data Analysis: Content Strategy Insights

## 📌 Project Overview

This project performs an in-depth exploratory data analysis (EDA) on the Netflix dataset, which contains information about all the movies and TV shows available on the platform as of mid-2021. The primary goal is to analyze the content catalog and generate actionable insights to help Netflix make strategic decisions regarding content production, international business growth, and optimal content launch timing.

## 🤔 Business Problem

The analysis aims to answer key business questions for Netflix:

#### Content Production: 

What types of movies and TV shows should Netflix focus on producing?

#### Global Expansion:

How can Netflix effectively grow its business in different countries?

#### Launch Strategy: 

When is the best time to release new content to maximize viewer engagement?

## 📊 Dataset

The dataset used for this analysis is netflix.CSV, a tabular file containing details for over 8,800 unique movies and TV shows. The data includes attributes such as: show_id, type, title, director, cast, country, date_added, release_year, rating, duration, listed_in (genre), and description.

## 📈 Analysis & Key Findings

The analysis, detailed in the Business_Case_Final.ipynb notebook, involved several stages:

#### 1. Data Cleaning

Handled missing values in critical columns like director, cast, country, and rating to ensure data integrity.

#### 2. Exploratory Data Analysis (EDA)

###### Content Type Distribution: 
The platform has a higher proportion of Movies (approx. 69%) compared to TV Shows (approx. 31%).

###### Geographic Production: 
The United States is the largest content producer, followed by India. This highlights the importance of these markets for original content.

###### Content Growth: 
The volume of content added to Netflix saw a significant surge between 2018 and 2020.

###### Top Genres: 
Dramas, Comedies, and Documentaries are the most prevalent genres on the platform.

###### Audience Ratings: 
The majority of the content is rated TV-MA (Mature Audiences) and TV-14 (Parents Strongly Cautioned), indicating a focus on adult and young adult demographics.

## 💡 Business Recommendations

Based on the analysis, the following strategic recommendations were formulated:

Focus on International Originals: Invest heavily in producing original content in high-growth markets like India, Japan, and South Korea to cater to local tastes and expand the subscriber base.

Expand TV Show Catalog: Given the rising popularity and engagement of TV Shows (binge-watching culture), increasing the production of diverse and high-quality series is recommended.

Diversify Family-Friendly Content: The data reveals a skew towards mature content. Adding more family-friendly movies and children's shows can attract and retain family subscribers.

Leverage Top Talent: Continue collaborations with popular directors and actors who have a proven track record of successful projects, as they significantly influence viewership.

Optimize Release Schedule: Plan major content releases around peak viewing times, such as holidays and seasonal breaks, to maximize impact and engagement.

## 🚀 How to Use

To explore the analysis yourself:

Clone this repository (replace with your actual repository URL):

git clone [https://github.com/your-username/your-repo-name.git](https://github.com/your-username/your-repo-name.git)


Navigate to the project directory:

cd your-repo-name


Open the Business_Case_Final.ipynb file in a Jupyter Notebook or Google Colab environment.

Ensure the netflix.CSV dataset is in the same directory.

Run the cells sequentially to reproduce the analysis.
