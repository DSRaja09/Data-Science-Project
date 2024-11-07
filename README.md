# Data Science Project - PDS Analysis

## Project Overview
This project investigates factors influencing student dropout rates using a dataset containing academic and demographic information. The analysis includes data cleaning, preprocessing, exploratory data analysis (EDA), and visualization. Additionally, it uses machine learning to build predictive models to classify students as either at risk of dropping out or not, based on their academic and personal characteristics.

## Project Structure
The notebook is organized as follows:

1. **Data Loading and Cleaning**: 
   - The dataset is loaded, and columns are cleaned to ensure uniform formatting.
   - Exploratory checks are conducted, including the dataset's shape, structure, and basic descriptive statistics.
   
2. **Exploratory Data Analysis (EDA)**:
   - **Target Distribution**: Visualizes the distribution of the target variable (dropout status) to understand the class balance.
   - **Gender and Scholarship**: Examines dropout rates by gender and scholarship holder status.
   - **Age, Qualification, and Grade Relationships**: Analyzes how factors like age, previous qualifications, and grades relate to dropout rates.
   - **Other Visualizations**: Includes insights on parental qualifications, tuition fees, and international student status.

3. **Feature Engineering and Model Preparation**:
   - Selected features based on EDA to prepare for machine learning.
   - Encodes categorical variables and standardizes features for modeling.

4. **Modeling**:
   - Uses classification models to predict dropout risk, evaluating each model based on accuracy, precision, recall, and F1-score.
   - Compares models to identify the best performer.

5. **Conclusion**:
   - Summarizes the findings and implications for identifying at-risk students.

## Requirements
- Python 3.x
- Jupyter Notebook
- Required Libraries: `numpy`, `pandas`, `matplotlib`, `seaborn`, `sklearn`

## Usage
1. Clone the repository:
   ```bash
   git clone https://github.com/DSRaja09/Data-Science-Project.git
