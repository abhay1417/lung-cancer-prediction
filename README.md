# 🫁 Lung Cancer Survival Prediction

This machine learning project predicts whether a lung cancer patient will survive, based on medical and personal history. The dataset is highly imbalanced, so class weighting was used.

---

## 📁 Project Files

- `lung_cancer_prediction.ipynb` – Full notebook with preprocessing, training, and evaluation
- `lung_cancer_prediction.pdf` – Report version for submission

---

## 📊 Dataset Info

- **Rows:** 890,000+  
- **Target:** `survived` (0 = no, 1 = yes)  
- **Features:** Gender, age, smoking history, BMI, treatment, etc.

---

## 🧠 Model Details

- **Algorithm:** Random Forest Classifier  
- **Accuracy Achieved:** 77.22%  
- **Issue:** Class imbalance (only ~22% survived)  
- **Solution:** Used `class_weight='balanced'`

---

## 🛠️ Tools Used

- Python
- Pandas
- Scikit-learn
- Google Colab

---

## 👤 Author

**Abhay Ajay Palkar**  
Guided by: **Unified Mentor**
