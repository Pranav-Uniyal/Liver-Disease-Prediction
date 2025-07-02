# Liver Disease Prediction System

A machine learning system that attempts to predict liver disease using various classification algorithms. This project is currently experimental — accuracy is modest, but it lays the groundwork for future improvements.

---

## 📌 Project Status

⚠️ **Not production-ready**  
This project currently does **not meet clinical reliability standards**, but it is a good foundation for further research, experimentation, and community contributions.

---

##  Models Implemented

- **Support Vector Machine (SVM)**
- **Logistic Regression**

---

##  Evaluation Metrics

### 🔹 SVM (Linear, `C=1.0`, `gamma=0.1`, `class_weight=balanced`)

| Metric        | Class 0 (No Disease) | Class 1 (Liver Disease) |
|---------------|----------------------|--------------------------|
| Precision     | 0.42                 | 0.89                     |
| Recall        | 0.87                 | 0.48                     |
| F1-score      | 0.57                 | 0.63                     |
| **Accuracy**  | **60%**              |                          |

- **Observation**: High false negatives for diseased patients. Model struggles to generalize on minority class.

---

### 🔹 Logistic Regression (`class_weight=balanced`)

| Metric        | Class 0 (No Disease) | Class 1 (Liver Disease) |
|---------------|----------------------|--------------------------|
| Precision     | 0.42                 | 0.82                     |
| Recall        | 0.71                 | 0.57                     |
| F1-score      | 0.53                 | 0.68                     |
| **Accuracy**  | **61.6%**            |                          |

- **Observation**: Slightly better balance than SVM. Still weak for recall on Class 1.

---

##  Technologies Used

- Python 3.x
- Jupyter Notebook
- scikit-learn
- pandas, numpy, matplotlib

---
##  Setup Instructions

1. **Clone the repo**
   ```
   git clone https://github.com/your-username/liver-disease-prediction.git
   cd liver-disease-prediction
   ```
2. Run the notebook
   ```
   jupyter notebook Liver_Prediction.ipynb
   ```
---
## Contributions Welcome
This project is open to collaboration. If you have ideas to:

-->Improve classification performance

-->Perform better preprocessing

-->Add visualizations

Please fork the repo and submit a pull request!

---
⚠️ Disclaimer: This tool is not approved for medical use. It's an academic project intended for learning and experimentation only.

---
# Pranav Uniyal


