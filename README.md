# 🧠 Artificial Intelligence & Ethical Systems (AIES) - Lab Experiments

This repository contains practical experiments for the **AIES** course, focusing on detecting bias, understanding fairness, and improving transparency in AI systems.

---

## 📜 List of Experiments

### **Experiment 1: Detecting Algorithm Bias in a Dataset**
**Objective:**  
To identify and measure bias in a machine learning model trained on a dataset with sensitive attributes.

**Dataset:**  
Synthetic Hiring Dataset or any dataset with demographic attributes such as `gender`, `age`, or `race`.

**Key Steps:**
1. Load dataset and explore data.
2. Split into training and testing sets.
3. Train a classification model (e.g., Logistic Regression).
4. Evaluate accuracy and fairness metrics (Selection Rate, Demographic Parity Difference).
5. Visualize group-wise outcomes to detect bias.

**Expected Outcome:**  
Identification of any disparity in model predictions across different demographic groups.

---

### **Experiment 2: Impact of Data Quality on AI Fairness**
**Objective:**  
To analyze how data imbalance impacts AI model fairness and apply techniques to mitigate bias.

**Dataset:**  
German Credit Dataset (binary classification: good/bad credit risk).

**Key Steps:**
1. Load and inspect dataset (`.head()`, `.describe()`).
2. Train a baseline model (Logistic Regression).
3. Evaluate fairness using `fairlearn`.
4. Apply oversampling using SMOTE to balance data.
5. Compare fairness metrics before and after balancing.

**Expected Outcome:**  
Balanced datasets lead to more equitable model predictions without major loss in accuracy.

---

### **Experiment 3: Transparency in AI Decision-Making**
**Objective:**  
To understand the role of transparency in AI models and use Explainable AI (XAI) techniques to interpret predictions.

**Dataset:**  
Loan Approval Dataset or similar decision-making dataset.

**Key Steps:**
1. Train a classification model (e.g., Decision Tree, Random Forest).
2. Use XAI tools (LIME, SHAP) to explain individual predictions.
3. Visualize feature importance and decision paths.
4. Discuss how transparency helps build trust.

**Expected Outcome:**  
Clear explanation of AI model decisions, improving accountability and user trust.

---

## ⚙️ Software & Tools Required
- Python 3.x
- Jupyter Notebook / VS Code
- Libraries:
  - `numpy`
  - `pandas`
  - `scikit-learn`
  - `fairlearn`
  - `imbalanced-learn`
  - `matplotlib`
  - `seaborn`
  - `lime`
  - `shap`
---
