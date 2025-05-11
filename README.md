# Netflix-Data-Cleaning-Analysis-and-Visualization
# Netflix Data Analysis & Recommendation System

## Project Overview
This project provides an in-depth analysis of Netflix's content library using Python. It covers various aspects of data cleaning, feature engineering, data visualization, and a content-based recommendation system.

The project aims to uncover key insights about the Netflix catalog, identify trends, and demonstrate the power of a machine learning recommendation system.

## Key Features
- **Data Cleaning**: Preparing raw data for analysis by handling missing values, duplicates, and irrelevant columns.
- **Feature Engineering**: Creating new features to better understand the data and improve model performance.
- **Data Visualization**: Using graphs and charts to explore key trends, distributions, and relationships in the data.
- **Recommendation System**: Implementing a content-based filtering model using TF-IDF and cosine similarity to recommend similar movies based on genre and director.

## Key Insights
1. **Content Composition**: Movies dominate Netflix’s catalog, with TV shows forming a strong secondary presence.
2. **Genre Distribution**: Dramas, comedies, and documentaries are the most prevalent genres, reflecting popular viewer preferences.
3. **Ratings Breakdown**: A significant portion of content is tailored for mature audiences, highlighting Netflix's target demographic.
4. **Global Footprint**: The dataset is heavily represented by content from the United States, India, and the UK.
5. **Temporal Trends**: Content additions surged between 2018–2020, aligning with Netflix's global expansion and pandemic-driven demand.
6. **Duration Patterns**: Movie durations typically range between 60–120 minutes, with notable outliers.
7. **Actor Frequencies**: A small group of actors appear across multiple titles, indicating prolific careers or frequent collaborations.
8. **Genre Trends**: Genre preferences have shifted over time, providing insights into evolving audience interests.

## Recommendation System
A content-based filtering model was implemented to recommend similar titles based on genre and director similarity. The model utilizes TF-IDF (Term Frequency-Inverse Document Frequency) and cosine similarity to identify and suggest similar movies.

## Setup Instructions

### Prerequisites
- Python 3.x
- Required Python libraries:
  - pandas
  - numpy
  - matplotlib
  - seaborn
  - scikit-learn
  - nltk

You can install the required libraries using `pip`:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn nltk
Made by - Rishav Kumar Sharma (Data Analyst)
