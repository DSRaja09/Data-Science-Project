# Data Science Project - Predicting Student Dropout Risk Using Machine Learning

## Project Overview
This project investigates factors affecting student dropout rates using academic and demographic data. The aim is to gain insights into dropout patterns using academic and socio-economic patterns and build predictive models to identify at-risk students. This analysis could assist institutions in designing intervention strategies for at-risk students.

## Project Objective 
This project aims to predict dropout rates based on socioeconomic factors alone.
By focusing on socioeconomic data, the project seeks to uncover patterns and indicators
that can reliably predict a student’s likelihood of dropping out, offering insights that can be
instrumental for targeted interventions.
**Goal**: To develop a model that leverages socioeconomic data to accurately predict dropout
status, identifying the most impactful socioeconomic factors contributing to student dropout.

## Project Structure
The Project is organized as follows:

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

Three classification models were implemented to predict the likelihood of student dropout, each with unique strengths. After training and evaluating each model, logistic regression provided the most reliable results in terms of accuracy and interpretability.

### 1. Logistic Regression
Logistic regression is a simple yet powerful algorithm for binary classification. It models the probability of the target variable (dropout or not) as a logistic function of the input features. This model is well-suited for cases where interpretability is essential, as it allows us to assess the impact of each feature on dropout risk directly. In this project, logistic regression outperformed other models, demonstrating strong predictive accuracy and providing clear insight into feature importance.

### 2. Decision Tree Classifier
The decision tree classifier is a non-linear model that splits the data based on feature values, creating a tree structure where each branch represents a decision rule. While decision trees are easy to interpret and visualize, they can be prone to overfitting, especially on smaller datasets. In this analysis, the decision tree classifier performed adequately but did not match the accuracy or stability of the logistic regression model.

### 3. Random Forest Classifier
The random forest classifier is an ensemble of multiple decision trees that works by averaging or voting on predictions from each tree. This model tends to provide high accuracy by reducing overfitting issues present in individual decision trees. While the random forest achieved a competitive performance, logistic regression still emerged as the best-performing model for this dataset.
### Model Comparison
| Model               | Accuracy |
|---------------------|----------|
| Logistic Regression | 60.0%    |
| Decision Tree       | 46.4%    |
| Random Forest       | 53.9%    |

### Conclusion
Based on these results, logistic regression was selected as the primary model due to its higher accuracy and straightforward interpretability. The results suggest that logistic regression effectively identifies students at risk of dropout, making it a practical choice for this dataset.

## Requirements
- Python 3.x
- Jupyter Notebook
- Required Libraries: `numpy`, `pandas`, `matplotlib`, `seaborn`, `sklearn`

## Usage
1. Clone the repository:
   ```bash
   git clone https://github.com/DSRaja09/Data-Science-Project.git
