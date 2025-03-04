**Machine Learning Lab Experiments Summary**

## **Experiment 8: Support Vector Machine (SVM) Classification**
### **Objective:**
- Implement the **Support Vector Machine (SVM)** classification algorithm.
- Measure accuracy by varying **kernel functions**.
- Tune the model using **regularization (C) and gamma parameters**.

### **Steps Performed:**
1. **Data Preprocessing**: Loaded dataset, handled missing values, performed encoding and scaling.
2. **Train-Test Split**: Divided dataset into 80% training and 20% testing.
3. **SVM Implementation**:
   - Applied SVM classifier with different kernels: **Linear, Polynomial, and RBF**.
   - Tuned hyperparameters like `C` and `gamma`.
4. **Evaluation**:
   - Computed accuracy for each kernel.
   - Observed performance variations based on kernel selection and tuning.

### **Results:**
- **Linear Kernel**: Performed well on linearly separable data.
- **Polynomial & RBF Kernels**: Showed better accuracy on complex data patterns.

---

## **Experiment 9: K-Means Clustering**
### **Objective:**
- Implement **K-Means Clustering**.
- Analyze the effect of **varying the number of clusters (K)**.
- Find the **optimal K value** using the **Elbow Method**.

### **Steps Performed:**
1. **Data Preprocessing**: Selected relevant numerical features and applied **feature scaling**.
2. **K-Means Implementation**:
   - Applied K-Means for different values of `K` (from 1 to 10).
   - Plotted the **Elbow Curve** to determine the optimal number of clusters.
3. **Visualization**:
   - Plotted clustered data and cluster centroids for visual analysis.

### **Results:**
- Found the **optimal K value** using the **Elbow Method**.
- Clustered data points based on similarities in features.
- Observed changes in cluster compactness as `K` varied.

---

## **Experiment 10: Recommendation System using Nearest Neighbor**
### **Objective:**
- Implement a **Recommendation System** using the **Nearest Neighbor algorithm**.
- Recommend similar data points (cars) based on feature similarity.

### **Steps Performed:**
1. **Data Preprocessing**: Selected numerical features and applied **Standard Scaling**.
2. **Nearest Neighbors Model**:
   - Implemented **K-Nearest Neighbors (KNN)** for recommendation.
   - Trained the model with `n_neighbors=5`.
3. **Generating Recommendations**:
   - Selected a **query car** and found its **5 nearest neighbors**.
   - Printed the recommended cars based on similarity.
4. **Custom Input Testing**:
   - Provided **manual input features** to get recommendations.

### **Results:**
- Successfully recommended **top 5 similar cars** based on numerical attributes.
- Observed the effect of different feature scaling techniques on recommendations.

---

## **Conclusion**
- Successfully implemented and analyzed **SVM classification, K-Means clustering, and Nearest Neighbor recommendation system**.
- Explored **hyperparameter tuning, visualization, and real-world applicability** of ML models.
- Results showed **significant improvements** in prediction accuracy and clustering efficiency when optimizing parameters.

---

### **Next Steps**
✅ Upload this summary along with **code and datasets** to GitHub.
✅ Write detailed **README files** for each experiment.
✅ Explore real-world applications of these ML models in business and research.

---

🔹 **Author:** Yash Patil  
🔹 **GitHub Repository:** *[\[Your Repo Link\]](https://github.com/yashpatil-1/Machine-Learning-LAB.git)*

