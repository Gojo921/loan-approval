# Loan Approval Predictor

## Overview
This project is a Machine Learning-based Loan Approval Prediction System using Python and Scikit-Learn. The model is trained on a dataset of loan applications and uses a Support Vector Machine (SVM) classifier to predict whether a loan will be approved or not.

## Features
- Loads and preprocesses a loan approval dataset
- Encodes categorical variables into numerical values
- Splits data into training and testing sets
- Trains an SVM model with a linear kernel
- Evaluates the model using accuracy score
- Accepts user input for real-time loan approval predictions

## Dependencies
Ensure you have the following Python libraries installed:

```bash
pip install numpy pandas seaborn scikit-learn
```

## Usage
1. Clone the repository:

```bash
git clone https://github.com/yourusername/loan-approval-predictor.git
cd loan-approval-predictor
```

2. Run the script:

```bash
python loan_approval_predictor.py
```

3. Enter the required details when prompted to get a loan approval prediction.

## Example Input
```
Gender (Male: 0, Female: 1): 1
Married (No: 0, Yes: 1): 1
Education (Not Graduate: 0, Graduate: 1): 1
Self Employed (No: 0, Yes: 1): 0
Property Area (Rural: 0, Semiurban: 1, Urban: 2): 2
Applicant Income: 5000
Coapplicant Income: 2000
Loan Amount: 150
Loan Amount Term: 360
Credit History (0 or 1): 1
Number of Dependents (Enter 4 for 3+): 2
```

## Model Accuracy
The model's accuracy is displayed after training on the dataset.

## License
This project is open-source and available under the MIT License.

