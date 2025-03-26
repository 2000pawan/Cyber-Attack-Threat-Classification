# Cybersecurity Threat Classification using Machine Learning

## Overview
This project classifies network intrusions using machine learning models. It utilizes the **CICIDS2017** dataset to detect various attack types. The model used in this project is implemented in a **single Jupyter Notebook** file instead of separate scripts.

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

3. **Run the Jupyter Notebook**
   - Open the Jupyter Notebook environment:
   ```bash
   jupyter notebook
   ```
   - Navigate to the **Cyber_attack.ipynb** file and execute all cells sequentially.

## Notebook Structure
- **Data Preprocessing**: Cleans missing values, normalizes numerical features, encodes categorical data, and balances the dataset using **SMOTE**.
- **Model Training**: Trains **Random Forest** and **SVM** classifiers with feature selection and hyperparameter tuning.
- **Evaluation**: Computes accuracy, precision, recall, and F1-score to compare model performance.
- **Visualization**: Generates confusion matrices and ROC curves for model assessment.

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
