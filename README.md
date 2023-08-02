# Pandas-Preparing-Dataset
**Pandas Assignment: Data Preprocessing and Visualization**

This repository contains a Python notebook focusing on data preprocessing and visualization using the Pandas library. The notebook covers essential steps to clean and analyze the Book-Crossing Dataset, which is used for recommendation algorithms.

**1. Packages**

In this notebook, we will utilize several Python libraries for data analysis and visualization, including:
- Pandas: The main tool for handling tabular datasets.
- NumPy: The fundamental package for scientific computing.
- Matplotlib, Seaborn, and Plotly: Libraries for plotting graphs in Python.
- Missingno: A module for visualizing missing data.
- Pycountry_convert: A module for converting ISO country names, codes, and continent names.
- Warnings: A module for handling warnings.

**2. Dataset**

The dataset used in this notebook is the Book-Crossing Dataset, collected from the Book-Crossing community. We will focus on the 'BX-Users.csv' file from this dataset, which contains user information such as user ID, location, and age.

**3. Data Preprocessing**

In this section, we will clean and preprocess the 'BX-Users.csv' file to make it suitable for analysis:
- Renaming columns: We will rename the columns from 'User-ID', 'Location', and 'Age' to 'userId', 'location', and 'age', respectively.
- Handling missing values in the 'age' column: We will convert the 'age' data type to float, set values below 5 and above 110 to NaN, and impute the missing values using a normal distribution based on mean and standard deviation.
- Handling messy location data: We will split the 'location' column into 'city', 'state', and 'country' columns and handle missing or incorrect values.
- Data visualization: We will visualize the age distribution using histograms and interactive choropleth maps for user distribution across countries.

**Conclusion**

This notebook provides a step-by-step guide to preprocess and visualize data using the Pandas library. The dataset used is the Book-Crossing Dataset, and various data preprocessing techniques are demonstrated, including handling missing values, splitting columns, and converting data types. Additionally, interactive choropleth maps are used to visualize user distribution across countries. Feel free to use this notebook as a starting point for your data analysis projects and experiments.
