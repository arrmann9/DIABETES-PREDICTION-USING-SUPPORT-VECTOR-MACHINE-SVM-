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
