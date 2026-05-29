# BODMAS Malware Category Classification

This project trains and evaluates two machine learning models for malware category classification using the BODMAS dataset:

1. Logistic Regression
2. Random Forest

---

## Project Structure

```text
BODMAS_Assignment/
│
├── dataset/
│   ├── bodmas.npz
│   ├── bodmas_metadata.csv
│   └── bodmas_malware_category.csv
│
├── HoldOutDataSet/
│   ├── bodmas_holdout.npz
│   ├── bodmas_metadata_holdout.csv
│   └── bodmas_malware_category.csv
│
├── logisticregression/
│   ├── logistic_regression_model.joblib
│   ├── label_encoder.joblib
│   ├── lr_class_distribution.csv
│   ├── lr_train_tpr_fpr.csv
│   ├── lr_test_tpr_fpr.csv
│   └── lr_results_summary.csv
│
├── randomforest/
│   ├── random_forest_model.joblib
│   ├── label_encoder.joblib
│   ├── rf_class_distribution.csv
│   ├── rf_train_tpr_fpr.csv
│   ├── rf_test_tpr_fpr.csv
│   └── rf_results_summary.csv
│
├── logistic_final_submit.ipynb
└── random_final_submit.ipynb
