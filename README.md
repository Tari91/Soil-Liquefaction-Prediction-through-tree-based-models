# Soil Liquefaction Prediction using Ensemble Models

This project simulates and predicts soil liquefaction potential using synthetic geotechnical and seismic data. It applies machine learning techniques such as Random Forest, Gradient Boosting, and Extra Trees classifiers for binary classification of liquefaction events.

## 📌 Features

- Generates realistic synthetic data for soil parameters and seismic attributes.
- Calculates simplified Cyclic Stress Ratio (CSR) and Cyclic Resistance Ratio (CRR).
- Labels liquefaction based on CSR vs CRR comparison.
- Preprocesses data with:
  - Imputation
  - Feature scaling
  - Handling class imbalance (oversampling, undersampling)
- Trains and evaluates models using:
  - Accuracy, AUC-ROC, AUC-PR
  - Confusion matrix, classification report
- Visualizes results via:
  - Confusion matrix heatmap
  - ROC and Precision-Recall curves
- Exports evaluation metrics to an Excel file.

## 🛠️ Requirements

Install the required libraries using:

```bash
pip install numpy pandas scikit-learn seaborn matplotlib openpyxl
🚀 How to Run
Clone the repository or use the script directly.

Run the script:

bash
Copy
Edit
python liquefaction_model.py
The script will:

Generate synthetic data

Preprocess it

Train and evaluate 3 classifiers

Save evaluation results to model_evaluation_results.xlsx

📁 Output Files
model_evaluation_results.xlsx: Excel sheet with model performance (Accuracy, AUC-ROC, AUC-PR)

📊 Example Metrics (Sample)
Model	Accuracy	AUC_ROC	AUC_PR
Random Forest	0.913	0.950	0.940
Gradient Boosting	0.907	0.948	0.935
Extra Trees	0.919	0.952	0.943

🧠 Notes
CSR and CRR are calculated using simplified assumptions for illustrative purposes.

The synthetic data generator can be extended to reflect more complex field behavior.

Intended for educational and prototyping purposes.

📬 Author
Tarinabo williamtarinabo@gmail.com
