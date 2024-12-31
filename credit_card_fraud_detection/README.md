# Credit Card Fraud Detection

## Overview

This project implements a machine learning pipeline to detect fraudulent credit card transactions. Using publicly available data, it leverages various algorithms to classify transactions as legitimate or fraudulent. The system aims to assist financial institutions in identifying and preventing fraud effectively.

---

## Features

1. **Data Preprocessing:**

   - Normalization of transaction amounts.
   - Balancing the dataset using SMOTE to handle class imbalance.

2. **Exploratory Data Analysis (EDA):**

   - Visualization of data distributions.
   - Correlation heatmap to analyze relationships between features.

3. **Model Building:**

   - Implemented three machine learning algorithms: Random Forest, Gradient Boosting, and Logistic Regression.
   - Metrics used for evaluation: Accuracy, Precision, Recall, F1 Score, and ROC AUC.

4. **Model Evaluation:**

   - Classification reports, confusion matrices, and ROC curves for detailed performance analysis.

5. **Feature Importance Analysis:**

   - Highlighted significant features contributing to fraud detection using Random Forest.

---

## Technologies Used

### Programming Language:

- Python

### Libraries:

- **Data Handling:** pandas, numpy
- **Visualization:** matplotlib, seaborn
- **Machine Learning:** scikit-learn
- **Oversampling:** imbalanced-learn (SMOTE)

---

## Dataset

The dataset used is the [Kaggle Credit Card Fraud Detection Dataset](https://www.kaggle.com/mlg-ulb/creditcardfraud).

- **Features:**
  - `Time`: Time elapsed between the transaction and the first transaction in the dataset.
  - `Amount`: Transaction amount.
  - `V1` to `V28`: Anonymized features.
  - `Class`: Target variable (0 = Legitimate, 1 = Fraudulent).

---

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/credit-card-fraud-detection.git
   ```
2. Navigate to the project directory:
   ```bash
   cd credit-card-fraud-detection
   ```
3. Install required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

---

## Usage

1. Place the `creditcard.csv` dataset in the project directory.
2. Run the script block-by-block in a Jupyter Notebook or execute the Python script:
   ```bash
   python fraud_detection.py
   ```
3. Visualize the results and evaluate model performance.

---

## Results

- **Random Forest**:
  - High accuracy and robust performance with significant feature importance analysis.
- **Gradient Boosting**:
  - Performed well in terms of precision and recall.
- **Logistic Regression**:
  - Provided a baseline comparison for other models.

---

## Future Enhancements

- Incorporate real-time streaming data for fraud detection.
- Implement additional algorithms like LightGBM and CatBoost for improved speed and performance.
- Create a user-friendly dashboard for visualizing transaction data and detection results.

---

## Contributing

Contributions are welcome! Please fork the repository and submit a pull request for any enhancements or bug fixes.

---

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

## Acknowledgments

Special thanks to the contributors of the Kaggle dataset and the open-source libraries used in this project.

