# TASK--7-ELEVATE-LABS
🧠 SVM for Breast Cancer Classification

This project demonstrates how to apply **Support Vector Machines (SVM)** for both **linear** and **non-linear** classification using the **Breast Cancer Wisconsin Dataset**. The implementation focuses on understanding the power of SVMs in distinguishing between malignant and benign tumors, supported by visualization and hyperparameter tuning.

 📌 Objectives

* Apply SVMs to a real-world binary classification problem
* Compare linear and RBF kernels
* Visualize decision boundaries in 2D space using PCA
* Tune hyperparameters `C` and `gamma` using Grid Search
* Evaluate model performance with cross-validation

 🧰 Tools & Libraries

* Python
* Scikit-learn
* NumPy
* Pandas
* Matplotlib & Seaborn
📊 Dataset

The dataset used is `breast-cancer.csv`, which contains features computed from digitized images of breast mass cell nuclei. The goal is to classify tumors as **Malignant (M)** or **Benign (B)**.
 📈 Workflow

1. **Data Preprocessing**: Clean the dataset, encode labels, and scale features.
2. **Dimensionality Reduction**: Use PCA to project features into 2D for easy visualization.
3. **Model Training**: Train SVMs using both linear and RBF kernels.
4. **Visualization**: Plot decision boundaries in 2D PCA space.
5. **Hyperparameter Tuning**: Use `GridSearchCV` to find optimal values for `C` and `gamma`.
6. **Evaluation**: Evaluate performance using cross-validation and classification reports.
📌 Results

The RBF kernel outperformed the linear model in terms of classification accuracy and flexibility in decision boundaries, especially when using optimized hyperparameters.
💡 Future Work

* Extend to multiclass classification tasks
* Integrate more feature selection techniques
* Deploy as a web application for demonstration

