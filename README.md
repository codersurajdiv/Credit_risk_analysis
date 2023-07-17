
# Credit Risk Analysis

The goal of this project is to develop a predictive financial model that can accurately predict loan default based on given features such as age, income, employment length, loan amount, interest rate, and more. The project is implemented in R using the random forests algorithm.



## Dataset

The dataset used for this project contains the following variables:

- `person_age`: Age of the individual
- `person_income`: Annual income of the individual
- `person_emp_length`: Employment length (in years)
- `loan_amnt`: Loan amount
- `loan_int_rate`: Interest rate
- `loan_percent_income`: Percent income
- `cb_person_default_on_file`: Historical default information
- `cb_person_cred_hist_length`: Credit history length
- `loan_grade`: Loan grade
- `person_home_ownership`: Home ownership status
- `loan_intent`: Loan intent
- `loan_status`: Loan status (0 for non-default, 1 for default)

The model is trained on a fictional dataset containing simulated loan data. This dataset is created for demonstration purposes and does not represent real-world data. It includes information on individuals' personal and financial attributes, as well as their loan status (default or non-default).

Please note that the fictional dataset used for training can be found [here](https://www.kaggle.com/datasets/laotse/credit-risk-dataset). You can explore the dataset for a better understanding of the features and their distributions.

When using this model for real-world applications, it is important to train it on representative and accurately labeled datasets that reflect the target population.


## Installation

To use the Loan Default Prediction Model, follow these steps:

1. Clone the repository to your local machine.
2. Install the required packages and dependencies specified in the code. This may include packages such as `randomForest`, `caret`, and `tidyverse`.
3. Ensure that you have the necessary version of R installed on your system.
4. Import the trained model or retrain the model using the provided dataset.
## Usage

To utilize the Loan Default Prediction Model, follow these instructions:

1. Prepare the input data: Ensure that you have the necessary information for the prediction, such as age, income, employment length, loan amount, interest rate, loan grade, home ownership, and loan intent.

2. Preprocess the input data: Perform any required data preprocessing steps, such as handling missing values, scaling, or encoding categorical variables, based on the preprocessing steps used during model training.

3. Make predictions: Utilize the trained model to make predictions on the preprocessed input data. The model should output a binary value indicating the likelihood of loan default.

4. Interpret the results: Analyze the prediction output and consider it alongside other factors to assess the risk of loan default for the individual.



## Future Improvements

There are several possible areas for future improvement in this project:

- Further feature engineering to create more informative variables.
- Exploring different machine learning algorithms and comparing their performance.
- Handling imbalanced classes in the dataset using advanced techniques.
- Tuning hyperparameters to optimize the model's performance.
- Conducting additional data exploration and visualization for deeper insights.

## Contributing

Contributions are always welcome!

If you have any suggestions, improvements, or bug fixes, feel free to open an issue or submit a pull request.


Please adhere to this project's `code of conduct`.


## License

This project is licensed under the [MIT License](LICENSE).

## Authors

- [@Suraj Divakala](https://github.com/codersurajdiv)

