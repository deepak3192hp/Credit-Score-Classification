# Credit Score Classification

This project analyzes customer financial and behavioral data to classify credit scores as Good, Standard, or Bad. It follows a data science workflow including exploratory data analysis, feature engineering, preprocessing, model training, and evaluation.

## Project overview

The notebook in this repository explores a credit dataset and demonstrates:

- Data loading and inspection
- Missing value handling
- Categorical feature encoding
- Model training for credit score prediction
- Evaluation using classification metrics
- Visual inspection of feature relationships

## Files in this repository

- `Credit_score_classification_Project.ipynb` — complete Jupyter notebook with the workflow
- `README.md` — project description and setup guide

## Environment setup

Create a virtual environment and install the dependencies:

```bash
python -m venv .venv
source .venv/bin/activate   # On Windows: .venv\Scripts\activate
pip install -r requirements.txt
```

## Run the notebook

Open the notebook with Jupyter:

```bash
jupyter notebook
```

Then open `Credit_score_classification_Project.ipynb` and run the cells in order.

## Notes

The notebook originally uses a Google Drive file path:

```python
pd.read_csv('/content/drive/My Drive/Colab Notebooks/Credit_Score_Classification_Train.csv')
```

For local execution, replace this with the path to your dataset CSV file, for example:

```python
dataset = pd.read_csv('data/Credit_Score_Classification_Train.csv')
```

## Typical workflow inside the project

1. Load the credit dataset
2. Inspect the data shape and columns
3. Check missing values and data types
4. Encode categorical variables
5. Train a classification model
6. Evaluate model performance and interpret results

## Dependencies

The project uses common Python data science libraries, including:

- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn

## License

This repository is intended for educational and personal project use.
