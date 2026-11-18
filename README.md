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

The final project presentation is in
[`final-project-text-classification/presentation/`](final-project-text-classification/presentation)
(PowerPoint and PDF, with the figures used in it).

## Datasets

Public datasets are linked rather than stored. To re-run a notebook, download
the data and save it next to the notebook under the name shown.

| File expected | Used in | Source |
|---|---|---|
| `dataset.csv` | homework/01-eda | `CreditCard` from the AER package — [docs](https://vincentarelbundock.github.io/Rdatasets/doc/AER/CreditCard.html) |
| `train.csv`, `test.csv`, `sample_submission.csv` | kaggle-spaceship-titanic | Kaggle competition *Spaceship Titanic* — [data](https://www.kaggle.com/competitions/spaceship-titanic/data) |

The final project's Persian news dataset (`dataset.json`) and the small course
files are kept in the repository; `kaggle-spaceship-titanic/submission.csv` is my
competition submission.

## Running

```bash
pip install numpy pandas matplotlib seaborn scikit-learn xgboost jupyter
jupyter lab
```

The final project was run on Google Colab with a GPU; it also needs
`transformers` and `torch`.
