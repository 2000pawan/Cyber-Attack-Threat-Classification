# Cyber-Attack-Threat-Classification
Cyber Attack Threat Classification using CICIDS2017 dataset.
# e Cybersecurity Threat Classification using Machine Learning

## Overview

This project classifies network intrusions using machine learning models. It utilizes the **CICIDS2017** dataset to detect various attack types. The models compared in this project are **Random Forest** and **Support Vector Machine (SVM)**.

## Requirements

Before running the code, ensure you have the following dependencies installed:

```bash
pip install pandas numpy scikit-learn matplotlib seaborn
```

Alternatively, you can install the dependencies using a requirements file:

```bash
pip install -r requirements.txt
```

## Running the Code

1. **Clone the Repository**

   ```bash
   git clone https://github.com/2000pawan/Cyber-Attack-Threat-Classification.git
   ```

2. **Download and Extract the Dataset**

   - Download the **CICIDS2017** dataset from [here](https://www.unb.ca/cic/datasets/ids-2017.html).
   - Extract the dataset into the `data/` directory.

3. **Preprocess the Data**

   - Clean missing values and normalize numerical features.
   - Encode categorical features using one-hot encoding.
   - Balance the dataset using **SMOTE** to handle class imbalances.

   ```bash
   python preprocess.py
   ```

4. **Train the Models**

   - Train both **Random Forest** and **SVM** classifiers.
   - Perform **feature selection** using **Recursive Feature Elimination (RFE)**.
   - Optimize hyperparameters using **Grid Search**.

   ```bash
   python train.py
   ```

5. **Evaluate the Models**

   - Compute evaluation metrics: **accuracy, precision, recall, F1-score**.
   - Compare model performance and analyze misclassifications.

   ```bash
   python evaluate.py
   ```

6. **Visualizing Results**

   - Generate confusion matrices and ROC curves.
   - Display feature importance plots.

   ```bash
   python visualize_results.py
   ```

## Results Summary

- **Random Forest** outperformed **SVM** in accuracy and generalization.
- **Feature selection** improved computational efficiency.
- **Future enhancements** could involve deep learning models for better performance.

## Future Work

- Implementing **deep learning models** like CNNs or LSTMs.
- Exploring **ensemble learning** approaches.
- Improving detection for minority attack classes.

For any issues, please create an issue on the repository.

---

**Author:** Pawan Yadav



