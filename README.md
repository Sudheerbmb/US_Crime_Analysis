# US_Crime_Analysis

## Overview

This project aims to perform exploratory data analysis (EDA), data cleaning, and model building using a crime dataset. The objective is to clean the dataset, visualize trends, and build a predictive model. The project concludes with a K-Nearest Neighbors (KNN) model that demonstrates the best performance for this dataset.

## Steps Taken in the Project

1. **Clone the Repository**

    To start, clone the repository using the following command:
    ```bash
    git clone https://github.com/Sudheerbmb/US_Crime_Analysis
    ```

2. **Install Dependencies**

    This project uses Python 3.x and requires the installation of several libraries. To install the necessary dependencies, run the following:
    ```bash
    pip install -r requirements.txt
    ```

    Or manually install the necessary libraries:
    ```bash
    pip install pandas numpy scikit-learn matplotlib seaborn
    ```

3. **Dataset Overview**

    The dataset used in this project contains crime data. .

4. **Data Cleaning and Preprocessing**

    - **Null Values**: Checked and handled missing data.
    - **Outliers**: Identified and managed outliers in the dataset.
    - **Duplicate Entries**: Removed any duplicate rows.
    - **Data Transformation**: Applied necessary transformations to the dataset for better analysis and model compatibility.

5. **Data Visualization**

    - Used various visualization tools such as histograms, bar plots, and scatter plots to explore the data and identify trends.
    - Visualized correlations between different features.
    
6. **Model Building**

    - Applied different machine learning models to predict outcomes.
    - The **K-Nearest Neighbors (KNN)** model was found to be the best-performing model based on accuracy and other metrics.

7. **Model Evaluation**

    - The model was evaluated using standard performance metrics, R^2



## How to Run the Project

1. **Download the Dataset**

    Download the `crime_data.csv` dataset from the repository.

2. **Run the Code**

    - Import the necessary libraries.
    - Load the dataset.
    - Follow the steps outlined in the code to clean the dataset, create visualizations, and build the KNN model.

3. **Evaluate the Model**

    After training the KNN model, evaluate its performance using the test dataset.

## Conclusion

This project demonstrates the process of cleaning, visualizing, and building predictive models using a crime dataset. The KNN model provided the best results for this particular dataset.

