# Predicting-Adverse-Reaction-of-COVID-19-Vaccine-With-The-Help-Of-Machine-Learning
Software group Project 2

## Introduction
This project was developed by **Vansh Desai** and **Aman Shah** under the guidance of **Prof. Ashwin Makwana** and **Chintal Raval**. The project was conducted during the COVID-19 vaccine development phase, utilizing the initial COVID-related data that became available. The aim of this project is to analyze vaccine data to understand various factors and their correlation with the outcome 'DIED'. This project has been published in a Scopus-indexed journal, which can be accessed [here](https://link.springer.com/chapter/10.1007/978-981-19-7447-2_40).


## Prerequisites
- Python 3.x
- Jupyter Notebook
- Required Python libraries:
  - pandas
  - scikit-learn

## Files
- `VACCINE_ANALYSIS.ipynb`: Jupyter notebook containing the analysis code.
- `vaccine_data.zip`: Zip file containing vaccine_data.xlsx dataset which vaccine information (this file should be placed in the same directory as the notebook).

## Setup
1. Ensure you have Python 3.7 installed on your system.
2. Install Jupyter Notebook if you haven't already:
    ```bash
    pip install notebook
    ```
3. Install the required Python libraries:
    ```bash
    pip install pandas scikit-learn
    ```

## Usage
1. Clone the repository or download the notebook and dataset files.
2. Open the Jupyter Notebook:
    ```bash
    jupyter notebook VACCINE_ANALYSIS.ipynb
    ```
3. Run the cells in the notebook sequentially to perform the analysis.

## Notebook Outline
1. **Introduction**: Overview of the project.
2. **Data Collection**: Data Was collected from [VAERS](https://vaers.hhs.gov/data/datasets.html).
3. **Load Data**: Load the dataset and implement initial basic filters.
4. **Exploratory Data Analysis**: Use visualization and techniques like frequent itemset mining to understand data and the impact of features on the target variable.
5. **Data Pre-Processing**: Convert categorical variables to numeric values using LabelEncoder and fill null values.
6. **Feature Selection**: Use the Variance inflation factor, Pearson matrix, and SelectKBest with chi-squared score function to select the top features.
7. **Split Data into Training and Testing Sets**: Split the data using a 60-40 split.
8. **Separate Features and Target Variable (Training Set)**: Separate features and target variable for the training set.
9. **Separate Features and Target Variable (Testing Set)**: Separate features and target variable for the testing set.
10. **Model Training and Evaluation**: Train model on differant machine learning algoritham.
11. **Conclusion**: Summary of the findings and next steps for model training and evaluation.

## Publication
The findings and methodology of this project have been published in a Scopus-indexed journal, emphasizing the importance and impact of the study in understanding vaccine efficacy and safety. The publication can be accessed [here](https://link.springer.com/chapter/10.1007/978-981-19-7447-2_40).

## Acknowledgements
We would like to express our gratitude to **Prof. Ashwin Makwana** and **Prof. Chintal Raval** for their guidance and support throughout this project.


## Conclusion
This project prepares the vaccine dataset for analysis by selecting relevant features, splitting the data into training and testing sets, and applying feature selection. The next steps involve training a predictive model using the selected features and evaluating its performance on the test set.
