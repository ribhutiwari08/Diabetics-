

# **Diabetes Prediction Using Machine Learning**  

### **Overview**
This project aims to predict whether a person is diabetic based on medical diagnostic measurements using a **Random Forest Classifier**. The dataset includes various health indicators such as glucose levels, BMI, and age, which are analyzed and used to build a predictive model.  

---

## **Dataset**
- **Source**: The dataset used in this project contains medical diagnostic features and a target variable indicating diabetes status (Outcome: 0 = No Diabetes, 1 = Diabetes).  
- **Features**:
  - `Pregnancies`: Number of pregnancies.
  - `Glucose`: Plasma glucose concentration.
  - `BloodPressure`: Diastolic blood pressure (mm Hg).
  - `SkinThickness`: Triceps skinfold thickness (mm).
  - `Insulin`: 2-Hour serum insulin (mu U/ml).
  - `BMI`: Body Mass Index (weight in kg/(height in m)^2).
  - `DiabetesPedigreeFunction`: A function that scores likelihood of diabetes based on family history.
  - `Age`: Age of the person.  
- **Target**: `Outcome` (0 or 1).

---

## **Tools and Libraries Used**
- **Programming Language**: Python  
- **Libraries**:
  - **Data Analysis**: pandas, numpy
  - **Visualization**: matplotlib, seaborn
  - **Machine Learning**: scikit-learn
  - **Model Persistence**: joblib  

---

## **Project Workflow**
1. **Data Exploration and Preprocessing**:
   - Loaded and analyzed the dataset.
   - Checked for missing values and statistical summaries.
   - Performed feature selection and correlation analysis.  

2. **Model Training and Testing**:
   - Split the dataset into training (80%) and testing (20%) subsets.
   - Trained a **Random Forest Classifier** on the training data.
   - Evaluated model performance using accuracy, confusion matrix, and classification report.  

3. **Results**:
   - **Model Accuracy**: ~[Insert Accuracy Score]
   - Identified the most important features influencing the predictions.  

4. **Visualization**:
   - Heatmap for feature correlation.
   - Confusion matrix to assess prediction performance.
   - Feature importance chart.  

---

## **Key Results**
1. Achieved a classification accuracy of ~[Insert Accuracy Score].  
2. Identified key factors influencing diabetes prediction (e.g., Glucose, BMI).  
3. Visualizations provided clear insights into the data and model performance.  

---


## **Future Enhancements**
1. Use hyperparameter tuning to optimize the Random Forest Classifier.
2. Compare performance with other classifiers like Logistic Regression, SVM, or XGBoost.
3. Deploy the model using Flask or Streamlit for real-time predictions.  

---


