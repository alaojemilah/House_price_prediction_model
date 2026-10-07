
# California House Price Prediction Model

## Problem Statement
The California Housing dataset contains information about housing across California. The goal of this project is to build a machine learning model that predicts median house values.

This is a *regression problem* because the output is a continuous value - house prices.

## Dataset
- *Source:* California Housing dataset (Scikit-learn)
- *Target:* Median House Value
- *Features used:*
  - MedInc (Median Income)
  - HouseAge
  - AveRooms
  - AveBedrms
  - Population
  - AveOccup
  - Latitude
  - Longitude

## What I Did
- Imported dataset directly from Scikit-learn
- Preprocessed and explored the data
- Split the data into training and test sets (80/20 split)
- Scaled features using feature scaling
- Trained multiple machine learning models
- Created a predict function to test on unseen data
- Used a Pipeline to improve model performance

## Models Tested & Results

| Model | Accuracy |
|---|---|
| Logistic Regression | 57.57% |
| Pipeline | *62.47%* |

## Best Model
The *Pipeline* achieved the highest accuracy of *62.47%*, a significant improvement over the base Logistic Regression model, showing the impact of combining preprocessing and modelling into one streamlined flow.

## Key Takeaways
- The model performed well on unseen data
- Using a Pipeline made a significant difference in performance
- Feature scaling and proper data splitting were key to reliable results
- Regression problems require different evaluation thinking than classification

## Tools & Libraries
- Python
- Pandas
- NumPy
- Scikit-learn

## Author
Jemilah Alao | Data Analyst
[LinkedIn](https://www.linkedin.com/in/jemilah-alao-8a684528a)
