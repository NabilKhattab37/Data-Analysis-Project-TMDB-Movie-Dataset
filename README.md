# Data Analysis Project: TMDB Movie Dataset

This README provides an overview of the data analysis project conducted on the TMDB Movie Dataset. The project aims to explore and analyze various aspects of movies, including popularity, budget, profits, and more. Below, you will find information on the project's structure, objectives, data sources, and key findings.

## Table of Contents

- [Introduction](#introduction)
- [Project Structure](#project-structure)
- [Objectives](#objectives)
- [Data Sources](#data-sources)
- [Project Steps](#project-steps)
- [Key Findings](#key-findings)
- [Limitations](#limitations)
- [Dependencies](#dependencies)
- [How to Run](#how-to-run)
- [Contributing](#contributing)
- [License](#license)

## Introduction

The TMDB Movie Dataset analysis project is an exploration of movie data, focusing on various aspects such as popularity, budget, release years, profits, and more. By conducting this analysis, we aim to gain insights into the factors that influence a movie's success and to answer specific questions related to the dataset.

## Project Structure

The project is structured as follows:

- **Data Wrangling**: In this phase, we cleaned and prepared the dataset for analysis. We addressed missing data, removed duplicates, and selected relevant columns.

- **Exploratory Data Analysis (EDA)**: This phase involved answering specific questions about the dataset through visualizations and calculations. We explored factors like movie popularity, budget, release years, profits, and more.

- **Conclusions**: We summarized the key findings from the analysis and drew conclusions based on the data.

## Objectives

The primary objectives of this project were to:

1. Identify the top 10 most popular movies in the dataset.
2. Determine the top 10 movies with the highest budgets.
3. Find the year with the most number of movie releases.
4. Identify the top 5 years with the highest total movie budgets.
5. Discover the top 10 movies with the highest profits.
6. Find the top 10 movies with the longest runtime.
7. Identify the top 10 directors with the most movies in the dataset.
8. Explore the factors that affect movie profits through correlation analysis.

## Data Sources

The dataset used in this analysis is the TMDB Movie Dataset. It contains information about thousands of movies, including details such as title, budget, revenue, runtime, release year, and more.

## Project Steps

The project followed these key steps:

1. Data Wrangling: Cleaning and preparing the dataset for analysis.
2. Exploratory Data Analysis: Answering specific questions using visualizations and calculations.
3. Conclusions: Summarizing the key findings and drawing conclusions based on the analysis.

## Key Findings

Some of the key findings from the analysis include:

- "Jurassic World" is the most popular movie in the dataset.
- "The Warrior's Way" has the highest budget among all movies.
- The year 2011 had the most movie releases (199).
- The year 2013 had the highest total movie budgets.
- "Star Wars" and "Avatar" are the most profitable movies.
- "Carlos" is the movie with the longest runtime.
- Steven Spielberg directed the most movies in the dataset.
- Factors like runtime, vote average, and budget have weak correlations with profits, while popularity is positively correlated with profits.

## Limitations

- Budgets and revenues are adjusted to inflation to the year 2010 to ensure consistent comparisons.
- Rows with zero or negative budget or revenue values were removed, potentially impacting the dataset's representativeness.

## Dependencies

To run this project, you will need the following dependencies:

- Python
- Pandas
- Matplotlib
- Seaborn

## How to Run

To reproduce the analysis:

1. Download the TMDB Movie Dataset (CSV format) or use your own dataset.
2. Open the Jupyter Notebook or Python script used for this analysis.
3. Make sure you have the required dependencies installed.
4. Follow the code and comments in the notebook/script to perform the data analysis.

## Contributing

Contributions to this project are welcome! If you have ideas for improvements, additional analyses, or new questions to explore, feel free to contribute. Please follow the guidelines for contributions in the repository.

## License

This project is licensed under the [MIT License](LICENSE). You are free to use, modify, and distribute the code and findings as long as you provide appropriate attribution and adhere to the terms of the license.