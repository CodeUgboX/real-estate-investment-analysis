# Real Estate Investment Data Exploration

**Authors:** Biose Ugbo and Team

This project explores a U.S. house prices dataset from Kaggle using basic data analysis and visualization tools. The objective is to uncover patterns, trends, and insights to help a new real estate investor make informed decisions.

## 1. Understanding the Data

- **Dataset Source:** [USA House Prices on Kaggle](https://www.kaggle.com/datasets/fratzcan/usa-house-prices)

- **Time Range:** Derived from the dataset’s `date` column.

- **Geography:** Includes U.S. cities, states, and zip codes.

- **Collection Method:** Likely compiled from public real estate records and listing data.

- **Features:** Includes price, number of bedrooms/bathrooms, living area (`sqft_living`), year built, and location info.

- **Data Types:** Mixture of numerical (e.g. `price`, `sqft_living`) and categorical (e.g. `city`, `statezip`).

## 2. Data Summary & Initial Insights

- Summary statistics include mean, median, mode, range, and standard deviation for numerical columns.

- **Missing Values:** Heatmap confirmed there were no missing values in the dataset.

- **Visualizations:**

  - **Histogram:** Showed the distribution of house prices.

  - **Box Plot:** Compared price distributions in top 10 cities.

  - **Scatter Plot:** Revealed the positive relationship between price and `sqft_living`.

  - **Correlation Heatmap:** Strongest correlations found between `price` and `sqft_living`, `bathrooms`, and `sqft_above`.

## 3. Expanding Your Investment Knowledge

- **Complementary Dataset:** [Zillow Rent Index by ZIP Code](https://www.kaggle.com/datasets/ananaym/zillow-rent-index-by-zip-code)

- **Why Useful:** Provides rental income data that can be used to estimate rent-to-price ratios and ROI.

- **Complementarity:** Helps compare property values with local rental income for cash flow analysis.

## 4. Communicating Findings

- Larger homes (`sqft_living`) strongly influence house prices.

- More bathrooms are also positively associated with higher property values.

- Bedrooms showed a weaker correlation with price, suggesting size matters more than room count.

- Clean dataset enabled efficient analysis without preprocessing hurdles.

---

colab link: https://drive.google.com/file/d/1D2sNMT-JYVPmauzrnhrOPjoAPLE-BLdR/view?usp=sharing
