# Sentiment Analysis for Women's Safety — Notebook

## Files
- `sentiment_analysis_womens_safety.ipynb` — the notebook (already run once, so you can see
  the results immediately when you open it; re-run any cell to refresh).
- `women_related_comments.csv` — the dataset. **Must stay in the same folder as the notebook.**

## How to run

### In Jupyter
1. Put both files in the same folder.
2. `pip install pandas numpy scikit-learn matplotlib nltk joblib jupyter`
3. `jupyter notebook` → open `sentiment_analysis_womens_safety.ipynb`
4. Run all cells (Cell → Run All), or step through one at a time.

### In VS Code
1. Put both files in the same folder, open the folder in VS Code.
2. Install the **Jupyter** and **Python** extensions if you don't have them.
3. Open `sentiment_analysis_womens_safety.ipynb` — VS Code will show it as a notebook.
4. Pick a Python kernel (top right), then "Run All".

The last cell asks you to type your own comment and shows the predicted sentiment — that one
needs to be run manually (it waits for your input).

## What it produces
- `labeled_comments.csv` — every comment with a positive/neutral/negative label
- `outputs/sentiment_bar_plot.png` and `outputs/sentiment_pie_chart.png` — charts
- `outputs/model_results.csv` — accuracy of all 6 models
- `models/sentiment_classifier.joblib` + `models/tfidf_vectorizer.joblib` — the saved best model
