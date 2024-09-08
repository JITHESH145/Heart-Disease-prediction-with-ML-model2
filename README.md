## README File for Heart Disease Prediction Streamlit App

### Introduction
This Streamlit web application is designed to predict the risk of heart disease based on various medical indicators. It utilizes a machine learning model trained on a heart disease dataset to provide a preliminary assessment.

### Dependencies
* **Python:** Ensure you have Python 3.x installed.
* **Streamlit:** Install using `pip install streamlit`.
* **NumPy:** Install using `pip install numpy`.
* **Scikit-learn:** Install using `pip install scikit-learn`.
* **Pickle:** Install using `pip install pickle`.

### Usage
1. **Clone the Repository:**
   ```bash
   git clone <repository_url>
   ```
2. **Install Dependencies:**
   ```bash
   pip install (the dependencies as mentioned above)
   ```
3. **Run the Streamlit App:**
   ```bash
   streamlit run test21.py
   ```
4. **Access the App:** Open your web browser and navigate to the provided URL.

### Input Parameters
The app requires the following input parameters:

* **Age:** The patient's age.
* **Sex:** 1 for male, 0 for female.
* **Chest Pain types:** 1-4, representing different types of chest pain.
* **Resting Blood Pressure:** The patient's resting blood pressure.
* **Serum Cholestoral:** The patient's serum cholesterol level.
* **Fasting Blood Sugar:** 1 if fasting blood sugar is greater than 120 mg/dl, 0 otherwise.
* **Resting Electrocardiographic results:** 0, 1, or 2, representing different ECG results.
* **Maximum Heart Rate achieved:** The patient's maximum heart rate achieved.
* **Exercise Induced Angina:** 1 if exercise induces angina, 0 otherwise.
* **ST depression induced by exercise:** The ST depression induced by exercise.
* **Slope of the peak exercise ST segment:** 1, 2, or 3, representing different slopes.
* **Major vessels colored by flourosopy:** The number of major vessels colored by flourosopy.
* **thal:** 0 for normal, 1 for fixed defect, 2 for reversible defect.

### Output
The app will provide a prediction indicating whether the patient has a high risk of heart disease or not.

### Note
Please note that this is a preliminary prediction based on a machine learning model. It is always recommended to consult with a healthcare professional for a definitive diagnosis.

### Acknowledgments

* Thank you to the contributors of the Streamlit library for creating a user-friendly framework.

**Enjoy using the Heart Disease Prediction app!**
