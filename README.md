
# Boston Airbnb Data Analysis

This repository contains a Jupyter Notebook analyzing Airbnb rental pricing patterns in Boston for a Udacity project. The analysis explores factors influencing pricing, with a focus on neighborhoods as a key variable.

## Project Overview
- **Objective**: Investigate how various factors affect Airbnb rental prices in Boston.
- **Data Source**: 
    - listing.csv includes information about listings. Data scraped on **September 7, 2016**. 
    - Boston Neighborhood Boundaries Approximated by 2020 Census Block Groups are taken from 
 __[ANALYZE BOSTON](https://data.boston.gov/dataset/boston-neighborhood-boundaries-approximated-by-2020-census-block-groups1)__.
 

## Key Analysis Steps
1. **Data Cleaning**:
   - Cleaning price variables, adding neigborhood dummies, adding amenities dummies.
2. **Exploratory Data Analysis**:
   - Identified disitribution of listings, and average rental prices by visualisation.
3. **Analysis and Findings**:
   - Evaluated which features (e.g., amenities, neighborhood characteristics) have significant effects on pricing by simple regression analysis and machin learning models such as Random Forest.
   - The geographic distribution and pricing of Airbnb listings in Boston are shaped by neighborhood characteristics, and available amenities. Central neighborhoods like Downtown, Back Bay, and Beacon Hill charge the highest prices, while areas further out offer more affordable options.


## Requirements
- Python 3.7+
- Jupyter Notebook
- Libraries: `pandas`, `numpy`, `matplotlib`, `seaborn`, etc. 


## Refrences
- [Boston Airbnb Open Data](https://www.kaggle.com/datasets/airbnb/boston/data)
- [How to use Airbnb to your advantage](https://medium.com/codex/how-to-use-airbnb-to-your-advantage-f568d8a6d282)
- [A Deep Dive into Geospatial Analysis](https://github.com/ResidentMario/boston-airbnb-geo/tree/master)

This project was developed with the support of OpenAI's ChatGPT for code explanation, README file creation, and analytical guidance. ChatGPT helped streamline and clarify the project documentation.

For a detailed write-up of this project, please see the Medium blog post [here](https://medium.com/@mdizadi/boston-airbnb-neighborhoods-pricing-1783f8ea730a).