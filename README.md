# Spotify_Audio_features_EDA

## Project Overview

This project performs an **Exploratory Data Analysis (EDA)** on Spotify songs using their audio features. The objective is to understand how musical characteristics such as danceability, energy, loudness, valence, tempo, and acousticness influence song popularity and identify patterns within the dataset. Spotify audio features provide quantitative measures of a track's musical properties, making them valuable for music recommendation systems, trend analysis, and machine learning applications. 

## Dataset Description

The dataset contains Spotify track information along with various audio features generated through Spotify's music analysis system. Common attributes include:

| Feature          | Description                                  |
| ---------------- | -------------------------------------------- |
| Danceability     | Measures how suitable a track is for dancing |
| Energy           | Represents intensity and activity level      |
| Loudness         | Overall track loudness in decibels           |
| Speechiness      | Presence of spoken words                     |
| Acousticness     | Confidence that a track is acoustic          |
| Instrumentalness | Likelihood of having no vocals               |
| Liveness         | Probability of a live performance            |
| Valence          | Musical positivity or happiness              |
| Tempo            | Estimated beats per minute (BPM)             |
| Popularity       | Spotify popularity score (0–100)             |

These features are widely used for music analysis and recommendation systems. ([Hugging Face][1])

## Objectives

* Understand the structure of Spotify audio features.
* Analyze distributions of numerical variables.
* Detect missing values and outliers.
* Explore relationships between audio features.
* Identify factors affecting song popularity.
* Visualize trends and correlations.
* Generate insights for future machine learning models.

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Jupyter Notebook

## EDA Process

### 1. Data Collection

* Load Spotify dataset.
* Inspect dataset dimensions and data types.

### 2. Data Cleaning

* Handle missing values.
* Remove duplicates.
* Check for inconsistent data.

### 3. Univariate Analysis

* Distribution of popularity scores.
* Histograms of audio features.
* Summary statistics.

### 4. Bivariate Analysis

* Correlation between popularity and audio features.
* Scatter plots and box plots.
* Feature relationship analysis.

### 5. Multivariate Analysis

* Correlation heatmap.
* Pair plots.
* Feature interaction analysis.

### 6. Insights Generation

* Most popular audio characteristics.
* Relationships among energy, danceability, and valence.
* Trends affecting listener engagement.

## Key Visualizations

* Histogram of Popularity
* Correlation Heatmap
* Boxplots for Outlier Detection
* Scatter Plots
* Pairplots
* Feature Distribution Graphs


## Conclusion

This EDA project provides valuable insights into Spotify audio features and their relationship with song popularity. The analysis helps understand music trends and lays a foundation for advanced machine learning applications such as recommendation engines and popularity prediction models. ([GitHub][3])

