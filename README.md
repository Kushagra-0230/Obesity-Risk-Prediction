# 🧠 Obesity Risk Prediction using Ensemble Learning

## 📌 Overview
This machine learning project focuses on classifying individuals into obesity risk categories based on lifestyle and health-related features. The goal is to explore and compare traditional ML models with advanced ensemble methods to achieve high accuracy and real-world interpretability.

---

## 🧪 Dataset
- Records: 20,000+ individuals.
- Features: 18 (eating habits, lifestyle, family history, etc.)
- Type: Multiclass classification (target = obesity category)

---

## ✅ Models Implemented

### 🔹 Traditional Baseline Models
- Logistic Regression
- Support vector machine (SVM)
- K-Nearest Neighbors (KNN)
- Gaussian Biasing

### 🔹 Ensemble Techniques Explored
- Random Forest (Bagging)
- AdaBoost (Boosting)
- Gradient Boosting
- XGBoost
- Voting Classifier (Hard & Soft)
- Stacking Classifier

---

### 🌍 Real - Life Application
- Integrated a custom human-readable message showing top 2 predicted classes with their confidence scores.
- These top 2 predictions capture ~99% of test cases, boosting trust and interpretability for users.

---

## ⚙ Model Tuning & Evaluation
- Hyperparameter tuning via GridSearchCV with cross-validation.
- Train/Test Split for final evaluation.
- Evaluation Metrics:
  - Accuracy
  - Precision, Recall, F1-Score
  - Confusion Matrix
  - Class-wise heatmaps

---

## ⚗ Experimental Logic-Based Model
An experimental self-crafted model using custom rules achieved 90.9% accuracy, but required manual adjustment when train-test splits changed. A dynamic version of this model holds strong potential, it has been commented as of now.

---

## 💻 How to Run
- Download the dataset and code file available in the repository.
- Install all the required libraries, as mentioned in the first non-commented code cell.
- Run all cells sequentially from top to bottom.
- Review the results, including:
  - Model evaluations (Accuracy, Precision, Recall, and F1 Score) for all models.
  - Visualizations (Probability plots, heatmaps, and combined dataframes).
  - Enhanced output with Top-2 predictions and formatted messaging.

---

## 🚀 Future Scope

- 🔄 Dynamic Rule-Based Modeling: Improving the experimental logic-based model to auto-adapt to train/test splits to increase the accuracy.

- 🌐 Web App Deployment: Building a user-friendly interface to allow real-time predictions based on user input.

- 🧪 Real-World Testing: Validating the model on external health datasets to assess generalization.

---

Feel free to reach out via GitHub issues or LinkedIn if you'd like to collaborate, suggest improvements, or learn more!
