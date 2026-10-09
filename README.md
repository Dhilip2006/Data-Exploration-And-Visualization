# Exoplanet and Astronomical Data Analysis

# Project Overview

This capstone project explores and visualizes astronomical data related to exoplanets using Python. The project applies concepts from all five units of the **Data Exploration and Visualization** course to discover patterns, analyze planetary characteristics, and understand trends in exoplanet discoveries.

The analysis uses data from the **NASA Exoplanet Archive** and demonstrates data preprocessing, statistical analysis, visualization, correlation analysis, and machine learning.

## Objectives

- Explore and understand an astronomical dataset.
- Clean data by handling missing values, duplicates, and inconsistent data types.
- Perform univariate, bivariate, and multivariate analysis.
- Visualize exoplanet properties and discovery trends.
- Analyze relationships between planetary and stellar characteristics.
- Apply Principal Component Analysis (PCA) and machine learning techniques.

## Dataset

- **Source:** [NASA Exoplanet Archive](https://exoplanetarchive.ipac.caltech.edu/)
- **Domain:** Astronomy and space science
- **Data includes:** Planet names, discovery methods, discovery years, orbital periods, planetary radii, masses, densities, and host-star properties.

## Technologies Used

- **Python**
- **Pandas** – Data manipulation and cleaning
- **NumPy** – Numerical computation
- **Matplotlib** – Data visualization
- **Seaborn** – Statistical visualization
- **SciPy** – Statistical analysis
- **Scikit-learn** – PCA and machine learning
- **Plotly** – Interactive visualizations

## Course Units Covered

|            Unit                   |                         Concepts Applied                                                     |  
|-----------------------------------|----------------------------------------------------------------------------------------------|
| Unit 1: Exploratory Data Analysis | Data loading, cleaning, missing values, duplicates, filtering, grouping, and transformations |
| Unit 2: Data Visualization        | Line charts, scatter plots, histograms, density plots, error bars, subplots, and 3D plots    |
| Unit 3: Univariate Analysis       | Descriptive statistics, frequency distributions, quartiles, skewness, and outlier detection  |
| Unit 4: Bivariate Analysis        | Pearson and Spearman correlation, scatter plots, grouped charts, and violin plots            |
| Unit 5: Multivariate Analysis     | Pair plots, correlation heatmaps, PCA, and machine learning                                  |

## Key Analysis Performed

1. Dataset overview and data quality assessment.
2. Missing-value and duplicate analysis.
3. Trends in exoplanet discoveries over time.
4. Distribution of planetary radii and orbital periods.
5. Comparison of exoplanet discovery methods.
6. Correlation analysis between planetary characteristics.
7. Outlier detection using the Interquartile Range (IQR).
8. Multivariate analysis using pair plots and heatmaps.
9. Dimensionality reduction using PCA.
10. Exploration of discovery-method classification using a Random Forest model.

## Project Structure

```text
Data-Exploration-And-Visualization/
│
├── Exoplanet_and_Astronomical_Data_Analysis.ipynb
├── README.md
└── Exoplanet and Astronomical Data.csv
```

## How to Run the Project

1. Clone or download this repository.
2. Download the required dataset from the [NASA Exoplanet Archive](https://exoplanetarchive.ipac.caltech.edu/).
3. Open the notebook using Google Colab or Jupyter Notebook.
4. Upload the dataset or update the CSV file path in the notebook.
5. Install any missing dependencies:

   ```bash
   pip install pandas numpy matplotlib seaborn scipy scikit-learn plotly
   ```

6. Run the notebook cells sequentially to perform the analysis and generate visualizations.

## Expected Outcomes

- Better understanding of exoplanet discovery patterns.
- Insights into the distributions and relationships of planetary properties.
- Identification of data-quality issues and potential outliers.
- Visual summaries of astronomical data.
- Practical experience applying statistical analysis, dimensionality reduction, and machine learning.

## Academic Context

**Project Type:** Capstone Project  
**Course:** Data Exploration and Visualization  
**Domain:** Astronomy and Data Science

## Acknowledgements

The project uses publicly available astronomical data from the NASA Exoplanet Archive.

---

⭐ *This project demonstrates the application of Python-based data exploration, statistical methods, and visualization techniques to real-world astronomical data.*
