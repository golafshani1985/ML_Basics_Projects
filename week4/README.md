# Week 4 - Titanic: Logistic Regression Modeling

**Goal:** Train and evaluate a Logistic Regression model to predict passenger survival on the Titanic dataset.

## Steps:
1. Load the preprocessed dataset (`titanic_processed.csv`).
2. Drop non-numeric or irrelevant columns (`name`, `sex`, `embarked`).
3. Apply encoding:
   - Convert `sex` → numeric (male = 0, female = 1)
   - Use one-hot encoding for `embarked`
4. Split the dataset into training and test sets.
5. Train a Logistic Regression model using `scikit-learn`.
6. Evaluate performance:
   - Accuracy
   - Confusion matrix
   - Classification report
7. Save model predictions for further analysis.
8. Export results as `titanic_logreg_results.csv`.

---

**Output Files:**
- `titanic_logreg_results.csv` – contains true vs. predicted labels.
- Model performance metrics printed in Colab.

---

📘 *Summary:*  
In this week, we built our first machine learning model on the Titanic dataset using Logistic Regression.  
We prepared the data, trained the model, and evaluated its predictive power — laying the foundation for more complex models in coming weeks.
