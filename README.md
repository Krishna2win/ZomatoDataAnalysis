# Zomato Data Analysis

This repository contains a data analysis project focused on Zomato restaurant data. The project involves exploring and analyzing data to gain insights into restaurant performance, customer ratings, and other relevant metrics.

## Table of Contents
- [Introduction](#introduction)
- [Features](#features)
- [Dataset](#dataset)
- [Installation](#installation)
- [Usage](#usage)
- [Results](#results)
- [Contributing](#contributing)

## Introduction

The Zomato Data Analysis project aims to explore and visualize restaurant data to uncover patterns and insights. This analysis includes exploring customer ratings, restaurant locations, and other factors affecting restaurant performance.

## Features

- **Data Cleaning**: Preparing and cleaning the dataset for analysis.
- **Exploratory Data Analysis (EDA)**: Visualizing and understanding data patterns.
- **Feature Analysis**: Examining features such as ratings, cuisine types, and locations.
- **Visualization**: Creating visualizations to represent data insights effectively.

## Dataset

The dataset used in this project is sourced from [Zomato](https://www.zomato.com). It includes various features such as:

- **Restaurant Name**: Name of the restaurant.
- **Location**: City or locality where the restaurant is located.
- **Cuisine**: Types of cuisine offered.
- **Average Cost for Two**: Average cost for dining for two people.
- **Rating**: Customer rating of the restaurant.
- **Votes**: Number of votes received.

## Installation

To run this project locally, follow these steps:

1. Clone this repository:
   ```bash
   git clone https://github.com/Krishna2win/ZomatoDataAnalysis.git
   cd ZomatoDataAnalysis
2. Create and activate a virtual environment (optional but recommended):
   ```bash
   python -m venv venv
   source venv/bin/activate   # On Windows use `venv\Scripts\activate`
3. Install the required packages:
   ```bash
   pip install -r requirements.txt

## Usage

After installation, you can run the Jupyter notebooks provided to explore the data and analyze various aspects of the Zomato restaurant dataset. The main notebook for the project is `Zomato_Data_Analysis.ipynb`.

To start the Jupyter notebook server, run:
    ```bash
    jupyter notebook

## Results

The analysis yielded the following insights:

- **Top Rated Restaurants**: The restaurants with the highest average ratings were found to be predominantly fine dining establishments with a focus on premium cuisine.
- **Popular Cuisines**: The most popular cuisines in the dataset were Indian, Chinese, and Italian, with Indian cuisine being the most frequently mentioned.
- **Average Cost Trends**: Restaurants with higher average costs tended to have higher ratings, indicating a possible correlation between cost and quality.
- **Restaurant Distribution**: Visualizations showed a high concentration of restaurants in metropolitan areas, with a notable density in cities like Bangalore, Delhi, and Mumbai.
- **Rating Distribution**: The majority of restaurants had ratings clustered around 3.5 to 4.5, with fewer restaurants receiving very low or very high ratings.

These insights help understand the restaurant landscape, customer preferences, and geographical distribution of dining options.

## Contributing

Contributions are welcome! If you would like to contribute to this project, please follow these steps:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Make your changes and commit them (`git commit -am 'Add new feature'`).
4. Push to the branch (`git push origin feature-branch`).
5. Create a new Pull Request.

Please make sure to follow the coding style and include tests for any new features or changes.
