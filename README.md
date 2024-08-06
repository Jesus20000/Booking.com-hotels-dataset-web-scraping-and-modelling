# Booking.com Hotels Dataset: Web Scraping and Modelling

## Overview
This project involves web scraping hotel information from Booking.com, followed by data analysis and building predictive models for hotel prices based on the provided features. The primary goal is to explore the relationship between hotel ratings and prices, identify patterns, and develop machine learning models for predicting hotel prices.

## Libraries Used
- `requests`: For making HTTP requests to the Booking.com website.
- `BeautifulSoup`: For parsing HTML and extracting data.
- `pandas`: For data manipulation and analysis.
- `numpy`: For numerical operations.
- `matplotlib`: For plotting and visualization.
- `seaborn`: For advanced data visualization.
- `scikit-learn`: For machine learning models and evaluation.

## Data
The data is scraped from Booking.com and includes the following columns:
- `name`: Name of the hotel.
- `description`: Description of the hotel.
- `location`: Location of the hotel.
- `pricing`: Pricing of the hotel.
- `rating`: Rating of the hotel.

## Analysis Steps
1. **Web Scraping**: Extract hotel data from Booking.com.
2. **Data Cleaning**: Clean and preprocess the scraped data.
3. **Exploratory Data Analysis (EDA)**: Visualize data to identify patterns and trends.
4. **Modelling**: Train and evaluate different machine learning models to predict hotel prices.

## Insights
- **Descriptive Statistics**: Provides an overview of the data distribution.
- **Distribution Plot**: Shows the distribution of hotel prices.
- **Scatter Plot**: Explores the relationship between ratings and prices.
- **Box Plot**: Identifies outliers in pricing.
- **Model Performance**: Compares the performance of various regression models.

## Conclusion
The analysis and models provide insights into how hotel ratings impact prices and help identify patterns that can be used for predictive modeling.

## Requirements
To run this project, you need the following Python libraries installed:

- `requests`
- `beautifulsoup4`
- `pandas`
- `numpy`
- `matplotlib`
- `seaborn`
- `scikit-learn`

You can install these libraries using pip:

```bash
pip install requests beautifulsoup4 pandas numpy matplotlib seaborn scikit-learn
