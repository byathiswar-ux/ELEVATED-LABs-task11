
# Task 11: SVM – Breast Cancer Classification

##  Project Overview
This project is part of the AI & ML Internship Task 11. The objective is to build a **Support Vector Machine (SVM)** model to classify breast cancer tumors as **Malignant** or **Benign** using machine learning techniques.

The task focuses on understanding kernel-based classification, feature scaling, hyperparameter tuning, and model evaluation.

---

##  Tools & Technologies Used
- Python  
- Google Colab  
- Scikit-learn  
- Pandas  
- NumPy  
- Matplotlib  

---

##  Dataset
- **Source:** Kaggle Breast Cancer Dataset  
- **Target Column:** `diagnosis`  
  - Malignant (M) → 1  
  - Benign (B) → 0  

---

##  Workflow
1. Loaded and inspected the dataset  
2. Encoded target labels  
3. Split data into training and testing sets  
4. Applied **StandardScaler** for feature normalization  
5. Trained SVM with:
   - Linear Kernel  
   - RBF Kernel  
6. Performed hyperparameter tuning using **GridSearchCV**  
7. Evaluated model using:
   - Accuracy  
   - Confusion Matrix  
   - Classification Report  
8. Plotted **ROC Curve** and calculated **AUC score**  
9. Saved the final trained model using Pickle  




## Output
<img width="1356" height="408" alt="Image" src="https://github.com/user-attachments/assets/d0f24c87-c7ac-4c75-95ab-46e5a33cff15" />
<img width="1274" height="678" alt="Image" src="https://github.com/user-attachments/assets/29850d9a-f392-4aa9-a76a-8a7e7a996331" />
<img width="888" height="634" alt="Image" src="https://github.com/user-attachments/assets/1a3df4f4-a009-4e45-a0b0-af102ff90117" />
<img width="862" height="627" alt="Image" src="https://github.com/user-attachments/assets/f03ebda1-4d9f-4fc0-96ac-4197f1064f5a" />