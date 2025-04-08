Credit Approval Decision Tree Project
This project implements two decision tree algorithms—C4.5 (using Gain Ratio) and CART (using Gini Index)—to classify credit approval decisions. The objective is to predict whether a credit application is approved (+) or denied (-) based on 15 features.

📂 Files
Siddarth_1.ipynb – Python implementation of C4.5 and CART decision trees.

training.data – Training dataset (553 records).

test.data – Test dataset (137 records).

README.md – Instructions to run the project.

report.pdf – (Coming soon) Detailed report explaining the algorithms and results.

📊 Dataset Description
Format: CSV

Features: A1 to A15

Target Label: A16 (+ for approved, - for denied)

Missing Values: Represented as ? and handled via median/middle-value imputation

Training Set: 553 records

Test Set: 137 records

🛠 Requirements
Python 3.7+

Libraries:

numpy

pandas

math

Install required libraries:

bash
Copy
Edit
pip install numpy pandas
To install Jupyter Notebook:

bash
Copy
Edit
pip install notebook
▶️ How to Run
Place all files in the same directory.

Launch Jupyter Notebook:

bash
Copy
Edit
jupyter notebook
Open Siddarth_1.ipynb in the Jupyter interface.

Run all cells sequentially (Shift + Enter or click "Run All").

The program will:

Load and preprocess the datasets.

Perform 10-fold cross-validation for both algorithms.

Evaluate the best model on the test dataset.

Display and compare the results.

✅ Expected Output
C4.5 (Gain Ratio)
Cross-Validation Accuracy: ~81.45%

Cross-Validation F1 Score: ~77.91%

CART (Gini Index)
Cross-Validation Accuracy: ~76.36%

Cross-Validation F1 Score: ~72.98%

Best Model
Based on: Highest F1 Score

Test Set Accuracy (C4.5): ~81.43%

Test Set F1 Score (C4.5): ~79.69%

📈 Comparison Summary
Model	Accuracy	F1 Score
C4.5	81.45%	77.91%
CART	76.36%	72.98%
Test Set (C4.5)	81.43%	79.69%
📝 Notes
Make sure training.data and test.data are in the same directory as the notebook.

Decision trees are limited to:

Max Depth: 10

Min Gain Threshold: 0.01 (to prevent overfitting)

🧰 Troubleshooting
File Not Found: Ensure the dataset files are correctly named and in the working directory.

Missing Libraries: Reinstall using pip install commands above.

Python Errors: Use Python version 3.7 or higher.

👤 Author
Cibi Siddarth
University of North Florida
School of Computing
