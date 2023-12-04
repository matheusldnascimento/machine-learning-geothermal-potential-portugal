# machine-learning-geothermal-potential-portugal

Machine Learning analysis of geothermal potential in Portugal.

## Overview

This project was undertaken as part of my Master's degree in Geospatial Technologies. Combining ArcGIS Pro and Python, I conducted a comprehensive study on geothermal potential in Portugal. The dataset was constructed using geospatial data from various public sources, including geological, geophysical, weather, and soil data.

## Workflow

1. **Data Preparation:**
   - Geospatial data from public sources was organized and compiled in ArcGIS Pro.
   - Features were generated, and the data was structured into vector grids of two different spatial resolutions (5x5 km² and 2.5x2.5 km²).

2. **Modeling in Python:**
   - Utilized Python libraries such as Pandas, Scikit-learn, and XGBoost.
   - Created machine learning models (Random Forests and XGBoost) to predict geothermal potential.
   - Implemented GridSearch CV, feature selection, and outlier elimination to optimize model performance.

3. **Integration with ArcGIS:**
   - Exported the predicted potential for the entire area back to ArcGIS.
   - Constructed maps illustrating the predicted geothermal potential for each model outcome.

4. **Training Data:**
   - Utilized a dataset provided by LNEG containing well data with calculated geothermal gradient and heat flux density.

## Repository Contents

- **Jupyter Notebooks:**
  - Separate notebooks for each model (Random Forests and XGBoost) in both 5x5 km² and 2.5x2.5 km² grids.

- **Presentation Slides:**
  - A concise presentation summarizing the methodology, results, and key findings.

- **Thesis PDF:**
  - The complete Master's thesis providing in-depth details of the study.

## Purpose

This repository serves as a publication of my work, showcasing my skills in data science, machine learning, Python, ArcGIS, and geospatial data analysis. It is also an integral part of my portfolio, demonstrating my proficiency in tackling complex geospatial challenges.

Feel free to explore the notebooks, presentation slides, and thesis PDF to gain insights into the methodologies employed and the outcomes achieved in this geothermal potential analysis.

Your feedback and insights are highly appreciated! If you have any questions or suggestions, feel free to reach out.

Matheus Nascimento.
