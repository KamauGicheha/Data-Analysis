# FIFA 21 Player Data Analysis

## Overview

This project explores the FIFA 21 player dataset using Python to investigate player characteristics, performance, positions, value, wages, nationality, and geographical distribution.

The project focuses on exploratory data analysis (EDA), data cleaning, statistical relationships, and visualization.

## Dataset

The dataset contains information on **18,979 FIFA 21 players** across **77 variables**.

The data includes attributes such as:

* Player age
* Overall rating
* Potential
* Value
* Wage
* Position
* Nationality
* Pace
* Shooting
* Passing
* Dribbling
* Defending
* Physicality
* Height and weight

## Tools & Technologies

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* GeoPandas
* Jupyter Notebook

## Analysis

The analysis covers several areas:

### Data Cleaning

The original dataset required transformation of several variables, including:

* Height
* Weight
* Joined date
* Player value
* Player wage
* Release clause

These variables were converted into formats suitable for analysis.

### Player Demographics

Analysis of:

* Age distribution
* Player nationality
* Geographical distribution of players
* Player positions

### Player Performance

The project investigates relationships between player attributes and overall rating, including:

* Pace
* Shooting
* Passing
* Dribbling
* Defending
* Physicality

### Position Analysis

Player positions are compared using:

* Number of players
* Average overall rating
* Average technical and physical attributes

### Geographical Analysis

Player nationality data is combined with geographic boundary data to visualize the global distribution of FIFA 21 players.

## Key Questions

Some of the questions explored in this project include:

1. What does the age distribution of professional football players look like?
2. Which positions have the highest representation?
3. How do player attributes vary between positions?
4. Which attributes have the strongest relationship with overall rating?
5. How are FIFA 21 players distributed geographically?
6. How does player value relate to player performance?

## Project Structure

```text
fifa21/
├── README.md
├── notebooks/
├── scripts/
├── reports/
└── visualizations/
```

## Status

Completed exploratory data analysis project.

Further analysis and modeling may be added in the future.
