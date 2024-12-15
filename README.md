# Kaggle Titanic Data Challenge

## Objective
This project aims to predict passenger survival on the Titanic based on features such as age, gender, ticket class, and more. This is a submission for the Kaggle Titanic Data Challenge, showcasing data preprocessing, feature engineering, and model training using Logistic Regression.

## Workflow
1. **Data Cleaning:**
   - Handled missing values in `Age`, `Embarked`, and `Fare`.
   - Dropped the `Cabin` column due to high missingness (~77%).
2. **Feature Engineering:**
   - Created new features: `FamilySize` (family size onboard) and `IsAlone` (indicator of solo travel).
   - Applied log transformation to `Fare` for normalization and introduced interaction terms to capture relationships between features.
3. **Model Selection and Evaluation:**
   - Trained a Logistic Regression model with scaled features.
   - Evaluated model performance using:
     - Validation accuracy
     - Confusion matrix
     - Classification report
4. **Prediction and Submission:**
   - Generated survival predictions for the test dataset.
   - Created a submission file (`submission.csv`) for the Kaggle competition.

## Results
- **Validation Accuracy:** 78.77%
- **Kaggle Public Leaderboard Score:** 0.75837  
  *(Rank and score available on the [public leaderboard](https://www.kaggle.com/competitions/titanic/leaderboard))*.

## File Outputs
- **`submission.csv`:** A CSV file with binary survival predictions for the test dataset, as required by the Kaggle competition.

## Links
- **Kaggle Profile:** [Sashwat Tanay on Kaggle](https://www.kaggle.com/sashwattanay)  
- **GitHub Repository:** [Kaggle Titanic ML Challenge](https://github.com/sashwattanay/Kaggle-Titanic-ML-challenge)

## Repository Author
**Name:** Sashwat Tanay  
**GitHub:** [Sashwat Tanay on GitHub](https://github.com/sashwattanay)

## How to Use
1. Clone the repository:
   ```bash
   git clone https://github.com/sashwattanay/Kaggle-Titanic-ML-challenge.git