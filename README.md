# README

## Project Overview
This project focuses on analyzing a mental health dataset and training machine learning models to predict depression. The workflow consists of two main steps:
1. **Exploratory Data Analysis:** Finding correlations, trends, and interesting groupings. Visualizing the data to see patterns and outliers.
2. **Model Training and Prediction:** Using several different models make predictions.

## File Structure
```
.
├── data
    ├── train.csv                         # Raw training dataset
    ├── test.csv                          # Raw test dataset
├── EDA.ipynb                          # Data analysis and visualization
├── transformer.ipynb                  # Transformer model
├── README.md                          # Documentation
```
## Requirements

- Python 3.7+ (or higher)
- [NumPy](https://pypi.org/project/numpy/)
- [pandas](https://pypi.org/project/pandas/)
- [scikit-learn](https://pypi.org/project/scikit-learn/) (>= 1.2 recommended)
- [CatBoost](https://pypi.org/project/catboost/)
- [XGBoost](https://pypi.org/project/xgboost/)
- [matplotlib](https://pypi.org/project/matplotlib/) or [seaborn](https://pypi.org/project/seaborn/) (if visualization is included)

You can install them via `pip`:

```bash
pip install numpy pandas scikit-learn catboost xgboost matplotlib seaborn
```
Or via `conda`:

```bash
conda install -c conda-forge numpy pandas scikit-learn catboost xgboost matplotlib seaborn
```

## Installation and Model Details




## Notes
- The scripts assume `train.csv` and `test.csv` are available in the working directory.
- The dataset includes categorical and numerical features, which are handled using different preprocessing techniques.

If you encounter any issues, ensure all dependencies are installed and that the input files are correctly formatted.
