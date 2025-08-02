# 🧠 Machine Learning Classification Assignment

This repository contains a collection of classification tasks using machine learning models applied to datasets like **Biomes.csv** and **Titanic.csv**.
The goal is to explore text and numeric classification, model comparison, tuning, and evaluation using key performance metrics.

---


### Task 1: Text Classification - Biomes Dataset
- Used `CountVectorizer` to process biome names (text data).
- Trained a `MultinomialNB` classifier.
- Evaluated using:
  - Accuracy
  - Precision
  - Recall
  - Confusion Matrix

### Task 2: Decision Tree - Titanic Dataset
- Preprocessed missing values and encoded categorical variables.
- Trained a `DecisionTreeClassifier`.
- Visualized decision tree using `plot_tree`.
- Evaluated model using accuracy and confusion matrix.

### Task 3: GaussianNB - Iris/Wine Dataset
- Trained `GaussianNB` on numeric data.
- Compared performance with `LogisticRegression` and `DecisionTreeClassifier`.

### Task 4: Model Tuning - Decision Tree
- Tuned parameters:
  - `max_depth`
  - `min_samples_split`
- Plotted training vs testing accuracy to detect overfitting.

### Task 5: Random Forest vs Decision Tree
- Trained a `RandomForestClassifier`.
- Compared with standalone Decision Tree on:
  - Accuracy
  - Precision
  - Recall
- Plotted feature importance.

### Task 6: Boosting - AdaBoost & Gradient Boosting
- Trained both `AdaBoostClassifier` and `GradientBoostingClassifier`.
- Compared with Decision Tree and Random Forest.
- Evaluation metrics:
  - Accuracy
  - F1-score
  - Training Time

---

##  Datasets Used

- **Biomes.csv**  
  Used for text classification based on biome names and precipitation levels.

- **Titanic.csv**  
  Used for predicting survival based on passenger data.

---

##  Technologies Used

- **Python 3**
- **Pandas**
- **NumPy**
- **Scikit-learn**
- **Matplotlib**
- **Seaborn**
