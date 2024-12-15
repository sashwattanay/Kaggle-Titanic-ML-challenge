# Kaggle Titanic Data Challenge

## Objective
This project addresses the Titanic Data Challenge on Kaggle, aiming to predict passenger survival based on various features such as age, gender, ticket class, and more.

## Workflow
1. **Data Cleaning:**
   - Handled missing values in `Age`, `Embarked`, and `Fare`.
   - Dropped the `Cabin` column due to high missingness (~77%).
2. **Feature Engineering:**
   - Created `FamilySize` and `IsAlone` features for better predictive power.
   - Performed log transformation on `Fare` and introduced interaction terms.
3. **Model Selection:**
   - Trained a Logistic Regression model with scaled features.
   - Evaluated using validation accuracy, confusion matrix, and classification report.
4. **Prediction and Submission:**
   - Generated predictions for the test dataset and created the submission file.

## Results
- **Validation Accuracy:** 78.77%
- **Kaggle Public Leaderboard Score:** 0.75837

## Links
- **Kaggle Profile:** [Sashwat Tanay on Kaggle](https://www.kaggle.com/sashwattanay)
- **GitHub Repository:** [Kaggle Titanic ML Challenge](https://github.com/sashwattanay/Kaggle-Titanic-ML-challenge)

## File Outputs
- A CSV submission file (`submission.csv`) with binary survival predictions for the Kaggle Titanic competition.

## Repository Author
**Name:** Sashwat Tanay  
**GitHub:** [Sashwat Tanay on GitHub](https://github.com/sashwattanay)