# Data Science Portfolio

My data science projects and notebooks. MSc Data Science student at the University of Messina.

---

## 📊 Heart Failure Prediction

Binary classification project predicting heart disease risk based on clinical patient data.

### Dataset
- Source: Kaggle — Heart Failure Prediction
- ~900 patient records with 11 clinical features (age, cholesterol, chest pain type, etc.)
- Target: `HeartDisease` (0 = no disease, 1 = disease)

### Approach
1. **Exploratory Data Analysis (EDA)** — distributions, correlations, class balance
2. **Preprocessing** — encoding categorical variables, feature scaling, train/test split
3. **Modeling** — trained and compared 3 classifiers + K-Fold cross-validation
4. **Evaluation** — Accuracy, Precision, Recall, F1-Score

### Results

| Model | Accuracy | Precision | Recall | F1-Score |
|-------|----------|-----------|--------|----------|
| Logistic Regression | 0.8750 | 0.8990 | 0.8725 | 0.8856 |
| Random Forest | 0.8750 | 0.8911 | 0.8824 | 0.8867 |
| Decision Tree (K-Fold) | 0.7854 | 0.7974 | 0.8216 | 0.8083 |
| Decision Tree (single split) | 0.7554 | 0.7767 | 0.7843 | 0.7805 |

**Best model:** Logistic Regression / Random Forest (both ~87.5% accuracy, ~0.886 F1)

### Tools
`Python` · `pandas` · `scikit-learn` · `matplotlib` · `seaborn` · `Jupyter Notebook`

### Files
- `Heart Failure Prediction.ipynb` — full analysis and modeling notebook
- `heart.csv` — dataset

---

## 📬 Contact
- Email: maataouichaimaa@gmail.com
- Location: Messina, Italy
- Open to data science / machine learning internships
