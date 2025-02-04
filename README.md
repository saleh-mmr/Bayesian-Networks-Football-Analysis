# Football Match Outcome Prediction using Bayesian Reasoning

## Project Overview  
This project predicts football game outcomes using **Bayesian reasoning techniques**. By leveraging match data and relevant features, we preprocess the dataset and apply probabilistic models to classify match results. **The goal is to provide accurate and interpretable predictions based on statistical insights.**

## Dataset  
The dataset used in this project is sourced from **Kaggle**. It contains historical football match data with relevant features such as teams, match results, and other statistical details.  

### Dataset Details  
- **Source**: [Kaggle](https://www.kaggle.com/datasets/gokhanergul/football-match-statistics/data)  
- **Format**: `.csv`  
- **Preprocessing**: Fixed data issues and cleaned the dataset to ensure accuracy.  

You can find the `.csv` file of the processed dataset in this repository.  

## Project Workflow  
1. **Data Preprocessing**:  
   - Imputation missing values
   - Label Encoding for categorical features
   - Min-Max Scaling for numerical features
   - Discretization for numerical featuures

2. **Model Building**:  
   - Application of Bayesian reasoning techniques.  
   - Implementation of Manual Model based on Domain Knowledge
   - Implementation of TreeSearch Model
   - Implementation of Hill Climb Model

3. **Methods**:
   - CPDs Fitting for all Models
   - Scoring of all Models
   - Markov blanket for all Nodes in all Models

4. **Prediction**:  
   - Predicting the outcome of football matches in different Evidence Scenarios

## Requirements  
- **Python 3.x**  
- **Libraries**:  
  - Pandas  
  - NumPy  
  - Scikit-learn  
  - Matplotlib/Seaborn (for data visualization)  

