# Handwritten Digit Classification using KNN  
## AI & ML Internship – Task 10

---

## Objective
The objective of this project is to classify **handwritten digits (0–9)** using the  
**K-Nearest Neighbors (KNN)** algorithm.  
The model learns patterns from pixel values of digit images and predicts the correct digit class.

---

##  Dataset
- **Dataset Name:** Digits Dataset
- **Source:** Built-in dataset from `scikit-learn`
- **Total Samples:** 1,797
- **Features:** 64 (8×8 pixel values)
- **Target Classes:** Digits from **0 to 9**

No external dataset download is required.

---

## Tools & Libraries
- Python  
- NumPy  
- Matplotlib  
- Scikit-learn  

---

##  Methodology
1. Loaded the handwritten digits dataset using `sklearn.datasets`
2. Visualized sample digit images
3. Split the dataset using stratified train-test split
4. Applied **StandardScaler** for feature normalization
5. Trained KNN models with different K values (3, 5, 7, 9)
6. Evaluated accuracy for each K
7. Selected the best K value based on accuracy
8. Evaluated final model using a **confusion matrix**
9. Saved all visual outputs as image files

---

##  Model Evaluation
### Metric Used:
- **Accuracy**

### Observations:
- Feature scaling significantly improves KNN performance
- Choosing the right K value is crucial
- The model achieves high accuracy for handwritten digit classification

---

##  Visualizations
The following plots are generated and saved:
- `sample_digits.png` – Sample handwritten digits
- `accuracy_vs_k.png` – Accuracy comparison for different K values
- `confusion_matrix.png` – Confusion matrix of final KNN model

---


