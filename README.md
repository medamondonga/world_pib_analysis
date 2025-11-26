# Global GDP Evolution Analysis (1980–2023)

This project explores the evolution of countries’ GDP between 1980 and 2023. It follows a complete data pipeline: data extraction, cleaning, and exploratory analysis. The goal is to visualize long-term economic trends and identify countries that have dominated global GDP over several decades.

Project Structure
## 1. Scraping

Notebook: scrapping.ipynb

Source: the Wikipedia page listing global GDP by country.

Work done:

Automated extraction of the GDP table.

Initial formatting and conversion of the collected data.

Output file: pib_data.csv.

## 2. Cleaning

Notebook: cleaning.ipynb

Work done:

Standardization of column names.

Conversion of GDP values into numeric format.

Handling missing values and inconsistencies.

Output file: pib_data_cleaned.csv.

## 3. Exploratory Data Analysis (EDA)

Notebook: eda.ipynb

Work done:

Analysis of GDP evolution from 1980 to 2023.

Visualizations of GDP trends for major countries.

Comparisons across multiple decades.

Key insight: the United States consistently dominates global GDP throughout the entire period.

## Data

The cleaned dataset used for the analysis is stored in:

pib_data_cleaned.csv

## Project Goal

Build an end-to-end data workflow (scraping → cleaning → analysis) and explore global economic trends over more than forty years.

## Technologies Used

Python

Pandas

BeautifulSoup / Requests

Matplotlib / Seaborn

Jupyter Notebook

## Result

The analysis highlights long-term economic patterns since 1980 and shows how certain countries—especially the United States—maintain a dominant position over the years.
