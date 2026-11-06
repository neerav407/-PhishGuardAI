# 🛡️ PhishGuard AI
### AI-Powered Phishing Website Detection Using Machine Learning

PhishGuard AI is a machine-learning-based phishing detection system designed to identify potentially malicious websites and URLs. It uses trained ML models to analyze website characteristics and URL-based features to classify websites as **Phishing** or **Legitimate**.

The project provides an interactive web interface built with Streamlit, allowing users to explore datasets, compare machine learning models, test website features, and analyze URLs.

---

## 🚀 Features

- **Phishing Website Detection:** Classifies websites as phishing or legitimate using machine learning.
- **URL Phishing Detector:** Analyzes URL characteristics to identify potentially suspicious links.
- **Multiple ML Models:** Supports Decision Tree, Random Forest, Logistic Regression, SVM, K-Nearest Neighbors, and Gradient Boosting.
- **Model Comparison:** Compares model performance using Accuracy, Precision, Recall, F1-Score, and ROC-AUC.
- **Performance Visualization:** Displays model comparison charts, confusion matrices, feature importance, and ROC curves.
- **Interactive Dashboard:** Easy-to-use Streamlit interface with multiple sections.
- **Prediction Probabilities:** Displays estimated phishing and legitimate probabilities when available.

---

## 🧠 Machine Learning Algorithms

The project includes the following algorithms:

| Algorithm | Purpose |
|---|---|
| Decision Tree | Classification |
| Random Forest | Classification |
| Logistic Regression | Classification |
| Support Vector Machine (SVM) | Classification |
| K-Nearest Neighbors (KNN) | Classification |
| Gradient Boosting | Classification |

---

## 🛠️ Technologies Used

- **Programming Language:** Python
- **Frontend / Dashboard:** Streamlit
- **Machine Learning:** Scikit-learn
- **Data Processing:** Pandas, NumPy
- **Data Visualization:** Matplotlib, Seaborn
- **Model Storage:** Joblib
- **Explainable AI:** SHAP

---

## 📂 Project Structure

```text
PhishGuardAI/
│
├── app.py
├── requirements.txt
├── README.md
│
├── data/
│   ├── raw/
│   └── processed/
│
├── models/
│   └── Trained ML Models
│
├── pages/
│
├── results/
│   ├── Model Comparison
│   ├── Confusion Matrices
│   ├── Feature Importance
│   └── ROC Curves
│
├── src/
│   ├── advanced_evaluation.py
│   ├── feature_extractor.py
│   ├── inspect_data.py
│   ├── predictor.py
│   ├── prepare_data.py
│   ├── train_models.py
│   ├── url_feature_extractor.py
│   ├── url_predictor.py
│   ├── prepare_url_dataset.py
│   └── train_url_model.py
│
└── tests/
```

---

## ⚙️ Installation and Setup

### Step 1: Clone the Repository

```bash
git clone https://github.com/neerav407/-PhishGuardAI.git
```

### Step 2: Navigate to the Project Folder

```bash
cd PhishGuardAI/PhishGuardAI - Copy
```

### Step 3: Create a Virtual Environment

```bash
python -m venv .venv
```

### Step 4: Activate the Virtual Environment

For Windows:

```bash
.venv\Scripts\activate
```

### Step 5: Install Dependencies

```bash
pip install -r requirements.txt
```

### Step 6: Run the Application

```bash
streamlit run app.py
```

The application will open in your browser, usually at:

```text
http://localhost:8501
```

---

## 📊 Application Modules

### 1. Overview
Displays dataset information, phishing and legitimate website records, and the overall project workflow.

### 2. Model Comparison
Compares different machine learning algorithms using performance metrics and visualizations.

### 3. Test a Prediction
Allows users to select website feature values and test them using trained machine learning models.

### 4. URL Phishing Detector
Allows users to enter a website URL and receive a machine-learning-based prediction with URL indicators and estimated probabilities.

---

## 🔄 Project Workflow

```text
Dataset Collection
       ↓
Data Preprocessing
       ↓
Feature Extraction
       ↓
Model Training
       ↓
Model Evaluation
       ↓
Model Comparison
       ↓
Streamlit Dashboard
       ↓
Phishing Detection
```

---

## ⚠️ Disclaimer

PhishGuard AI is an educational machine learning project. Its predictions are estimates and do not guarantee that a website is safe or malicious.

The URL detector performs offline URL-feature analysis. It does not automatically visit websites, inspect webpage content, follow redirects, or verify live website reputation.

Always follow safe browsing practices and never enter sensitive information based only on an ML prediction.

---

## 👨‍💻 Developer

**Neerav Parikh**

GitHub: [@neerav407](https://github.com/neerav407)

Project: [PhishGuardAI](https://github.com/neerav407/-PhishGuardAI)

---

⭐ If you find this project interesting, consider giving the repository a star!

**PhishGuard AI – Smarter Detection, Safer Browsing.** 🛡️