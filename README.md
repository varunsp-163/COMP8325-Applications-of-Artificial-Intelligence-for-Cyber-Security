# BODMAS Malware Classification

Multi-class malware family classification on the BODMAS dataset using Logistic Regression and Random Forest.

## Requirements

```
numpy
pandas
scikit-learn
matplotlib
joblib
```

```bash
pip install numpy pandas scikit-learn matplotlib joblib
```

## How to Run

Both notebooks are designed for **Google Colab**. Create the `BODMAS_Assignment/` folder to your Google Drive under `MyDrive`, then open and run each notebook top to bottom.

- `logistic_final_submit.ipynb` - Logistic Regression training, evaluation, and holdout prediction
- `random_final_submit.ipynb` - Random Forest training, evaluation, and holdout prediction

### Running Locally

Comment out the Drive mount cell and update `PROJECT_DIR` to your local path:

```python
# from google.colab import drive
# drive.mount('/content/drive')

PROJECT_DIR = "/path/to/BODMAS_Assignment"
```

## Dataset Structure

```
BODMAS_Assignment_Final/
├── dataset/
│   ├── bodmas.npz
│   └── bodmas_metadata.csv
│
├── HoldOutDataSet/
│   ├── bodmas_metadata_train_test.csv
│   ├── bodmas_holdout.npz
│   ├── bodmas_metadata_holdout.csv
│   └── bodmas_malware_category.csv
│
├── randomforest/(to store the outputs)
├── logisticregression/(to store the outputs)
├── random_final_submit.ipynb
└── logistic_final_submit.ipynb
```