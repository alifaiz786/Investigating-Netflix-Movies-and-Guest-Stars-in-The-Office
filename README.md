# Netflix Movie Duration Analysis

This project explores a dataset of Netflix titles to analyze trends in movie durations over time. The goal is to identify patterns in movie lengths from 2011 to 2020 and assess whether the average duration of Netflix movies has declined, as suggested anecdotally.

# Objectives

- Analyze yearly trends in Netflix movie durations
- Compare durations using both summary statistics and visualizations
- Subset and clean data from a broader dataset of Netflix titles
- Visualize movie-specific trends using line and scatter plots

# Dataset

The dataset used in this notebook is publicly available and includes metadata about Netflix titles including:
- Title
- Type (Movie or TV Show)
- Country
- Genre
- Release Year
- Duration

# Key Steps

1. Created and visualized a sample dictionary of durations over 10 years
2. Loaded and explored the full Netflix dataset from a CSV file
3. Filtered the data to include only rows where type = "Movie"
4. Selected relevant columns for analysis
5. Created line and scatter plots of movie durations over time

# Tools Used

- Python
- pandas
- matplotlib
- Jupyter Notebook

# How to Run

1. Clone this repository
2. Ensure you have the required dataset (e.g., `netflix_data.csv`) in the `datasets/` directory
3. Open the notebook `notebook.ipynb` in Jupyter
4. Run all cells to reproduce the visualizations and insights
