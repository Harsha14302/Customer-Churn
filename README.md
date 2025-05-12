# Customer Churn Prediction using ANN

This project applies an Artificial Neural Network (ANN) to predict customer churn using a banking dataset. It involves data preprocessing, visualization, model training, and evaluation using standard classification metrics.

## 📁 Project Structure

- `customer_churn.ipynb`: Jupyter Notebook containing the full analysis and ANN implementation.
- Dataset: The notebook uses `Churn_Modelling (AI).csv` as input.

## 📊 Dataset Overview

The dataset includes customer-related information such as:
- CreditScore, Geography, Gender
- Age, Tenure, Balance, NumOfProducts
- HasCrCard, IsActiveMember, EstimatedSalary
- Exited (target variable)

## 🔍 Key Steps

1. **Data Loading and Cleaning**  
   Load CSV data and handle missing values.

2. **Exploratory Data Analysis (EDA)**  
   Includes plotting distributions and understanding correlations.

3. **Feature Engineering**  
   Label encoding, one-hot encoding, feature scaling.

4. **Train/Test Split**  
   Separate dataset into training and testing sets.

5. **Model Building (ANN)**  
   Implemented using TensorFlow/Keras (or another library depending on the notebook).

6. **Model Evaluation**  
   Confusion matrix, classification report, and accuracy score.

## 🚀 How to Run

1. Clone this repository or download the notebook.
2. Ensure the dataset `Churn_Modelling (AI).csv` is in the same directory.
3. Install required dependencies:

   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn
   ```

4. Open the notebook:

   ```bash
   jupyter notebook customer_churn.ipynb
   ```

5. Run all cells sequentially.

## 📈 Output

The final output is:
- Predicted churn values for test data.
- Classification report and confusion matrix for model evaluation.
- Accuracy of the ANN model.

## 📌 Requirements

- Python 3.7+
- Jupyter Notebook
- Libraries: pandas, numpy, matplotlib, seaborn, scikit-learn

## 🧠 Author

Developed for educational purposes to demonstrate churn prediction using machine learning techniques.
