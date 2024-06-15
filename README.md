# Heart Stroke Prediction Classifier

Welcome to the Heart Stroke Prediction Classifier project repository! This project aims to create a classifier that can predict how likely a patient is to get a heart stroke based on their medical conditions. The project utilizes a dataset containing various medical attributes of patients, such as age, hypertension, heart disease, smoking status, etc., to predict the likelihood of a heart stroke.

## Overview
The goal of this project is to build a machine learning model that can accurately classify whether a patient is at risk of having a heart stroke based on their medical conditions. By training a classification model on historical data, we aim to create a predictive model that can provide valuable insights into the risk factors associated with heart strokes.

## Dataset
The dataset used in this project contains the following medical attributes:
- Age: Age of the patient
- Hypertension: Whether the patient has hypertension (binary: yes/no)
- Heart disease: Whether the patient has heart disease (binary: yes/no)
- Average glucose level: Average glucose level in the blood
- BMI (Body Mass Index): Body Mass Index of the patient
- Smoking status: Whether the patient smokes or not (binary: yes/no)
- etc.

The target variable is whether the patient is likely to have a heart stroke (binary: yes/no).

## Source
The dataset can be downloaded from below link.

Dataset: https://drive.google.com/file/d/1uqi87nveAWf1sQ6bTaedVBEGidwre1Pf/view?usp=sharing

## Techniques Used
- Classification: Utilizing classification algorithms such as logistic regression, decision trees, random forests, or gradient boosting to predict the likelihood of a heart stroke based on the input medical attributes.
- Data Preprocessing: Cleaning the dataset, handling missing values, encoding categorical variables, and scaling numerical features.
- Model Evaluation: Assessing the performance of the classification model using evaluation metrics such as accuracy, precision, recall, F1-score, and ROC-AUC score.

## Setup Instructions
1. Clone the repository:
   ```
   git clone https://github.com/your-username/heart-stroke-prediction.git
   ```
2. Install the required dependencies specified in the `requirements.txt` file.
3. Download the heart stroke prediction dataset and preprocess it as necessary.
4. Train the classification model on the preprocessed dataset.
5. Evaluate the performance of the trained model and make predictions on new data.

## Usage
1. **Data Preprocessing**: Clean and preprocess the heart stroke prediction dataset, handle missing values, encode categorical variables, and scale numerical features.
2. **Model Training**: Train a classification model using algorithms such as logistic regression, decision trees, random forests, or gradient boosting.
3. **Model Evaluation**: Evaluate the performance of the trained model using evaluation metrics such as accuracy, precision, recall, F1-score, and ROC-AUC score.
4. **Prediction**: Make predictions on new data using the trained classification model to determine the likelihood of a patient getting a heart stroke.

## Contributing
Contributions are welcome! If you have any ideas, suggestions, or improvements, feel free to open an issue or create a pull request.

## License
This project is licensed under the [MIT License](LICENSE).
