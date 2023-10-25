# Electric Vehicle (EV) Adoption in Washington State: A Data Analysis Project

## Author: Yingfa Gao
## Date: April 27, 2023

---

## Overview

This project aims to analyze electric vehicle (EV) adoption in Washington State. Specifically, the project focuses on:
- The distribution of electric vehicles by city
- Top-selling EV models
- The relationship between model year and electric range
- Prediction of electric range using model year and vehicle type
- Visualization through interactive maps

The analysis aims to help understand the current state of EV adoption in Washington State and inform future policy-making and infrastructure planning.

---

## Libraries Used

The R libraries used in this project include:
- dplyr
- ggplot2
- leaflet
- stringr
- caret
- corrplot
- reactable
- reactablefmtr
- ggmap
- opencage
- maps
- formattable
- FactoMineR
- factoextra
- plotly

---

## Data Source

The data used in this project comes from a CSV file, `WashingtonEVehicle.csv`, which contains information on various aspects of electric vehicles such as model year, make, electric range, and location details like city and postal code.

---

## Analyses Performed

1. **Data Cleaning and Pre-processing**: Filtered out missing values and irrelevant columns.
2. **Top 5 Cities with the Highest EV Adoption**: Calculated and displayed in a reactable.
3. **Top 3 Models in Top 5 Cities**: Identified and displayed using the formattable function.
4. **Relationship Between Model Year and Electric Range**: Explored using a boxplot visualization.
5. **Prediction of Electric Range**: Performed linear regression using model year and vehicle type as predictors. Calculated the mean squared error and visualized residuals.
6. **Principal Component Analysis (PCA)**: Performed PCA for dimensionality reduction.
7. **Geographic Visualization**: Geocoded zip codes to obtain longitude and latitude, and visualized the distribution of electric vehicles using a leaflet map.

---

## How to Run the Project

1. Clone the repository or download the R Markdown file and the `WashingtonEVehicle.csv` data file.
2. Open the R Markdown file in RStudio.
3. Make sure you've installed all the required libraries.
4. Run the R Markdown file to generate the Slidy presentation.

---

For any additional information or clarification, feel free to contact the author.

---

