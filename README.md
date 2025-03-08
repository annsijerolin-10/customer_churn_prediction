# Customer Churn Prediction

## Overview
This project focuses on predicting customer churn using machine learning techniques. It employs the Random Forest algorithm to classify customers as either churned or retained based on various features.

## Dataset
The dataset contains customer-related information such as:
- Customer demographics
- Subscription details
- Usage behavior
- Support interactions

The target variable is **Churn**, which indicates whether a customer has left the service.

## Project Workflow
1. **Data Preprocessing**
   - Handling missing values
   - Encoding categorical variables
   - Normalization/Scaling
   - Feature selection

2. **Exploratory Data Analysis (EDA)**
   - Visualizing customer trends
   - Identifying key factors contributing to churn

3. **Model Training & Evaluation**
   - Splitting data into training and test sets
   - Training a Random Forest classifier
   - Evaluating performance using metrics such as Accuracy, Precision, Recall, and F1-score

## Installation & Dependencies
To run this project, install the required dependencies using:
```bash
pip install pandas numpy scikit-learn matplotlib seaborn
```

## Usage
Run the Python script to train and evaluate the model:
```bash
python customer_churn_prediction.py
```

## Results
The Random Forest model achieves a strong performance with high accuracy. The classification report and confusion matrix provide insights into the prediction quality.

## Future Improvements
- Experimenting with other machine learning models (e.g., XGBoost, Neural Networks)
- Hyperparameter tuning to optimize model performance
- Deploying the model as a web service using Flask or FastAPI

## Contributing
Feel free to submit pull requests or report issues if you find areas for improvement.

## License
This project is licensed under the MIT License.

