# NYC Airbnb Analysis: A Personal Project

![Project Image](https://img.shields.io/badge/MachineLearning-Python-blue)

## Overview

As an international student, finding a place to live in New York City has been a personal challenge. The high rents, the fierce competition, and the diversity of neighborhoods make it a daunting experience. This project stems from my own struggles navigating the NYC rental market, and it focuses on analyzing Airbnb data to better understand pricing trends, popular neighborhoods, and more.

The project uses **Pyspark**, **Pandas**, **Matplotlib**, and **Seaborn** for data analysis, visualization, and modeling, providing insights into the NYC Airbnb market.

The key sections of the project include:
- **Data Preprocessing**
- **Exploratory Data Analysis (EDA)**
- **Modeling: Logistic Regression, Random Forest Classification, Decision Trees**


## Table of Contents
1. [Installation](#installation)
2. [Data Preprocessing](#data-preprocessing)
3. [Exploratory Data Analysis](#exploratory-data-analysis)
4. [Modeling](#modeling)
   - Logistic Regression
   - Random Forest
   - Decision Trees
5. [Conclusion](#conclusion)
6. [Usage](#usage)
7. [License](#license)

## Installation

To run this project locally, clone the repository and install the required dependencies.

```bash
git clone https://github.com/your-username/NYCAirbnbAnalysis.git
cd NYCAirbnbAnalysis
pip install -r requirements.txt
```

## Data Preprocessing

The dataset includes Airbnb listings in New York City, and the preprocessing involves:
- Handling missing values
- Encoding categorical variables (such as neighborhood groups)
- Scaling numerical features like price and availability
- Splitting the data into training and testing sets

## Exploratory Data Analysis

Several visualizations are created to explore the data, including:
- **Price Distribution Across Neighborhoods**: Identifying which areas have the highest and lowest listings.
- **Room Type Distribution**: Analyzing the proportion of room types such as entire homes, private rooms, etc.
- **Price Heatmaps**: Visualizing price trends across different boroughs.

## Modeling

### Logistic Regression

Logistic regression is used to classify whether a listing is affordable or expensive based on various features like neighborhood, room type, and price.

### Random Forest

A Random Forest model was trained for classification, showing better performance than Logistic Regression. Feature importance analysis helped identify key drivers of Airbnb pricing.

### Decision Trees

A Decision Tree model is also used to classify pricing and understand the most influential factors in determining Airbnb prices.

## Conclusion

This analysis of Airbnb listings in NYC provides insights into the city’s rental market and offers practical tools for prospective renters. By using this project, others may better understand the dynamics of Airbnb pricing in New York City, particularly for students and people new to the area.

## Usage

To replicate this analysis or adapt it to another city:
1. Download the Airbnb dataset for your desired location.
2. Open the `NYCAirbnbAnalysis.ipynb` notebook.
3. Run each cell sequentially, following along with the comments.
4. Modify the dataset or features as needed to adapt the models.