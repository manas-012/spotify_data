🎵 Spotify Dataset – Exploratory Data Analysis (EDA)

This repository contains a comprehensive Exploratory Data Analysis (EDA) of a Spotify dataset, performed through a structured and highly visual approach.
The objective of this project is to analyze Spotify audio features, understand popularity drivers, explore musical patterns, and uncover relationships between different attributes of songs.

The notebook is organized into clearly defined analytical phases—Univariate, Bivariate, Multivariate, and Time-Series Analysis—making it easy to navigate and understand insights step-by-step.

📘 Table of Contents

Project Objective

Dataset Description

Analysis Workflow

Data Loading & Preprocessing

Univariate Analysis

Bivariate Analysis

Multivariate Analysis

Time-Series Analysis

Key Insights

Technologies Used

How to Run

File Structure

Conclusion

🎯 Project Objective

The primary objective of this project is to perform a complete exploratory analysis of Spotify audio features to understand:

What makes songs popular

How musical attributes vary across tracks

Relationships between different audio features

Trends in music over time

Patterns that define energetic, calm, danceable, or emotional songs

The analysis aims to help beginners and intermediate learners understand the thought process behind structuring an EDA project.

📂 Dataset Description

The dataset includes multiple audio feature columns provided by Spotify’s API, such as:

danceability – How suitable a track is for dancing

energy – Intensity and activity level

valence – Musical positivity (happy vs. sad)

acousticness – Amount of acoustic sound

loudness – Overall decibel level

tempo – BPM of the track

liveness – Probability of a live performance

instrumentalness – Whether a track contains vocals

speechiness – Spoken words proportion

duration_ms – Length of the track

popularity – Popularity score assigned by Spotify

release_year – Year of song release (if available)

These features collectively allow deep musical analysis.

🔄 Analysis Workflow

The EDA notebook is divided into multiple sections to ensure clarity and progressive insight building.

🧹 Data Loading & Preprocessing

This section includes:

Importing required libraries (pandas, seaborn, matplotlib)

Loading the dataset

Inspecting dataset structure (info(), describe())

Checking for missing values

Handling duplicated records if any

Converting data types where necessary

Formatting date or year columns for time-based analysis

Goal: Ensure the dataset is clean, consistent, and ready for analysis.

📌 1. Univariate Analysis

Univariate analysis focuses on studying each feature independently to understand its distribution, behavior, and patterns.

The notebook examines:

Distribution plots for numerical features (danceability, valence, tempo, energy…)

Boxplots to identify outliers

Count plots if categorical data is present

Statistical summaries

Through this, you can understand:

Which features are normally distributed

Which features show skewness

Which ranges are most common

Whether certain attributes dominate the dataset

If any feature needs transformation or scaling

This is the foundation for more detailed analysis.

📌 2. Bivariate Analysis

Bivariate analysis explores relationships between two variables at a time.

The notebook includes:

Scatter plots (e.g., energy vs. loudness)

Regression plots (popularity vs. danceability)

Boxplots comparing audio features across categories

Correlation comparisons between pairs

Common interpreted relationships include:

Does higher danceability tend to increase popularity?

Does loudness correlate strongly with energy?

Are higher valence songs generally more popular?

Does tempo influence mood or popularity?

This section provides meaningful insights into how one feature affects another.

📌 3. Multivariate Analysis

Multivariate analysis studies multiple features together to detect deep patterns.

Key components include:

✔ Correlation Heatmap

A visual map showing correlations between all numerical features:

Helps identify which audio features move together

Detects multicollinearity

Reveals clusters of related features (e.g., loudness + energy)

✔ Pair Plots

Visual pairwise relationships across selected features:

Shows linear or non-linear patterns

Highlights natural grouping or clustering

Helps identify unusual data combinations

✔ Combined Feature Interpretations

The notebook may cover:

How energy + loudness + tempo collectively define song intensity

How valence + danceability contribute to a “happy and danceable” track

Multi-feature interactions influencing popularity

This section helps view the dataset holistically.

📌 4. Time-Series Analysis

If the dataset includes release dates or years, the notebook performs temporal trend analysis, such as:

Number of songs released each year

How audio features evolve over time

Whether modern songs are more energetic or louder

Popularity trends across decades

Changes in danceability or tempo over time

Typical visualizations:

Line plots

Rolling averages

Year-wise feature comparison

This helps understand how music has evolved.

⭐ Key Insights

The analysis helps answer questions like:

Which features are most correlated with popularity?

What makes a track energetic, calm, emotional, or danceable?

How audio features relate to each other

How modern music differs from older music

What underlying patterns define song attributes

You can also derive:

Popularity prediction indicators

Feature engineering ideas for ML projects

Trends for music recommendation systems
