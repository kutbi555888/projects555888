# Machine Learning Flow Chart  
Baseline Model → Model Improvement

---

## 🔹 BASELINE MODEL

### 1. Kutubxonalar
- NumPy  
- Pandas  
- Matplotlib / Seaborn  
- Scikit-learn  

---

### 2. DATA LOADING + DASTLABKI TAHLIL (EDA)
- Datasetni yuklash  
- Shape, info(), describe()  
- Target va featurelarni aniqlash  
- Dastlabki statistik tahlil  

---

### 3. Featurelar ma’nosi
- Har bir feature mazmuni  
- Numerical va Categorical ajratish  
- Target bilan bog‘liqlikni tushunish  

---

### 4. Missing Valuelarni to‘ldirish
- Numerical → median / mean  
- Categorical → most frequent (mode)  
- Train va test alohida ishlov  

---

### 5. Encoding
- Label Encoding  
- One-Hot Encoding  
- Zarur bo‘lsa Target Encoding  

---

### 6. Scaling
- StandardScaler  
- MinMaxScaler  
- Modelga mos scaling  

---

### 7. Baseline Model Train
- Logistic Regression  
- Decision Tree  
- Random Forest  
- KNN  
- LightGBM (baseline)

---

## 🔹 MODEL IMPROVEMENT

---

### 1. Problem Statement + Baseline bilan solishtirish
- Baseline natijalarini tahlil qilish  
- Muammo va kamchiliklarni aniqlash  

---

### 2. Model Improvementning asosiy maqsadi
- Model aniqligini oshirish  
- Generalization yaxshilash  
- Overfittingni kamaytirish  

---

### 3. ADVANCED EDA (Exploratory Data Analysis)
- Correlation Heatmap  
- Distribution & Skewness  
- Outlier Analysis  
- Feature–Target Relationship  
- Categorical profiling  

---

### 4. Missing Valuelarni to‘ldirish (Advanced)
- Median / Mode  
- KNN Imputer  
- MICE (Iterative Imputer)  

---

### 5. Scaling
- Pipeline ichida scaling  
- Leakage oldini olish  

---

### 6. Feature Engineering
- Interaction features  
- Ratio features  
- Log / transformation  
- Domain-based featurelar  

---

### 7. Feature Selection
- Correlation Heatmap  
- Multicollinearity removal  
- RFE (Recursive Feature Elimination)  

---

### 8. Advanced Model Train

#### Tree Based Family
- Decision Tree  
- Random Forest  

#### Linear, Distance Based, Probabilistic Family
- Logistic Regression  
- KNN  
- Naive Bayes  

#### Boosting Family
- XGBoost  
- LightGBM  
- CatBoost  

---

### 9. Stratified K-Fold
- Stratified K-Fold CV  
- XGBoost  
- LightGBM  

---

### 10. Hyperparameter Tuning (RandomizedSearchCV)
- XGBoost + Final Evaluation (Test)  
- LightGBM + Final Evaluation (Test)  
- CatBoost + Final Evaluation (Test)  

---

### 11. Optuna Tuning
- Optuna (LightGBM)  
- Best hyperparameters  
- Final Evaluation (Test)  

---

### 12. Tabulate Compare
- Barcha modellarning taqqoslanishi  
- Accuracy, Precision, Recall, F1-score  

---

### 13. Final Model Save
- Eng yaxshi model tanlash  
- joblib / pickle orqali saqlash  

---

