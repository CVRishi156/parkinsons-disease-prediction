# Parkinson’s Disease Prediction System

This project is a Machine Learning-based application that predicts the likelihood of Parkinson’s disease based on clinical voice parameters. It uses **Python**, **scikit-learn**, and **Streamlit** to provide an interactive web interface.

---

## 🚀 Features

- Accepts 22 clinical voice measurement inputs (e.g., MDVP:Fo(Hz), Jitter, Shimmer, RPDE, DFA, PPE).
- Predicts whether the person is likely to have Parkinson’s disease.
- Built using **Support Vector Machine (SVM)** classifier.
- Provides a simple **Streamlit web interface** for user interaction.

---

---

## ⚙️ Tech Stack

- **Python 3.x**
- **scikit-learn**
- **pandas**, **numpy**
- **Streamlit**
- **pickle**

---

## 📦 Installation & Usage

1. Clone the repository:
   ```bash
   git clone https://github.com/CVRishi156/parkinsons-disease-prediction.git
   
   ```

2. Create a virtual environment & install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Run the Streamlit app:
   ```bash
   streamlit run app.py
   ```

4. Open your browser:
   ```
   http://localhost:8501
   ```

---

## 📊 Dataset

The model was trained using the [UCI Parkinson’s Dataset](https://archive.ics.uci.edu/ml/datasets/parkinsons), which contains biomedical voice measurements.

---

## ✅ For Whom is This Useful?

- **Researchers**: Demonstrates application of ML for early disease detection.
- **Healthcare prototyping**: Example of integrating AI into a simple UI.
- **Students & Learners**: Good reference for end-to-end ML model deployment.
