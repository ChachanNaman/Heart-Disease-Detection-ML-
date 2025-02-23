# ❤️ Heart Disease Prediction

## 📌 Project Overview
This project aims to predict the likelihood of heart disease based on various health parameters. Using **Logistic Regression**, we analyze patient data and determine whether an individual is at risk (*1 - Heart Disease*) or healthy (*0 - No Heart Disease*).

## 📂 Dataset
- The dataset used is **heart_disease_data.csv**.
- It contains various medical parameters such as age, cholesterol levels, blood pressure, etc.
- The **14th column (Target variable)** indicates:
  - `1` → Heart Disease
  - `0` → Healthy

## 🔥 Technologies Used
- Python 🐍
- Pandas 📊
- NumPy 🔢
- Scikit-learn 🤖
- Matplotlib 📉
- Seaborn 🎨
- Jupyter Notebook 📒

## 📊 Model & Approach
1. **Data Preprocessing:**
   - Handled missing values
   - Standardized numerical features
   - Encoded categorical variables
2. **Exploratory Data Analysis (EDA):**
   - Visualized data distributions
   - Identified correlations
3. **Machine Learning Model:**
   - Trained a **Logistic Regression** model
   - Evaluated performance using **accuracy, precision, recall, and F1-score**

## 🚀 Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/heart-disease-prediction.git
   ```
2. Navigate to the project folder:
   ```bash
   cd heart-disease-prediction
   ```
3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
4. Run the Jupyter Notebook:
   ```bash
   jupyter notebook
   ```

## 📌 Results
- Achieved **high accuracy** in detecting heart disease.
- The model helps in **early diagnosis** and risk assessment.
- Visualizations provided insights into key health parameters affecting heart disease.

## 📌 Example Prediction
```python

patient_data = np.array([[63, 1, 3, 145, 233, 1, 0, 150, 0, 2.3, 0, 0, 1]])


prediction = model.predict(patient_data)
print("Heart Disease" if prediction == 1 else "Healthy")
```

## 🎯 Future Enhancements
- Implementing **Deep Learning models** for better accuracy
- Creating a **web app** for easy accessibility
- Exploring **other ML algorithms** for comparison

## 👏 Contributing
Contributions are welcome! Feel free to fork the repo, make improvements, and submit a PR. 😊

## 🏆 Acknowledgments
- Inspired by **UCI Heart Disease Dataset**
- Thanks to the **open-source ML community** ❤️

AUTHOR - NAMAN CHACHAN
EMAIL - chachannaman@gmail.com
