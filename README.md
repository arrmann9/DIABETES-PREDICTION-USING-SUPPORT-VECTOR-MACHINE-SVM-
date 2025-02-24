# DIABETES PREDICTION USING SUPPORT VECTOR MACHINE (SVM)

This project implements a Diabetes Prediction Model using Support Vector Machine (SVM). The model is trained on the Pima Indians Diabetes Dataset to predict whether a person has diabetes based on key medical features.

**Dataset:**
The dataset consists of multiple health-related parameters such as: Pregnancies,
Glucose Level,
Blood Pressure,
Skin Thickness,
Insulin Level,
BMI,
Diabetes Pedigree Function,
Age

**Outcome:** (0: Non-Diabetic, 1: Diabetic)

**Technologies Used:**
* Python
* NumPy, Pandas
* Scikit-learn (SVM, StandardScaler, Train-Test Split, Accuracy Score)
  {**Why Use SVM?**

* Effective for Binary Classification – Since the outcome is either diabetic (1) or non-diabetic (0), SVM is well-suited for this type of problem.
* Works Well on Small to Medium Datasets – The Pima Indians Diabetes Dataset is not huge, and SVM performs well in such cases.
* Maximizes the Decision Boundary – SVM finds the optimal hyperplane that best separates diabetic and non-diabetic cases, improving classification performance.
* Robust to High-Dimensional Data – Even if some features don’t contribute much, SVM efficiently handles them by using kernel tricks (though this model uses a linear kernel).
* Good Performance with Standardization – Since the dataset features have different ranges, using StandardScaler improves SVM’s performance.}

**Project Workflow:**
* Load and preprocess the dataset using StandardScaler.
* Split data into training (80%) and testing (20%) sets.

**Train an SVM Classifier**
* Evaluate model performance using accuracy score.
* Make predictions on new input data.

**Installation & Usage:**
* Install Dependencies: *pip install numpy pandas scikit-learn**
* Run the Model
  
**Model Performance**
* Training Accuracy: 78.6%
* Testing Accuracy: 77.2%

**Example Prediction:**
For an input like (7,196,90,0,0,39.8,0.451,41), the model predicts:
*-The person is diabetic*

**Future Improvements:**
Tune hyperparameters for better accuracy.
Experiment with different ML models (Random Forest, XGBoost, etc.).
Deploy the model as a web app.

**Author:**
Arman Ahmaad
-> Connect with me on LinkedIn: [www.linkedin.com/in/armanahmad16]
