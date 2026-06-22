# 🎬 IMDb Top 1000 Movies — EDA

Exploratory Data Analysis on the IMDb Top 1000 Movies dataset using Python, pandas, and NumPy.

## 📌 Questions Answered
1. Which genres have the highest average IMDb rating?
2. Who are the top 10 directors by number of movies?
3. Is there a correlation between number of votes and rating?
4. How have average ratings changed across decades?
5. Which movies have missing revenue data — is there a pattern?

## 🔍 Key Findings
- War, Western and Film-Noir have the highest average ratings — not mainstream genres
- Christopher Nolan leads in average rating (8.46) among top directors
- Moderate correlation (0.495) between votes and rating — only Very High vote movies show a clear jump
- Older decades have fewer but higher-rated movies — time filters out bad films
- Missing gross data is concentrated in pre-1980s movies (30–45%) due to historical record-keeping gaps

## 🛠️ Tech Stack
- Python 3.14.2
- pandas
- NumPy
- Jupyter Notebook

## 📁 Files
| File | Description |
|---|---|
| `imdb_eda.ipynb` | Main analysis notebook |
| `imdb_top_1000.csv` | Original dataset |
| `imdb_top_1000_cleaned.csv` | Cleaned dataset with engineered features |

## 📊 Dataset
[IMDb Top 1000 Movies — Kaggle](https://www.kaggle.com/datasets/harshitshankhdhar/imdb-dataset-of-top-1000-movies-and-tv-shows)