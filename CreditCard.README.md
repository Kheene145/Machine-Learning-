# :rocket: Credit Card Fraud Detection Using Machine Learning 

## :mag: Overview
- Credit card fraud is a significant challenge in the financial sector. In this project, I built a fraud detection model using machine learning classify transactions as fraudelent or non-fraudulent.

## 📂 Dataset
- Source:[Kaggle- Credit Card Fraud Detection Dataset](https://www.kaggle.com/datasets/whenamancodes/fraud-detection)
  

- size: 284,807 trasactions
  
  
- Features: 30 numerical features + 1 target column
  
  
- Target Variable
    - 0: Legitimate transaction
    - 1: Fraudulent transaction
      
 
## 🛠️  Tech Stack
✔️ Python (pandas, Numpy, scikit-learn, matplotlib seaborn)


✔️ Machine Learning (LogisticRegression)


✔️ Jupyter Notebook

## 📊 Exploratory Data Analysis
 ✔️ Checked for missing values

 
✔️ Visualized fraud and non-fraud transactions


  ✔️ Examined featured distributions


 ✔️ Addressed class imbalance using under-sampling technique



## 📈 Machine Learning Model Used
| **Model**            |                       **Description**                                      |                                  **Advantages**                                      |       **Disadvantages**  |
|----------------------|----------------------------------------------------------------------------|---------------------------------------------------------------------------------------|----------------------------------------------|
| LogisticRegression   | A linear Classifier used as a baseline for binary classification problems|- Simple and easy to implement. <br>-Provides probability for risk assessment. <br> -Quick to train and predict|- Struggle with complex relationships in the data. <br> - Less effective when data is not linearly separable.|


## Model Evaluation

| **Metric**            |                       **Description**                                      |                                  **Importance**                                      |
|-----------------------|----------------------------------------------------------------------------|--------------------------------------------------------------------------------------|
| Accuracy              | Measures the overall percentage of correct predictions.                    | Provides a basic indication of model perforamance.                                   |
| Precison              | The proportion of predicted fraud cases that are actually fraudulent.      | Helps minimize false positives(legitimate transactiobs labeled as fraud.             |
| Recall                | The proportion of actual fraud cases that are correctly identified.        | Helps minimize false negatives (fraudulent transactions labeled as legitmate).       |
| F1-Score              | The harmonic mean proportion and Recall.                                   | Provides balance between Precision and Recall, useful for imbalance dataset.         |
| AUC-ROC               | The area under the receiver operating charactistics curve.                 | measure the model's ability to distinguish between fraudulent and legitmate transactions.| 



### Model Performance Comparison

| **Model**            | **Accuracy**  |  **Precision**  |  **Recall**  |  **F1-Score**  |  **AUC-ROC**  |
|----------------------|---------------|-----------------|--------------|----------------|---------------|
| LogisticRegression   | Baseline      |  Baseline       |  Baseline    |  Baseline      |  Basel;ine    |


## Key Takeaways

- The dataset contains 284,807 transactions, out of which only 492 transactions were identified as fraudulent.

  
- The fraudulent transactions account for approximately 0.173% of the total dataset, highlighting a highly imbalanced dataset.

  
- To improve model performance, we extracted 492 legitimate transactions to create a balanced subset for initial predictions.


- To fully address the class imbalance, we applied undersampling technique



## Conclusion
- Logistic Regression served as the baseline model, giving us a starting point for performance evaluation.


- Further improvements in model performance can be explored with advanced techniques or fine-tuning.
