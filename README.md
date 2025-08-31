# 🧠 Stress Level Prediction (Classification)

This project predicts **student stress levels (Low/Medium/High)** from a dataset of psychological, social, and lifestyle indicators.  

## 🔹 Features
- **Data Preprocessing & Cleaning**
  - No missing values
  - Scaling, encoding, and train/test split

- **Exploratory Data Analysis (EDA)**
  - Distributions & correlations
  - Heatmaps and group comparisons

- **Machine Learning Models**
  - Logistic Regression
  - Random Forest
  - Gradient Boosting
  - Cross-validation & performance metrics (Accuracy, F1, Confusion Matrix)

- **Explainability**
  - **SHAP**: global feature importance, dependence plots
  - **LIME**: instance-level local explanations

- **Deliverables**
  - Cleaned dataset
  - Trained models (`joblib`)
  - Visualizations & explainability reports

## 🔹 Example Insights
- Higher anxiety and depression scores strongly correlate with higher stress.
- Peer pressure & academic load are significant contributors.
- Strong social support and self-esteem reduce stress likelihood.

## 🔹 Tech Stack
- Python (Pandas, NumPy, Scikit-learn)
- Seaborn / Matplotlib for EDA
- SHAP & LIME for XAI
- Colab-friendly Jupyter Notebook

## 🔹 How to Run
1. Clone this repo
2. Upload dataset to Colab / mount Google Drive
3. Run `Stress_Level_Prediction_Project_(Classification).ipynb`
4. View outputs, explanations, and saved artifacts in `/artifacts`

---

### 📊 Why this matters
Understanding **why** a model predicts high stress helps educators, psychologists, and organizations design interventions. This project demonstrates a full **ML pipeline + explainability** in an accessible way.

---
