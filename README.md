# ML--MBA-Admission-Prediction

This project uses machine learning to predict MBA admission status based on various applicant metrics such as GMAT scores, work experience, and GPA. It is implemented using Python and Jupyter Notebook, applying data preprocessing, visualization, and classification techniques.

---

## 🔍 Project Overview

This notebook explores and analyzes an MBA admission dataset, ultimately building a classification model to predict whether a candidate is likely to be admitted.

### Key Steps:
- Data cleaning and preprocessing
- Exploratory Data Analysis (EDA)
- Feature engineering
- Building and evaluating classification models
- Visualizing performance with confusion matrix and ROC curve

---

## 📌 Insights & Highlights

- **Data Preprocessing:** 
  - Handled missing values and removed irrelevant columns like `Serial No`.
  - Converted the categorical `Gender` variable into numerical format.

- **Exploratory Analysis:**
  - Visualized distributions of `GMAT`, `GPA`, and `Work Experience`.
  - Compared features across `Admission_Status`.

- **Feature Engineering:**
  - Created dummy variables for gender.
  - Normalized numeric features.

- **Modeling:**
  - Used **Logistic Regression** to build the prediction model.
  - Evaluated the model using **accuracy**, **precision**, **recall**, **F1-score**, and **ROC-AUC**.

- **Performance:**
  - The model shows good discrimination ability, as reflected in ROC-AUC.
  - Confusion matrix and classification report help assess practical utility.

---

## 🛠️ Tech Stack

- Python 🐍
- Jupyter Notebook 📒
- Pandas, NumPy
- Seaborn, Matplotlib
- Scikit-learn

---

## 📁 Files

- `MBA_Admission_Status.ipynb`: Main notebook containing all code, analysis, and visualizations.
- Dataset (not included): Ensure your dataset is correctly named and structured as expected in the notebook.

---

## 🚀 Getting Started

### 1. Clone the repo
```bash
git clone https://github.com/yourusername/MBA-Admission-Prediction.git
cd MBA-Admission-Prediction
```

### 2. Install dependencies
Create a virtual environment (optional but recommended):
```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

Install required packages:
```bash
pip install -r requirements.txt
```

### 3. Run the Notebook
```bash
jupyter notebook MBA_Admission_Status.ipynb
```

---

## 📈 Future Improvements

- Try advanced classification models (e.g., Random Forest, XGBoost)
- Perform hyperparameter tuning
- Add more features (e.g., Statement of Purpose score, Interview rating)
- Convert to a web app using Streamlit or Flask

---

## 📬 Contact

For feedback or collaboration, feel free to reach out via [GitHub Issues](https://github.com/thatboypage/ML-MBA-Admission-Prediction/issues).
