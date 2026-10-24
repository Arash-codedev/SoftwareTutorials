# Data Science Lifecycle

According to the CRISP-DM framework:

## 1. Business Understanding
- Define business objectives, requirements, and success criteria.

## 2. Data Understanding
- Includes collecting initial data.

## 3. Data Preparation/Processing (Data Wrangling)
Often taking up 70%-80% of a data scientist's time.

- Cleaning data:
    - Handling data from different structures.
    - Handling duplicate data.
    - Removing or filling in missing, empty, or null values.
    - Handling incorrect data types.
    - Handling gaps in data.
- Manipulating data:
    - Reshaping
    - Scaling
        - Min-Max Scaling (Normalization)
        - Standardization
- Organizing data:
    - Splitting data into training and testing sets (e.g., 80% and 20%).

## 4. Modeling
- KNN (K-Nearest Neighbors)
- SVM (Support Vector Machines)
- Linear Regression
- K-Means Clustering
- Neural Networks (NN)
- Decision Trees

## 5. Evaluation
- Error evaluation methods:
    - MAE (Mean Absolute Error): All errors matter equally.
    - RMSE (Root Mean Squared Error): Penalizes large errors more heavily (units match original data).
    - MSE (Mean Squared Error): Penalizes large errors more heavily (units are squared).

## 6. Deployment & Monitoring
- Communicating results and deploying the model to production for ongoing monitoring.
