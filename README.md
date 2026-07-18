# Streaming Services and Film Trend Analysis
(Uploaded from Deepnote Notebook)

Collaborators: Sarah Kim, Nathaniel Kim, Terry Chen

## Overview

This project investigates how the rise of major streaming platforms has influenced characteristics of popular films. By combining multiple public movie datasets, we analyzed whether films available on modern streaming services differ from films released before streaming became widespread in terms of genre, runtime, ratings, and commercial success.

Rather than focusing solely on prediction, this project combines exploratory data analysis, statistical hypothesis testing, clustering, and classification to better understand how the streaming era has changed the film landscape.

---

## Datasets

This project combines three publicly available datasets:

### IMDb Dataset

Contains metadata for approximately 10,000 popular movies and television titles, including:

- Release year
- Genre
- IMDb rating
- Vote count

### Top Rated Movies Dataset

Contains highly rated films across multiple decades, including:

- Release year
- Popularity
- Vote count

### Movies on Streaming Platforms Dataset

Contains movie availability across major streaming platforms, including:

- Netflix
- Hulu
- Disney+
- Amazon Prime Video

Additional features include:

- Rotten Tomatoes score
- Runtime
- Age rating
- Streaming platform availability

---

## Research Question

**Are movies currently available on major streaming platforms different in genre and runtime compared to movies released before streaming became widespread?**

---

## Hypothesis

Movies available on major streaming platforms will naturally cluster together based on characteristics such as genre, runtime, ratings, and popularity, indicating that streaming services tend to favor films with similar attributes.

---

## Methods

### Exploratory Data Analysis

- Data cleaning and preprocessing
- Distribution analysis
- Correlation analysis
- Temporal trend visualization
- Genre comparisons

### Statistical Analysis

- Independent two-sample t-tests
- Chi-square tests of independence

### Machine Learning

#### Logistic Regression

Built a classification model to predict whether a movie belongs to the streaming era based on its characteristics.

#### K-Means Clustering

Applied unsupervised clustering to determine whether streaming-available movies naturally group together in feature space.

---

## Stakeholders

This analysis may provide useful insights for:

- Film studios
- Streaming platforms
- Content distributors
- Marketing teams

These stakeholders rely on audience trends and content characteristics to guide production, acquisition, marketing, and release strategies.

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Jupyter Notebook
