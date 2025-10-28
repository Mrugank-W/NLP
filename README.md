# Experiment 9 — NLP Notebook (exp9.ipynb)

Overview
--------
This folder contains Experiment 9: a Jupyter/Colab notebook (exp9.ipynb) that performs a complete NLP classification experiment using the 20 Newsgroups dataset. The notebook demonstrates data loading, preprocessing, TF-IDF feature extraction, model training (Logistic Regression), evaluation, and visualizations.

Quick highlights
----------------
- Notebook: exp9.ipynb
- Purpose: Text classification on the 20 Newsgroups dataset using TF-IDF + Logistic Regression
- Key sections:
  - Imports and environment
  - Data loading & inspection (20 Newsgroups)
  - Text preprocessing (basic cleaning)
  - Feature extraction (TfidfVectorizer)
  - Model training & evaluation (LogisticRegression)
  - Results & visualizations (confusion matrix, classification report)

How to run
----------
1. In Google Colab: Upload or open `exp9.ipynb` and run cells sequentially. Colab provides required compute and displays plots inline.
2. Locally:
   - python -m venv .venv
   - source .venv/bin/activate  (macOS / Linux) or .venv\Scripts\activate (Windows)
   - pip install -r experiments/exp9/requirements.txt
   - jupyter notebook
   - open `experiments/exp9/exp9.ipynb` and run cells.

Dependencies
------------
Pinned versions are provided in requirements.txt. Install with:

    pip install -r experiments/exp9/requirements.txt

Data
----
This notebook uses scikit-learn's built-in 20 Newsgroups dataset (downloaded automatically).

Suggested repository layout
--------------------------
- /experiments/exp9/
  - exp9.ipynb          <- notebook
  - exp9.md             <- this README
  - requirements.txt    <- package pins used for the experiment

Notes
-----
- The notebook is self-contained and downloads the dataset on first run. If you prefer another dataset, replace the data-loading cell.
- Consider running in Colab for faster downloads and convenience.
https://colab.research.google.com/drive/18ih6L82TCa8NUkrKCJnRFK4L5x8K1Lqq#scrollTo=89d2f819
