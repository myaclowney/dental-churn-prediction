
# Dental Office Customer Churn Prediction

This project focuses on building a machine learning model to predict customer churn for a dental office. The model uses logistic regression, supported by advanced feature engineering and data balancing techniques to achieve high accuracy. I changed the dataset to a synthetic data because this project was created while working for a dental office and had to change due to privacy policies. 

## 🚀 Features
- **Churn Prediction Model:** Built with logistic regression, achieving 97% accuracy.
- **Feature Engineering:** Includes time since last appointment, appointment frequency, and outstanding balance trends.
- **Data Balancing:** Resampling techniques to address class imbalance for improved model performance.
- **Evaluation Metrics:** Accuracy, precision, recall, F1-score, and confusion matrix.

## 📦 Files
- `logistic_regression_churn_model.pkl`: The trained logistic regression model.
- `improved_dental_dataset.csv`: The dataset with churn-related features.
- `churn_prediction.ipynb`: Full code for data preprocessing, model training, and evaluation.

## 💡 Usage
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/dental-churn-prediction.git
   cd dental-churn-prediction
   ```

2. Install dependencies:
   ```bash
   pip install pandas scikit-learn
   ```

3. Run the Jupyter Notebook:
   ```bash
   jupyter notebook churn_prediction.ipynb
   ```

## 📊 Model Performance
- **Accuracy:** 97%
- **Precision & Recall:** Balanced for both churn and non-churn cases.

