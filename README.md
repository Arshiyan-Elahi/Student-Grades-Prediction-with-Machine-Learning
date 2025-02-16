# 🚀 Student Grades Prediction - Machine Learning Project

## 📌 Project Overview
This project predicts student grades using machine learning techniques based on various features such as study time, past grades, failures, and absences. The dataset is trained using a **Linear Regression model** to predict final grades (G3).

### **Key Features:**
✅ **Dataset Processing:** Cleans and preprocesses student data.
✅ **Machine Learning Model:** Uses Linear Regression for grade prediction.
✅ **Feature Importance Analysis:** Identifies the most influential factors.
✅ **Data Visualization:** Various graphs to understand trends and performance.
✅ **Colab & GitHub Integration:** Runs smoothly in Google Colab and auto-uploads results to GitHub.

---

## 📂 Folder Structure
```
📦 Student-Grades-Prediction
├── data/  # Dataset Files
│   ├── student-mat.csv  # Student performance dataset
├── notebooks/  # Jupyter Notebooks for analysis and model training
│   ├── student_grades_prediction.ipynb
├── images/  # Visualizations and model output
│   ├── actual_vs_predicted.png  # Scatter plot of actual vs predicted grades
│   ├── feature_importance.png  # Importance of features
│   ├── grade_distribution.png  # Histogram of final grades (G3)
├── models/  # Trained machine learning models
│   ├── grades_prediction_model.pkl
├── README.md  # This file
```

---

## 🔧 How It Works
### **Step 1: Load Dataset**
- The dataset (`student-mat.csv`) contains student performance data.
- Features include **G1, G2 (previous grades), study time, failures, absences, and more**.
- The target variable is **G3 (Final Grade)**.

### **Step 2: Train Machine Learning Model**
- Uses **Linear Regression** to predict G3 based on input features.
- Model is trained using `train_test_split` with an 80-20 ratio.
- Performance is evaluated using **R² Score and Mean Absolute Error (MAE)**.

### **Step 3: Generate Predictions & Visualizations**
- The model predicts **G3** based on student data.
- **Graphs** like scatter plots, feature importance, and grade distribution are generated.

---

## 🚀 Running the Project
### **Using Google Colab**
1. Open `student_grades_prediction.ipynb` in **Google Colab**.
2. Run all cells to preprocess the data, train the model, and generate predictions.
3. Check the generated images in the `images/` folder.

### **Locally on Your System**
1. Clone the repository:
   ```sh
   git clone https://github.com/YOUR_USERNAME/Student-Grades-Prediction.git
   ```
2. Install dependencies:
   ```sh
   pip install -r requirements.txt
   ```
3. Run the notebook or script to generate predictions.

---

## 📊 Data Visualization
Several charts are used to analyze data trends and model performance:
- **Scatter Plot**: Relationship between `G1` and `G3` (First Exam vs Final Grade)
- **Feature Importance (Bar Chart)**: Identifies key factors affecting final grades.
- **Line Chart**: Trends of `G1`, `G2`, and `G3` over time.
- **Histogram**: Distribution of `G3` scores.
- **Box Plot**: Study Time vs Final Grades.

---

## 🛠️ Future Enhancements
- Improve accuracy using **Decision Trees / Random Forest**.
- Develop a **Web App** for student grade prediction.
- Implement **Real-Time Data Analysis**.

---

## 📜 License
This project is open-source under the **MIT License**.

---

🚀 **Built for Accurate Student Grade Predictions!** 🎯

