# Unveiling_vinecultural_secrets
Insights on the different types of wines through streamlit application.

## Overview

The Wine dataset is a classic dataset in machine learning and contains the results of a chemical analysis of wines grown in a specific area of Italy. The analysis determined the quantities of 13 constituents found in each of the three types of wines.

This web application provides interactive visualizations to explore the dataset, including scatter plots to examine relationships between ingredients and bar charts showing average ingredient levels per wine type.

## Features

- **Scatter Plot:** Explore relationships between different ingredients by selecting X and Y axes.
- **Color Encoding:** Color encode data points by wine type for better visualization.
- **Bar Chart:** View average ingredient levels for each wine type using customizable bar charts.

## Usage

1. Clone the repository:
git clone <[repository-url](https://github.com/Vinothinichandrakrishnan/Unveiling_vinecultural_secrets/blob/Boss/README.md)>

2. Install the required dependencies:
   #### Dependencies:

   - Streamlit
   - Pandas
   - Pandas-Bokeh
   - Scikit-learn

3. Run the Streamlit application: Use the code in the terminal

```streamlit run yourfilename.py```

4. Open the provided URL in your web browser to access the application.

5. My streamlit URL:
     Local URL: http://localhost:8501
  Network URL: http://172.16.6.83:8501 

## Limitations

1. Data Preprocessing: Handling missing values, outliers, and categorical variables requires careful preprocessing steps to ensure accurate and meaningful results.
2. Chart Overlapping: As mentioned, when using Streamlit's sidebar for user input, both charts may overlap each other due to the fixed layout.
3. Performance Optimization: Streamlit's caching features can help improve performance by avoiding redundant computations and data reloads.

