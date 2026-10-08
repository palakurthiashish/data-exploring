# Data Exploring

A collection of Jupyter notebooks for practicing data cleaning, exploratory data analysis, classification, regression, and clustering with pandas and scikit-learn.

## Notebooks

- `data_cleaning.ipynb` - inspect and clean a product dataset.
- `data_exploaring.ipynb` and `data_exploring_pratice.ipynb` - explore tabular data with pandas.
- `food quality regression pratice14.pynb` and `food qualityregression pratice.ipynb` - food-quality modeling exercises.
- `food quallity classfication pratice 16.ipynb` - compare classification models.
- `_food qyality pratice 17.ipynb` - cluster food batches with K-means.

## Datasets

The repository includes food-quality regression, classification, and batch-clustering datasets, plus a synthetic student-details dataset. Student names have been replaced with generic identifiers.

The files ending in `.xls` are CSV-formatted text files, not Excel workbooks. Some notebooks refer to `.csv` filenames (for example, `students_details.csv` and `Food_Quality_Classification_Day15_Dataset.csv`), while the repository files retain their `.xls` extensions. Rename a dataset to the expected `.csv` filename or update the corresponding `pd.read_csv(...)` path in the notebook before running it.

`data_cleaning.ipynb` expects a `Product_details.csv` input file, which is not included in this repository.

## Getting started

Install Jupyter and the libraries used by the notebooks:

```bash
python -m pip install jupyter pandas numpy matplotlib scikit-learn
```

Start Jupyter from the repository directory:

```bash
jupyter notebook
```

Open a notebook and run its cells in order. Update input file paths as described above when needed.
