# Zomato Bangalore Restaurants Data Analysis

## Description
This project analyzes Zomato restaurant data from Bangalore to uncover trends, customer preferences, and insights about the food and restaurant industry in the city. The analysis leverages Python libraries like pandas, NumPy, Matplotlib, and Seaborn for data manipulation and visualization.

## Table of Contents
- [Introduction](#introduction)
- [Dataset Overview](#dataset-overview)
- [Data Cleaning](#data-cleaning)
- [Exploratory Data Analysis](#exploratory-data-analysis)
- [Key Insights](#key-insights)
- [Conclusions](#conclusions)
- [Requirements](#requirements)
- [How to Run](#how-to-run)
- [Future Enhancements](#future-enhancements)

## Introduction
The Zomato Bangalore dataset provides detailed information about restaurants, including their location, cuisines, ratings, price ranges, and customer preferences. This project aims to analyze this data to provide insights into:
- Customer preferences for online ordering and table booking.
- Restaurant ratings and their correlation with price range and services.
- Popular cuisines and locations for dining out.

## Dataset Overview
The dataset includes the following key features:
- `name`: Name of the restaurant.
- `location`: Area where the restaurant is located.
- `cuisines`: Types of cuisines offered.
- `online_order`: Whether the restaurant offers online ordering.
- `book_table`: Whether the restaurant allows table booking.
- `rate`: Average customer rating.
- `votes`: Number of votes received by the restaurant.


Dataset Source: [Kaggle Dataset Link](https://www.kaggle.com/datasets/himanshupoddar/zomato-bangalore-restaurants)

## Data Cleaning
- Removed duplicate entries and null values.
- Standardized inconsistent data formats.
- Filtered outliers in ratings and price ranges.

## Exploratory Data Analysis
Key visualizations and analyses include:
1. **Customer Preferences**:
   - Online Order vs Book Table trends.
   - Online Order and Book Table analysis by ratings and price range.
2. **Location Analysis**:
   - Most popular locations for dining.
   - Location-wise analysis of online ordering and table booking facilities.
3. **Cuisines and Ratings**:
   - Most popular cuisines.
   - Ratings by cuisine type.
4. **Price Range and Votes**:
   - Votes received by restaurants in different price ranges.
   - Correlation between price range and ratings.

## Key Insights 
For detailed insights and conclusions, check [INSIGHTS.md](INSIGHTS.md).

## Conclusion
This analysis provides valuable insights into customer preferences and trends in the Bangalore restaurant industry. It can help restaurant owners optimize their services and target their audience effectively.

## Requirements
- Python 3.x
- pandas
- NumPy
- Matplotlib
- Seaborn

## How to Run
1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/zomato-bangalore-restaurants-data-analysis.git
   ```
2. Navigate to the project directory:
   ```bash
   cd zomato-bangalore-restaurants-data-analysis
   ```
3. Install the dependencies:
   ```bash
   pip install -r requirements.txt
   ```
4. Open the Jupyter Notebook:
   ```bash
   jupyter notebook zomato-bangalore-restaurants-data-analysis.ipynb
   ```
5. Run the cells to reproduce the analysis.

## Future Enhancements
- Incorporate machine learning models to predict ratings based on features like location, price range, and services.
- Expand the analysis to include sentiment analysis of customer reviews.
- Compare trends across multiple cities using similar datasets.

---
Feel free to contribute to this project by submitting issues or pull requests. Your feedback is welcome!

