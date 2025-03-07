# Aggregate Mobility Score & City Ranking

This project aims to create an aggregate **Mobility Score** that evaluates and ranks cities based on various mobility factors. The score is derived from multiple transportation metrics, aggregated into a single ranking system. The methodology ensures a data-driven and fair comparison of different cities' mobility efficiency.

# Data Sources
The dataset for this project includes mobility-related data collected from multiple sources such as:
  - **Walkability Scores**
  - **Transit Scores**
  - **Bike Scores**

# Methodology 

1. **Data Collection & Cleaning**
   - Extracted data from Kaggle dataset for American Cities
   - Cleaned and standardized data
   - Removed unwanted datapoints

2. **Aggregation of Mobility Score**
   - Combined individual metric scores into a weighted formula
    \[
     Mobility Score = (w_1 (Walk_Score) + w_2 (Transit_Scores) + w_3 (Bike_Score)) / 3
      \]

3. **Ranking Cities**
   - Calculated final scores and ranked cities accordingly.
   - Visualized results using Python data plots.
