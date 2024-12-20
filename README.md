# LightGBM_on_Credit_score_classification
**Credit Scoring Model**

This repository contains a machine learning project for developing a credit scoring model to predict the creditworthiness of individuals using historical financial data. The project uses the LightGBM algorithm for classification and includes preprocessing, feature engineering, and evaluation steps.

**Project Structure**

train.csv: Training dataset.

test.csv: Test dataset.

credit_scoring.py: Python script for training and evaluating the model.

predicted_credit_scores.csv: Output file containing predicted credit scores for the test dataset.

README.md: Project documentation.

**Requirements**

To run the project, you need the following libraries installed:

pandas

numpy

scikit-learn

lightgbm

You can install the required libraries using pip:

pip install pandas numpy scikit-learn lightgbm

Dataset

The project uses the train.csv and test.csv files as input. Ensure these files are placed in the appropriate directory before running the script.

Running the Project

Clone the repository:

git clone https://github.com/Ishrat-Jahan-Mim456/LightGBM_on_Credit_score_classification.git


The predicted credit scores will be saved in the predicted_credit_scores.csv file in the project directory.

**Methodology**

**Data Preprocessing:**

Missing values are filled with a placeholder value (-999).

Categorical features are encoded using Label Encoding.

**Model Training:
**
LightGBM is used as the classifier.

Hyperparameters are set for multi-class classification.

Early stopping is implemented to prevent overfitting.

**Evaluation:**

The model is evaluated using metrics such as classification report and ROC-AUC score.

**Prediction:**

The model predicts credit scores for the test dataset, which are saved to an output CSV file.

**Results**

The classification report and ROC-AUC score provide insights into the model's performance. These metrics are displayed in the console after training.

Contributing

Contributions are welcome! Feel free to open issues or submit pull requests for improvements.



**Contact**

For questions or feedback, please contact:

Name: Ishrat Jahan Mim

Email: ishratmim456@gmail.com

GitHub: https://github.com/Ishrat-Jahan-Mim456

