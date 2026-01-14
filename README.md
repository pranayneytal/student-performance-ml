# 🎓 Student Performance Prediction (Machine Learning)

This project predicts whether a student will **pass or fail** based on academic, behavioral, and demographic features using machine learning.

---

## 🧠 Problem Type
**Binary Classification**  
(Pass / Fail)

---

## 📊 Dataset
Student performance dataset containing:
- Academic scores
- Study habits
- Attendance and participation metrics
- Socio-demographic attributes

---

## ⚙️ Tech Stack
- Python
- pandas
- NumPy
- scikit-learn
- Jupyter Notebook
- Matplotlib & Seaborn

---

## 🛠️ Approach
1. Data loading and inspection
2. Feature selection and preprocessing
3. Train–test split
4. Model training
   - Logistic Regression
   - Decision Tree
5. Model evaluation using:
   - Accuracy
   - Precision
   - Recall
   - Confusion Matrix

---

## 📈 Results
| Model | Accuracy |
|------|----------|
| Logistic Regression | ~62% |
| Decision Tree | **~72%** |

Decision Tree performed better, indicating non-linear relationships between features and student performance.

---

## 🚀 How to Run
```bash
pip install -r requirements.txt
jupyter notebook
