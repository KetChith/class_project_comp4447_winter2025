# Assessing the Impact of Drought on Corn and Soybean Productivity

## Instructions  
1. Run **`ket_poungnachith_project.ipynb`** to execute the analysis.  
2. Ensure that **no unrelated CSV files** are saved in the directory, as the code will **override existing files**, potentially leading to inaccurate results.  
3. Install all required packages as listed in the **`requirements.txt`** file before running the project.
4. Note: it takes about 5min to run **`ket_poungnachith_project.ipynb`**

## System Requirements¶
This project requires Google Chrome to run Selenium WebDriver.

## Install Google Chrome in WSL:
Run the following commands in your WSL terminal:

```bash
wget https://dl.google.com/linux/direct/google-chrome-stable_current_amd64.deb
sudo apt update
sudo apt install -y ./google-chrome-stable_current_amd64.deb
google-chrome --version
```

## Project Structure
├── README.md                        # Project documentation (this file)

├── ket_poungnachith_project.ipynb   # Jupyter notebook for analysis

├── requirements.txt                 # Dependencies and required libraries

## Overview
This project investigates the relationship between drought severity (measured using the Drought Severity and Coverage Index, DSCI) and crop yields and prices for corn and soybeans in five U.S. states. The analysis includes exploratory data analysis (EDA), hypothesis testing, and regression modeling to determine if drought significantly affects agricultural markets.

## Project Goals
* Analyze trends in crop acreage, yield, and price over time.
* Assess the impact of drought on crop prices and yields using T-tests, Mann-Whitney U tests, and regression analysis.
* Investigate adjusted yield and price metrics by normalizing values based on drought severity.
* Identify key factors influencing price and yield variations.
* Propose improvements for further research and analysis.

## Data Sources
* Crop Data: USDA National Agricultural Statistics Service (NASS)
* Drought Data: U.S. Drought Monitor (DSCI values)

## Key Findings
* No strong evidence that drought significantly affects price or yield under normal drought conditions.
* More noticeable effects when prices and yields are adjusted for drought severity (DSCI-adjusted values).
* Extreme drought years (e.g., 2012) show a potential threshold where drought may start affecting agricultural markets.
* Technological advancements (e.g., irrigation, drought-resistant seeds) likely mitigate the impact of drought.
* Future improvements include multicollinearity analysis (VIF), refining regression models, and incorporating external economic factors.

## Next Steps & Future Improvements
* Refine regression models by removing non-significant variables.
* Check for multicollinearity using Variance Inflation Factor (VIF).
* Expand dataset to analyze longer historical trends.
* Include additional variables such as government subsidies, international trade, and technology advancements.
* Explore machine learning approaches for better predictive modeling.
