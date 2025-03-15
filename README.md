# Economic and Fast Food Price Correlation Analysis

## Overview
This repository contains an analysis of economic factors and their correlation with fast food prices across different states in the U.S. The dataset has been compiled from various sources, cleaned, and analyzed to visualize relationships between variables such as average income, cost of living, GDP, and fast food prices.

## Repository Contents
- **`fast_food_analysis.csv`**: The compiled dataset containing economic indicators and fast food prices for all 50 states.
- **`my_datatable.ipynb`**: A Jupyter Notebook with the code used to compile individual dataframes into the final dataset. Also used to perform the correlation analysis and generates a heatmap to visualize relationships between different factors.
- **`correlation_between_economic_factors_and_restaurant_prices.png.`**: The generated heatmap showing correlation values between economic indicators and fast food prices.

## Dataset Description
The dataset includes the following variables:
- **Economic Indicators**
  - `AverageIncome`: The average income in each state.
  - `MedianIncome`: The median income in each state.
  - `CostOfLiving`: A cost-of-living index for each state.
  - `MinimumWage`: The minimum wage in each state.
  - `GDP`: The gross domestic product of each state.
  - `GDPGrowth`: The GDP growth rate for each state.
  - `UnemploymentRate`: The unemployment rate in each state.
- **Fast Food Prices**
  - `DominosMedCheese`: The price of a medium cheese pizza from Domino's.
  - `McDonaldsHappyMeal`: The price of a Happy Meal from McDonald's.
  - `McDonaldsBigMac`: The price of a Big Mac from McDonald's.
  - `ChickfilAChickenSandwich`: The price of a Chick-fil-A Chicken Sandwich.
  - `TacoBellComboMeal`: The price of a combo meal from Taco Bell.

## Correlation Analysis
A correlation heatmap was generated to identify relationships between economic indicators and fast food prices. Some key findings:
- **Average Income and Fast Food Prices**: Higher average income is positively correlated with higher fast food prices, suggesting that states with higher earnings tend to have more expensive fast food.
- **Cost of Living and Fast Food Prices**: Strong correlation, indicating that in states where living expenses are higher, fast food is also more expensive.
- **GDP and Fast Food Prices**: States with a higher GDP tend to have higher fast food prices, showing an overall economic impact on food costs.
- **Minimum Wage and Fast Food Prices**: Positive correlation, meaning states with higher minimum wages generally have pricier fast food items.

## Usage
To reproduce the analysis:
1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/economic-fastfood-correlation.git
   cd economic-fastfood-correlation
   ```
2. Open the Jupyter notebooks (`data_compilation.ipynb` and `correlation_analysis.ipynb`) to explore the data and generate visualizations.
3. Run the Python scripts to regenerate the correlation heatmap if needed.

## License
This project is licensed under the MIT License. Feel free to use and modify the dataset and code.

---
If you have any questions or suggestions, feel free to reach out!