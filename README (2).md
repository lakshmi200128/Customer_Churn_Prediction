# Customer Churn Prediction

## Overview
This project aims to predict customer churn using machine learning techniques. The dataset contains various customer attributes and behaviors that influence churn probability. The Jupyter Notebook includes data preprocessing, exploratory data analysis (EDA), model training, and evaluation.

## Dataset
- **File:** `Churn Modeling.csv`
- **Description:** Contains customer details such as demographics, account information, and churn status.
- **Key Features:**
  - Customer ID
  - Credit Score
  - Geography
  - Gender
  - Age
  - Tenure
  - Balance
  - Number of Products
  - Has Credit Card
  - Is Active Member
  - Estimated Salary
  - Exited (Churn Label)

## Project Files
- `Customer Churning Prediction.ipynb`: Jupyter Notebook containing data analysis and model implementation.
- `Churn Modeling.csv`: Dataset used for training and evaluation.
- `README.md`: Project documentation.

## Installation & Requirements
To run this project locally, install the required dependencies:
```bash
pip install pandas numpy scikit-learn matplotlib seaborn
```

## Running the Notebook
1. Open Jupyter Notebook:
   ```bash
   jupyter notebook
   ```
2. Load `Customer Churning Prediction.ipynb`.
3. Run all cells to process the data and train the model.

## Results
The model evaluates customer churn based on historical data. Various metrics such as accuracy, precision, recall, and F1-score are used to measure performance.

## Contribution
Feel free to fork this repository, report issues, or submit pull requests.

## License
This project is licensed under the MIT License.
