# Cancer Prediction

This project focuses on predicting cancer diagnoses using machine learning, specifically logistic regression.

## What I Did

- **Data Loading and Preprocessing:**  
  - Loaded the breast cancer dataset from a CSV file.
  - Explored the dataset’s features and checked for missing values.
  - Encoded the target variable (diagnosis) for modeling.

- **Exploratory Data Analysis:**  
  - Examined feature distributions and correlations.
  - Analyzed the dataset to understand the feature importance.

- **Model Building:**  
  - Split the data into training and test sets.
  - Built a logistic regression model using scikit-learn.
  - Trained the model on the training data.

- **Model Evaluation:**  
  - Made predictions on the test data.
  - Evaluated the model using accuracy, precision, recall, f1-score, and specificity.
  - Generated and visualized the confusion matrix.
  - Calculated the AUC-ROC score to assess the model’s ability to distinguish between classes.

- **Visualization:**  
  - Used seaborn and matplotlib for plotting the confusion matrix and other relevant graphs.

## Results

- Achieved an accuracy of approximately 91% on the test set.
- The model demonstrated good precision and recall for both malignant and benign cases.
- The AUC-ROC score was around 0.90, indicating strong classification performance.

## Technologies Used

- Python (Jupyter Notebook)
- pandas, numpy
- scikit-learn
- seaborn, matplotlib

## How to Run

1. Clone the repository.
2. Open `Logistic_regression.ipynb` in Jupyter Notebook or Google Colab.
3. Run the notebook cells in order to reproduce the results.

---

This project demonstrates the process of building, training, and evaluating a binary classification model for cancer prediction using logistic regression.
