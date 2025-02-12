# Indian-Agriculture-Analysis
# Analysis of Indian Agricultural Production and Trends (1966-2017)

**Project Overview:**
This repository contains a comprehensive analysis of Indian agricultural production and trends from 1966 to 2017 in python using pandas, numpy, matplotlib, seaborn.  The analysis utilizes a district-level dataset provided by ICRISAT, encompassing area, production, and yield data for 20 major crops across India.  The project explores key trends in crop production, yield, and diversity across different states and districts, providing insights into the evolution of Indian agriculture over this period. 

**Dataset:**
The primary dataset used in this analysis is the "ICRISAT-District Level Data.csv" file.  This dataset includes annual data on area (in thousands of hectares), production (in thousands of tons), and yield (in kg per hectare) for various crops, including cereals, pulses, oilseeds, cotton, sugarcane, fruits, and vegetables, at the district level.

**Analysis Objectives:**
The project aims to address the following key questions:
* How have crop production and yield trends changed over time for major crops in India?
* What are the most productive regions for different crops, and how has this changed over the years?
* How diverse are cropping systems in different states, and what are the trends in crop diversification?
* What are the relationships between area, production, and yield for key crops?
* Are there any correlations between the adoption of High Yielding Varieties (HYVs) and improvements in yield? (Where HYV data is available)
* What are the key drivers of agricultural productivity in India? (This may involve exploring external data sources in future iterations).

**Methodology:**
The analysis employs a variety of techniques, including:
* **Data Cleaning and Preprocessing:** Handling missing values, converting units, and ensuring data consistency.
* **Descriptive Statistics:** Calculating summary statistics (mean, median, standard deviation) for key variables.
* **Time Series Analysis:** Visualizing trends in area, production, and yield over time using line plots and moving averages.
* **Geographic Visualization:** Creating choropleth maps to display the spatial distribution of agricultural production and yield across India.
* **Correlation Analysis:** Examining relationships between different variables (e.g., area vs. production, yield vs. rainfall).
* **Crop Diversity Calculation:** Quantifying crop diversity for each state and year by counting the number of distinct crops grown.
* **Statistical Modeling (Potential Future Work):** Exploring regression analysis to model the relationship between yield and other factors.

