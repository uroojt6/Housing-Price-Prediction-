# Housing-Price-Prediction-
It was project for Lakeshore real state company i work for 1 year

# Prediction of Housing Prices 🏡📊  

## Project Overview 
This project aims to predict housing prices using **supervised learning** techniques. The task is a **regression problem**, where we predict the **median value of owner-occupied homes (MEDV)** based on various housing attributes. The model is trained using **online learning** for continuous updates and adaptation. Performance is evaluated using **Root Mean Square Error (RMSE).**  

## Dataset & Features
The dataset contains **14 attributes**, including crime rate, property tax, and number of rooms, which influence housing prices.  

### Attribute Information:
1. CRIM – Per capita crime rate by town  
2. ZN – Proportion of residential land zoned for lots over 25,000 sq.ft.  
3. INDUS – Proportion of non-retail business acres per town  
4. CHAS – Charles River dummy variable (1 if tract bounds river, 0 otherwise)  
5. NOX – Nitric oxides concentration (parts per 10 million)  
6. RM – Average number of rooms per dwelling  
7. AGE – Proportion of owner-occupied units built before 1940  
8. DIS – Weighted distances to five Boston employment centers  
9. RAD – Index of accessibility to radial highways  
10. TAX – Full-value property-tax rate per $10,000  
11. PTRATIO – Pupil-teacher ratio by town  
12. B – 1000(Bk - 0.63)^2 where Bk is the proportion of Black residents by town  
13. LSTAT – Percentage of lower-status population  
14. MEDV – Median value of owner-occupied homes (in $1000s)  

## Machine Learning Approach 
- Task Type: Supervised Learning  
- Model Type: Regression  
- Learning Technique: Online Learning  

## Performance Evaluation
The model’s performance is measured using **Root Mean Square Error (RMSE): 

\[
RMSE = \sqrt{\frac{1}{n} \sum_{i=1}^{n} (y_i - \hat{y}_i)^2}
\]

Where:  
- \( y_i \) = Actual house price  
- \( \hat{y}_i \) = Predicted house price  
- \( n \) = Total number of observations  

## Setup & Requirements 
### Installation
Ensure you have Python 3.x installed along with the following dependencies:  
```bash
pip install numpy pandas scikit-learn matplotlib seaborn jupyter
```

### Running the Project 
1. Open Jupyter Notebook 
2. Load the dataset and preprocess it  
3. Train the model using online learning  
4. Evaluate performance using RMSE  
5. Visualize predictions vs. actual values  

## Future Improvements  
🔹 Feature engineering for better insights  
🔹 Hyperparameter tuning for better accuracy  
🔹 Deployment as a web app for real-time predictions  

## Author  
👩‍💻 Urooj Tariq 


