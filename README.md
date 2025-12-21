

<!-- Top Dashboard Gallery -->
<p float="left">
  <img src="images/distribution_of_median_house_value.png" width="45%" />
  <img src="images/median_income_vs_median.png" width="45%" />
</p>

<p float="left">
  <img src="images/median_house_value_by_ocean_proximity.png" width="45%" />
  <img src="images/distribution_by_ocean_proximity.png" width="45%" />
</p>

# CALIFORNIA-HOUSING-PRICES-

This project explores the California housing dataset to understand the factors affecting median house values. Using data visualization and analysis, key patterns and relationships are highlighted to inform data-driven decisions.

Business Problem

Housing affordability and pricing are influenced by multiple socioeconomic and geographic factors.
The objective of this analysis is to explore how variables such as median income, housing age, and location impact median house values in California districts.

This analysis aims to identify key drivers of housing prices and provide insights that could support decision-making in areas such as urban planning, real estate investment, and policy development.

Dataset Description

The dataset used in this project is the California Housing dataset, which contains housing information collected from California districts.

Each row in the dataset represents a housing district, and the columns describe various demographic and housing characteristics.

Key features include:

Median Income – Median income of households in the district

House Age – Median age of houses

Total Rooms – Total number of rooms in the district

Total Bedrooms – Total number of bedrooms

Population – Population of the district

Households – Number of households

Median House Value – Median house price (target variable)

Latitude & Longitude – Geographic location of each district

The dataset is widely used for exploratory data analysis and regression tasks in housing price studies.

Data Cleaning

Before conducting the analysis, the dataset was reviewed to ensure it was suitable for exploration and visualisation.

1. Initial Inspection

The dataset was loaded and examined to understand its structure, column names, and overall size. This confirmed that the data was correctly imported and ready for analysis.

2. Data Readiness

No significant data quality issues were observed during inspection. As a result, no rows or columns were removed, and no transformations were required.

3. Analysis Preparation

The dataset was used in its original form for exploratory data analysis to preserve the integrity of the original housing data.

Exploratory Data Analysis

Exploratory Data Analysis (EDA) was conducted to understand the distribution of variables and identify relationships between housing characteristics and median house values.

1. Distribution of Key Variables

The distributions of numerical variables such as median income, house age, total rooms, population, and median house value were examined. This helped identify general trends, skewness, and the range of values across California districts.

2. Income and House Value Relationship

Median income was analysed in relation to median house value to assess whether higher household income levels are associated with higher property prices. This relationship provided early insight into income as a key driver of housing prices.

3. Housing Characteristics Analysis

Variables such as house age, total rooms, and number of households were explored to understand how housing stock characteristics vary across districts and how they may influence house values.

4. Geographic Exploration

Latitude and longitude were used to explore geographic patterns in housing prices across California. This helped highlight regional differences and clustering of higher and lower house values.

5. Insight Preparation

The EDA findings informed the selection of visualisations and guided deeper analysis in later stages of the project.

## Visualizations

### 1. California Housing # California Housing Prices

![Distribution of Median House Value](images/distribution_of_median_house_value.png)

![Correlation Heatmap](images/median_income_vs_median.png)

![Price vs Median Income](images/median_house_value_by_ocean_proximity.png)

![Housing Map](images/distribution_by_ocean_proximity.png)

## Key Insights
- Median house value shows a strong correlation with median income and proximity to the ocean.  
- Certain features are more predictive of housing prices than others, helping focus analysis on important variables.  
- Geographical visualization highlights regional differences in house prices across California.  

---

## Technologies Used
- Python  
- Pandas, NumPy for data manipulation  
- Matplotlib, Seaborn for visualization  
- Jupyter Notebook for analysis  

---

## Conclusion
This analysis demonstrates how data visualization can uncover patterns in real estate data. Insights gained here can support investment decisions, urban planning, and understanding socio-economic trends in California housing.

  
