# 🎵 Music Streaming Behavior: Springfield vs. Shelbyville Analysis

## 🎯 Project Overview
This project performs a comparative analysis of listening habits between two cities using streaming platform data. The primary focus was to validate behavioral hypotheses through advanced **Data Wrangling** and descriptive statistical analysis, transforming raw data into actionable insights for content strategy.

## 🧪 Business Hypothesis
The study tested the following premise: *"User activity varies significantly depending on the day of the week and the specific geographical location."*

## 🛠️ Tech Stack & Methodology
* **Libraries:** Pandas (Dataframe manipulation), Matplotlib (Data Visualization).
* **Data Wrangling Pipeline:**
    * **Schema Standardization:** Refactored headers to consistent `snake_case` format.
    * **Data Integrity:** Implemented imputation for missing values (`NaN` -> `unknown`) in critical dimensions (artist, genre, track).
    * **Deduplication:** Removal of explicit duplicates and unification of implicit variants (e.g., merging 'hip', 'hop', and 'hip-hop' into a single genre).



## 📊 Exploratory Data Analysis (EDA)
The analysis was structured around three main pillars:

### 1. Temporal Activity by City
Custom functions were developed to filter playback volumes by day and location, revealing distinct consumption patterns.

### 2. Audience Segmentation
Identified the most popular genres in each region to understand the cultural identity of Springfield vs. Shelbyville users.

## 📈 Key Insights
* **Volume Dominance:** Springfield exhibits a more active user base with clear activity peaks on Mondays and Fridays.
* **Mid-week "Valley" Pattern:** Both cities show a significant decrease in engagement during mid-week (Wednesday).
* **Hypothesis Validation:** The study confirmed that location and temporal factors are key predictors of user engagement.

## 💡 Data Impact
This analytical pipeline enables streaming platforms to optimize recommendation algorithms and schedule content releases during high-traffic days to maximize reach and user retention.
