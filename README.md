# 🎬 Film Review Sentiment Classification

A supervised machine learning project that builds and evaluates sentiment classifiers for movie reviews. The goal is to distinguish positive and negative reviews using natural language processing techniques and achieve a minimum F1 score of **0.85**.

---

## 📌 Objective

Build a binary classification model to automatically detect negative film reviews using labeled data from IMDB. Explore different modeling techniques and analyze their ability to generalize to unseen reviews.

---

## 🧠 Project Tasks

1. **Data Loading & Cleaning**
   - Handle missing values and check data consistency.
   - Analyze class balance.
2. **Preprocessing & Feature Engineering**
   - Apply tokenization, lowercasing, and stopword removal.
   - Transform text into numerical vectors using TF-IDF.
3. **Model Training & Evaluation**
   - Train at least 3 models: logistic regression, random forest, and gradient boosting.
   - Evaluate using F1 score and classification reports.
4. **Text Generation & Predictions**
   - Create sample reviews and test predictions across all models.
   - Analyze discrepancies between models.
5. **Bonus (Optional)**
   - Use BERT embeddings on a small subset of data for comparison.

---

## 📊 Dataset

- **File:** `imdb_reviews.tsv`
- **Content:** Labeled IMDB reviews for training and testing
- **Columns:**
  - `review`: Review text
  - `pos`: Label – 1 for positive, 0 for negative
  - `ds_part`: Indicates if sample is from `train` or `test`
- **Source:** ACL 2011, Maas et al.

---

## 🧪 Models Used

- Logistic Regression
- Random Forest
- Gradient Boosting
- (Optional) BERT embeddings + simple classifier

---

## 🛠️ Tools & Libraries Used

- Python
- pandas
- numpy
- matplotlib
- nltk
- scikit-learn
- torch

---

## 📁 Project Structure

```
film-review-sentiment/
│
├── sentiment_analysis_imdb_reviews.ipynb
├── imdb_reviews.tsv
├── requirements.txt
└── README.md
```

---

## ✅ Status

✔️ Project completed as part of the **TripleTen Bootcamp** – Sprint: *Text Classification & NLP*

---

## 📌 Author

David Villanueva  
[LinkedIn](https://www.linkedin.com/in/david-villanueva-59659727)  
[GitHub](https://github.com/lolapaul)
