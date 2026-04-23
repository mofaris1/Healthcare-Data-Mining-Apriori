# Healthcare Data Mining: Diabetes Association Rules

## Overview
This project applies Unsupervised Machine Learning and Data Mining techniques to a healthcare dataset to uncover hidden patterns and correlations related to Diabetes. By utilizing the **Apriori algorithm**, the project extracts meaningful Association Rules that highlight how different lifestyle and health indicators (e.g., Physical Activity, Diet, Blood Pressure) frequently co-occur with diabetes diagnoses.

## Key Technical Achievements
1. **Data Preprocessing:**
   - Performed categorical data transformation using **One-Hot Encoding** to convert features (BMI, General Health, Education, Income) into binary formats suitable for rule mining.
   - Binarized continuous and multi-class variables to create a strict True/False itemset matrix.
2. **Association Rule Mining:**
   - Implemented the **Apriori algorithm** to identify frequent itemsets (health indicator combinations) with a defined minimum support threshold.
   - Extracted and filtered Association Rules based on critical metrics: **Support**, **Confidence**, and **Lift**.
3. **Insight Generation:**
   - Interpreted the mathematical outputs to generate real-world healthcare insights (e.g., demonstrating the high confidence rules linking high blood pressure and cholesterol checks with overall healthcare engagement).

## Technologies Used
- Python
- Pandas & NumPy (Data manipulation)
- MLxtend / Scikit-Learn (Apriori Algorithm & Association Rules)
- Data Mining & Unsupervised Learning
