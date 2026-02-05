# Amazon-Prime-TV-Shows-and-Movies

📊 Streaming Platform Content Analysis & Visualization

📌 Project Overview

This project focuses on analyzing a streaming platform’s content library to uncover key insights related to content diversity, regional availability, audience engagement, and growth trends. Using exploratory data analysis (EDA) and data visualization techniques, the project aims to understand how genres, production countries, ratings, and popularity influence subscription growth and content investment strategies in the streaming industry.

🎯 Business Objective

->The primary objective of this analysis is to support data-driven decision-making by:

->Improving user engagement and retention

->Optimizing content investment strategies

->Expanding regional and genre diversity

->Maintaining content quality while scaling the platform

📂 Dataset Description

->The dataset contains metadata related to movies and TV shows, including:

->Content details: title, type, release year, runtime, seasons

->Content classification: genres, age certification

->Regional information: production countries

->Audience metrics: IMDb score, IMDb votes, TMDB popularity and score

To enable deeper analysis, additional derived datasets were created by exploding multi-valued columns such as genres and production countries.

🔧 Data Cleaning & Feature Engineering

->Key preprocessing steps include:

->Handling missing and inconsistent values

->Converting stringified lists into Python lists

->Removing or labeling entries with missing genre information

Feature engineering:

->genre_count: number of genres per title

->country_count: number of production countries per title

->Creating exploded datasets (df_genre, df_country) for granular analysis

📊 Exploratory Data Analysis & Visualization

->The analysis includes multiple visualizations to understand relationships between variables:

->Distribution of movies vs TV shows

->Top genres and genre diversity

->Country-wise content distribution

->Content growth trends over time

->IMDb ratings and popularity analysis

Genre and regional preference patterns

Pairplot analysis to explore correlations among numerical features

Each visualization is supported with insights and business interpretations.
