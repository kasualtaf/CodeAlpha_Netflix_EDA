# Netflix Movies and TV Shows - Exploratory Data Analysis

## Project Description
This project is an Exploratory Data Analysis (EDA) of the Netflix Movies and TV Shows dataset. The goal is to uncover insights regarding Netflix's content library, including trends in content addition, geographic distribution, ratings, and popular genres. 

This beginner-friendly project demonstrates the use of Python and popular data science libraries to clean, analyze, and visualize data without relying on advanced statistical methods or machine learning models.

## Dataset Information
The dataset used in this project is `netflix_titles.csv`, which contains details about all the movies and TV shows available on Netflix, including:
- `show_id`: Unique ID for every Movie / Tv Show
- `type`: Identifier - A Movie or TV Show
- `title`: Title of the Movie / Tv Show
- `director`: Director of the Movie
- `cast`: Actors involved in the movie/show
- `country`: Country where the movie/show was produced
- `date_added`: Date it was added on Netflix
- `release_year`: Actual Release year of the movie/show
- `rating`: TV Rating of the movie/show
- `duration`: Total Duration - in minutes or number of seasons

## Installation Steps
1. Clone this repository or download the project files.
2. Ensure you have Python installed on your system.
3. Install the required libraries using `pip`:
   ```bash
   pip install -r requirements.txt
   ```
4. Navigate to the `notebook` directory and launch Jupyter Notebook:
   ```bash
   cd notebook
   jupyter notebook Netflix_EDA.ipynb
   ```

## Project Screenshots
*Placeholders for visualizations generated in the notebook:*
- ![Number of Movies vs TV Shows](../images/movies_vs_tv_shows.png)
- ![Top 10 Countries](../images/top_countries.png)
- ![Content Added Over Years](../images/content_added.png)
- ![Distribution of Ratings](../images/distribution_ratings.png)

## Directory Structure
```
CodeAlpha_EDA_Netflix/
│
├── dataset/
│   └── netflix_titles.csv
│
├── notebook/
│   └── Netflix_EDA.ipynb
│
├── images/
├── README.md
├── requirements.txt
└── LICENSE
```
