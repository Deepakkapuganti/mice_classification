# Classification of Mice Based on Protein Expression Levels

##  Project Overview
Understanding the molecular mechanisms underlying learning and memory is a major challenge in neuroscience, especially in the context of **Down syndrome (Trisomy 21)**. This project applies **machine learning techniques** to classify mice based on **protein expression levels** measured in the cerebral cortex.

The dataset contains protein expression profiles from **control and trisomic mice**, subjected to **context fear conditioning** and treated with either **saline or memantine**. The project aims to identify biological markers associated with learning, genotype differences, and therapeutic intervention.

---

##  Objectives
- Develop a machine learning model to classify mice into **8 distinct classes** based on genotype, behavior, and treatment.
- Identify **key discriminant proteins** responsible for classification.
- Analyze the impact of **genotype (control vs. trisomic)**, **behavior (stimulated vs. not stimulated)**, and **treatment (saline vs. memantine)** on protein expression.
- Evaluate the potential therapeutic effects of **memantine** in trisomic mice.

---

##  Dataset Description
- **Domain:** Biology / Neuroscience / Bioinformatics  
- **Type:** Multivariate  
- **Associated Tasks:** Classification, Clustering  
- **Total Instances:** 1080  
- **Features:** 80  
  - 77 protein / protein modification expression levels  
  - Mouse ID, Genotype, Treatment  

Protein expression levels were measured from the **nuclear fraction of the cerebral cortex** of mice after a **context fear conditioning task**, which is widely used to study associative learning.

Each mouse contributes **15 measurements per protein**, providing a detailed molecular profile.

---

##  Class Distribution

| Class Label | Description | Number of Mice |
|------------|------------|----------------|
| c-CS-s | Control, Stimulated, Saline | 9 |
| c-CS-m | Control, Stimulated, Memantine | 10 |
| c-SC-s | Control, Not Stimulated, Saline | 9 |
| c-SC-m | Control, Not Stimulated, Memantine | 10 |
| t-CS-s | Trisomic, Stimulated, Saline | 7 |
| t-CS-m | Trisomic, Stimulated, Memantine | 9 |
| t-SC-s | Trisomic, Not Stimulated, Saline | 9 |
| t-SC-m | Trisomic, Not Stimulated, Memantine | 9 |

---

##  Machine Learning Workflow
1. **Data Preprocessing**
   - Handling missing values
   - Normalization and scaling
   - Encoding categorical variables

2. **Exploratory Data Analysis (EDA)**
   - Distribution of protein expression levels
   - Class-wise comparison of features
   - Correlation analysis

3. **Feature Selection**
   - Statistical methods
   - Model-based feature importance

4. **Model Training**
   - Logistic Regression
   - Support Vector Machine (SVM)
   - Random Forest

5. **Model Evaluation**
   - Accuracy
   - Precision, Recall, and F1-score
   - Confusion Matrix

---

## Results & Observations
- Achieved strong classification performance across all 8 classes.
- Identified **key proteins** associated with learning and memory processes.
- Clear differences observed in protein expression between:
  - Control vs. Trisomic mice
  - Stimulated vs. Non-stimulated behavior
  - Saline vs. Memantine treatment
- Results suggest **memantine improves protein response** in trisomic mice, indicating its therapeutic potential.

---

##  Biological Significance
- Provides insight into molecular mechanisms of **associative learning**.
- Highlights protein dysregulation related to **Down syndrome**.
- Demonstrates the effectiveness of **machine learning in biological data analysis**.
- Supports data-driven evaluation of drug treatment effects.

---

## 🛠 Technologies Used
- **Programming Language:** Python  
- **Libraries:**  
  - NumPy  
  - Pandas  
  - Scikit-learn  
  - Matplotlib  
  - Seaborn  

---
