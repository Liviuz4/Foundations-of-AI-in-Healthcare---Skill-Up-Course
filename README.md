# Foundations-of-AI-in-Healthcare---Skill-Up-Course

# Early Liver Disease Detection using Machine Learning 🏥🤖

## 📌 Project Overview
This project focuses on the development of a Machine Learning model to assist in the early diagnosis of liver disease. Using the **Indian Liver Patient Dataset (ILPD)**, I built a supervised classification model to predict whether a patient suffers from liver disease based on clinical blood test records (e.g., Bilirubin, Albumin, Enzymes).

This project serves as the final capstone for the **"Foundations of AI in Healthcare"** course, demonstrating the practical application of AI in a clinical setting.

## 🎓 About the Course: Foundations of AI in Healthcare
This project was developed as part of a specialized curriculum focused on bridging the gap between Medicine and Artificial Intelligence. 

**Key learning outcomes applied in this project:**
* **Clinical Data Handling:** Processing real-world medical datasets (cleaning, normalization, feature selection).
* **Supervised Learning:** Implementing classification algorithms for diagnosis.
* **Medical Metrics Evaluation:** Going beyond "Accuracy" to understand **Sensitivity** (Recall) and **Specificity**, which are critical for medical screening tools.
* **Decision Support:** Understanding how AI acts as a support tool for physicians, not a replacement.

## ⚙️ Methodology
1.  **Data Acquisition:** Loaded the Indian Liver Patient Dataset (583 records).
2.  **Exploratory Data Analysis (EDA):** Analyzed distributions and correlations between liver enzymes and disease status.
3.  **Data Preprocessing:** Handled categorical variables and split data into Training (80%) and Testing (20%) sets.
4.  **Model Training:** Implemented **Logistic Regression**, chosen for its interpretability in clinical environments.
5.  **Evaluation:** assessed model performance using a Confusion Matrix.

## 📊 Results & Clinical Impact
The Logistic Regression model achieved the following performance on the test set:

| Metric | Score | Clinical Interpretation |
|--------|-------|-------------------------|
| **Accuracy** | ~75% | Overall correctness of the model. |
| **Sensitivity** | **~90%** | The model is highly effective at detecting patients *with* disease (Minimizing False Negatives). |
| **Specificity** | ~30% | The capability to correctly identify healthy patients. |

**Insight:** The high sensitivity score suggests this model is well-suited for **preliminary screening**, where the priority is to ensure no potential cases are missed, even if it means some healthy patients require further testing.

## 🛠️ Technologies Used
* **Language:** Python 3.10+
* **Libraries:** * `pandas` (Data Manipulation)
    * `scikit-learn` (Machine Learning)
    * `matplotlib` / `seaborn` (Visualization)
* **Environment:** Jupyter Notebook

## 📂 Repository Structure
* `ProyectoFinalCursoIA.ipynb`: The main Jupyter Notebook containing the code and analysis.
* `indian_liver_patient_dataset.csv`: The dataset used for training and testing.
* `Early Liver Disease Detection Project Submission.pdf`: Detailed project report and screenshots.

---
*This project is for educational purposes and demonstrates the potential of AI as a Clinical Decision Support System (CDSS).*
