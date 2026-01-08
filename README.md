Tanvi Sakhale
Machine Learning & Web Development Enthusiast
# Loan Approval Prediction – Machine Learning Project 💳📊

## 📌 Project Overview
The **Loan Approval Prediction System** is a Machine Learning–based application that predicts whether a loan will be **Approved** or **Rejected** based on applicant details.  
The project is deployed using **Streamlit** to provide an interactive and user-friendly interface.

This system helps banks and financial institutions automate loan approval decisions efficiently and accurately.

---

## 🚀 Features
- Predicts loan approval status
- Interactive Streamlit web interface
- Uses trained Machine Learning model
- Real-time prediction results
- Data preprocessing with StandardScaler

---

## 🛠️ Technologies Used
- Python
- Pandas
- NumPy
- Scikit-learn
- Streamlit
- Pickle
- Jupyter Notebook

---

## 📂 Project Structure
```
Loan-Approval-Prediction/
│
├── app.py                          # Streamlit application
├── Loan_Approval_Pred_Model.ipynb  # Model training notebook
├── loan_approval_dataset.csv       # Dataset
├── model.pkl                       # Trained ML model
├── scaler.pkl                      # Scaler for preprocessing
├── README.md                       # Project documentation
```

---

## 📊 Dataset Description
The dataset includes the following features:

| Feature Name | Description |
|-------------|-------------|
| no_of_dependents | Number of dependents |
| education | Education status (Graduated / Not Graduated) |
| self_employed | Self-employed or not |
| income_annum | Annual income |
| loan_amount | Loan amount requested |
| loan_term | Loan duration (years) |
| cibil_score | Credit score |
| Assets | Total assets |
| loan_status | Loan approval status (Target) |

---

## 🧠 Machine Learning Model
- Data preprocessing using **StandardScaler**
- Model trained using **Scikit-learn**
- Trained model saved as `model.pkl`
- Scaler saved as `scaler.pkl`

---

## 🖥️ Streamlit Web Application
The Streamlit app allows users to:
- Enter applicant details
- Click the **Predict** button
- Instantly see loan approval results

---

## ▶️ How to Run the Project

### Step 1: Install Required Libraries
```
pip install pandas numpy scikit-learn streamlit
```

### Step 2: Run the Streamlit App
```
streamlit run app.py
```

### Step 3: Open in Browser
```
http://localhost:8501
```

---

## ✅ Sample Output
- Loan Is Approved
- Loan Is Rejected

---

## 📈 Future Enhancements
- Add more ML models and compare performance
- Improve UI/UX
- Add database integration
- Deploy on cloud platforms

---

## 👩‍💻 Author
**Tanvi Sakhale**  
Machine Learning & Web Development Enthusiast

---

## ⭐ Acknowledgement
This project is developed for educational and learning purposes to understand Machine Learning model building and deployment using Streamlit.
