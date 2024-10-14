# Movie Analysis

## Overview
This Jupyter Notebook provides a comprehensive analysis of movies released before 2021 using a dataset sourced from Filmtv.it. The analysis aims to uncover insights about various movies based on their attributes such as genre, release year, duration, votes, and more. The goal is to help users identify trends in movie ratings, genres, and public preferences.

## Dataset
The dataset used for this analysis is titled **Films and Movies**. It contains the following columns:
- **filmtv_id**: Unique identifier for each movie.
- **title**: Title of the movie.
- **year**: Year of release.
- **genre**: Genre of the movie (e.g., Drama, Comedy, etc.).
- **duration**: Duration of the movie in minutes.
- **country**: Country where the movie was filmed.
- **directors**: Directors of the movie.
- **actors**: Main actors featured in the movie.
- **avg_vote**: Average rating of the movie (scale of 1 to 10).
- **critics_vote**: Average vote from critics (scale of 1 to 10).
- **public_vote**: Average vote from the public (scale of 1 to 10).
- **total_votes**: Total number of votes received.
- **description**: A brief description of the movie.
- **notes**: Additional notes about the movie.
- **humor**, **rhythm**, **effort**, **tension**, **erotism**: Subjective scores assigned to the movie based on various attributes.

## Installation
To run this Jupyter Notebook, you'll need the following Python libraries installed:
- NumPy
- Pandas
- Matplotlib
- Seaborn

You can install these libraries using pip:
```bash
pip install numpy pandas matplotlib seaborn
