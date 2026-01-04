Census Income Prediction (Linear SVM vs Linear Regression)
📌 Overview

This project predicts whether an individual earns more than $50K per year using the U.S. Census Adult Income Dataset.
It compares the performance of Linear SVM and Linear Regression on an imbalanced classification problem.

📊 Dataset

Source: U.S. Census Bureau (1994–95)

Target: Income (>50K or ≤50K)

Features: Age, education, occupation, workclass, hours-per-week, marital status, etc.

⚙️ Methodology

Data preprocessing and label encoding

Correlation analysis using heatmaps

Models:

Linear Regression

Linear SVM (LinearSVC)

5-Fold Cross-Validation

Balanced Accuracy used for evaluation

📈 Key Results

Linear SVM outperforms Linear Regression in balanced accuracy

Linear Regression struggles with class imbalance

High overall accuracy is misleading without balanced metrics

Linear SVM provides better generalization and stability

🛠️ Tools

Python, NumPy, Pandas, Scikit-learn, Matplotlib, Jupyter Notebook

📄 Report

A detailed PDF report is included in this repository.

👤 Author

Himanshu Beri
