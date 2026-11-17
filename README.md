# Applied Data Science — Coursework

Homework, a Kaggle competition and the final project from the **Applied Data
Science** course (M.Sc. Data Science, 1401-1). All work is in Jupyter
notebooks, committed with outputs so they render on GitHub.

| Folder | What it is |
|---|---|
| [`homework/01-eda`](homework/01-eda) | Exploratory analysis and data cleaning |
| [`homework/02-regression`](homework/02-regression) | Regression: feature/target relationships, train/test split, model comparison |
| [`homework/03-classification`](homework/03-classification) | Binary and multi-class classification |
| [`kaggle-spaceship-titanic`](kaggle-spaceship-titanic) | Kaggle *Spaceship Titanic*: EDA, feature engineering and a submission |
| [`final-project-text-classification`](final-project-text-classification) | Final project: news text classification, from n-grams and TF-IDF to RNNs, attention and BERT |
| [`kaggle-learn-certificates`](kaggle-learn-certificates) | Kaggle Learn certificates completed for the course |

Homework 1–3 were done with Maryam Hokmabadi.

## Large files

The final presentation (`.pptx` and its images), zipped datasets and old
notebook checkpoints are on Google Drive under
`applied-data-science-coursework/`, to keep the repository small.

## Running

```bash
pip install numpy pandas matplotlib seaborn scikit-learn xgboost jupyter
jupyter lab
```

The final project was run on Google Colab with a GPU; it also needs
`transformers` and `torch`.
