## Spotify Music Trends Analysis

## Exploratory Data Analysis of Spotify Music Dataset using Python

## Overview

This project performs **Exploratory Data Analysis (EDA)** on a Spotify music dataset using Python and visualization tools.  
The main goal is to explore music trends, understand popular artists and genres, analyze audio features (like danceability, energy, valence, tempo), and extract insights about song popularity and music characteristics over time.  
This repository includes a Colab notebook (`Spotify_EDA.ipynb`), dataset files, and images generated from the analysis.

## Dataset

+ **Dataset Source:**  
Spotify Data (1986–2023) — https://www.kaggle.com/datasets/ksuqing/spotify-data-1986-2023/data

+ Includes metadata such as:

- Track title  
- Artist  
- Release year  
- Genre  
- Popularity  
- Audio features (danceability, energy, valence, tempo, etc.)


## Tools & Libraries

- Python 3  
- Pandas for data manipulation  
- NumPy for numerical operations  
- Matplotlib / Seaborn for visualizations  
- Jupyter Notebook (Google Colab)


## Key Analyses

### 1. Basic Dataset Overview
- Load and preview the Spotify music dataset  
- Check number of rows, columns, and missing values  
- Understand data structure and types  

### 2. Distribution of Genres
- Analyzed how many tracks belong to each genre  
- Identified the most frequent genres  

### 3. Top Artists & Popular Tracks
- Ranked artists by the number of songs they have in the dataset  
- Identified most popular tracks based on the popularity metric  

### 4. Audio Feature Analysis
- Explored audio features such as danceability, energy, tempo, valence, and loudness  
- Plotted distributions and correlations between features  

### 5. Yearly Trends
- Visualized the number of songs released over years  
- Observed how characteristics like popularity or audio features changed over time  

### 6. Feature Correlation
- Created heatmaps to identify correlations between attributes  
- Analyzed relationships, e.g., between popularity & danceability  


## Key Insights

Here are some insights based on the analysis:

- Certain genres like **Pop**, **Hip-Hop**, and **Dance** appear most frequently.  
- Popular tracks often cluster around specific audio characteristics (high energy or danceability).  
- Trends over years show changes in artist prominence and audio features.  
- Correlation analysis may reveal strong links between popularity and features like tempo or valence.

 ## How to Run

1. Open Spotify dataset from kaggle on google colab.
2. Run all the cells sequentially from top to bottom.
