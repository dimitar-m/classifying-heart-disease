# Heart Disease Prediction Using Logistic Regression

This project builds and evaluates a logistic regression model to predict the presence of heart disease using clinical features from the UCI Heart Disease dataset.

## How to Run  
- Open the latest version of the project in **NBViewer**:  
  [View in NBViewer](https://nbviewer.org/github/dimitar-m/classifying-heart-disease/blob/master/classifying-heart-disease.ipynb)

## Project Goals
- Predict heart disease presence using logistic regression.
- Evaluate model accuracy, sensitivity, and specificity.
- Interpret coefficients in both log-odds and odds-ratio scales.

## Methods Used
- Data preprocessing (encoding, scaling)
- Logistic regression modeling (`scikit-learn`)
- Performance metrics (`accuracy_score`, `recall_score`)
- Feature interpretation (log-odds & odds ratio)

## Key Findings
- The model achieved strong performance on both training and test sets.
- Certain features like `thal`, `cp`, and `ca` showed strong predictive power.
- Sensitivity and specificity highlight balanced performance.

## Requirements
- Python 3.8+
- pandas, numpy, matplotlib, seaborn, scikit-learn

## License
This project is licensed under the MIT License.
