# 🏠 Airbnb Superhost Predictor

This project uses machine learning to predict whether an Airbnb host is likely to become a **Superhost** based on listing and host features. Superhosts are experienced, highly rated hosts who are committed to providing great stays for guests.

## 📌 Project Overview

The goal is to build a classification model that can accurately identify potential Superhosts, helping Airbnb and travelers better understand host quality.

We apply data preprocessing, exploratory data analysis, feature engineering, and machine learning techniques to classify hosts.

---

## 🔧 Tools & Technologies

- **Python**
- **Pandas**, **NumPy** – Data manipulation
- **Matplotlib**, **Seaborn** – Data visualization
- **Scikit-learn** – Machine learning (Logistic Regression, Random Forest, Gradient Boosting, etc.)
- **Pickle** – Model serialization

---

## 📊 Features Used

- Host response rate & response time
- Number of listings
- Listing review scores
- Availability & cancellation policy
- Instant booking feature
- Listing amenities & description length
- Location and price


---

## 🔍 Model Training & Evaluation

We tested several machine learning models including:

- Logistic Regression
- Decision Tree
- Random Forest
- Gradient Boosting
- Stacking Ensemble

**Metrics Used:**
- Accuracy
- Precision
- Recall
- F1-score
- ROC-AUC
- Log Loss

---

## 🧠 Best Performing Model

The **Random Forest Classifier** was selected as the best model, achieving a **ROC-AUC score of 0.89** and the lowest **Log Loss**, indicating strong predictive performance and well-calibrated probabilities.

---

## 💡 Future Improvements

- Incorporate NLP on listing descriptions
- Use SHAP for model explainability
- Deploy the model as a web app using Flask or Streamlit
- Train on a larger, more diverse dataset

---

## 🚀 How to Run the Project

1. **Clone the repo**
   ```bash
   git clone [https://github.com/yourusername/airbnb-superhost-predictor.git](https://github.com/yourusername/airbnb-superhost-predictor.git)
   cd airbnb-superhost-predictor
2. **Create a virtual environment** (recommended)
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
3. **Install the required libraries**
   ```bash
   pip install -r requirements.txt
  Run the main notebook or script

4. **Open and run the superhost_prediction.ipynb notebook in Jupyter.**



   
