# 📩 Spam vs Ham Email Classifier

A simple beginner-friendly Machine Learning project that classifies emails as **Spam** or **Ham** (not spam).

## What this project does

1. Loads and explores a labeled email dataset (`emails.csv`).
2. Checks missing values and demonstrates simple text cleaning.
3. Converts text into numbers using **CountVectorizer** (demo) and **TF-IDF** (training).
4. Trains a **Multinomial Naive Bayes** classifier.
5. Evaluates predictions with **Precision, Recall, and F1-score**.
6. Saves the vectorizer and model together as `spam_detector.joblib` to predict new messages.

## Files

- `Spam_Ham_Simple_Section.ipynb` — step-by-step notebook
- `emails.csv` — labeled dataset (`text`, `spam`)
- `spam_detector.joblib` — saved model pipeline (created when the notebook runs)

## How to run

1. Download or clone this repository.
2. Install the required libraries:

   ```bash
   pip install pandas scikit-learn joblib notebook
   ```

3. Open the notebook:

   ```bash
   jupyter notebook Spam_Ham_Simple_Section.ipynb
   ```

4. Run the cells in order. Keep `emails.csv` in the same folder as the notebook.

## Labels

- **0 = Ham** (normal email)
- **1 = Spam** (unwanted email)

## Tools

Python · Pandas · Scikit-learn · Joblib · Jupyter Notebook
