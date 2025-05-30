# Vote Drishti — Election Data Analysis & Prediction

**Vote Drishti** is a machine learning-based election prediction app that compares two candidates in a constituency using features like party, gender, education, criminal records, and assets. It predicts the likely winner using trained models based on the **Maharashtra Assembly Election 2019** data.

---

## 📁 Project Structure
ELECTION-DATA-ANALYSIS/
│
├── model/ # Trained ML models (.joblib, .pkl)
├── static/ # Static files (CSS, JS, images)
├── templates/ # HTML templates (Flask frontend)
├── train/ # Training scripts and notebooks
│
├── app.py # Flask web app entry point
├── predict.py # Prediction logic using trained model
├── preprocessed_X_test.csv # Preprocessed test features
├── preprocessed_y_test.csv # Preprocessed test labels
├── requirements.txt # Python dependencies
└── README.md # This file

---

## 🎯 Project Objective

- Predicts the winner between two election candidates  
- Uses real candidate and constituency-level features  
- Provides a Flask-based frontend for interactive prediction  

---

## 🔍 Features Used for Prediction

- **STATE**  
- **PARTY**  
- **GENDER**  
- **CRIMINALCASES**  
- **AGE**  
- **CATEGORY**  
- **EDUCATION**  
- **ASSETS**  
- **LIABILITIES**  
- **TOTAL ELECTORS**

### 🔠 Categorical Features:
- STATE, PARTY, GENDER, CATEGORY, EDUCATION

### 🔢 Numerical Features:
- CRIMINALCASES, AGE, ASSETS, LIABILITIES, TOTAL ELECTORS

---

## 🚀 Getting Started

### Step 1: Clone the repository
```bash
git clone https://github.com/your-username/ELECTION-DATA-ANALYSIS.git
cd ELECTION-DATA-ANALYSIS

### Step 1: Clone the repository

```bash
pip install -r requirements.txt
python app.py
🤖 Model Information
Trained using Logistic Regression

Compares feature differences between two candidates

Outputs probability that Candidate A will win

Trained model is saved in the model/ directory

🔮 Predict Programmatically
python
Copy
Edit
from predict import predict_winner  
result = predict_winner(candidate_a, candidate_b)
🚧 Future Enhancements
Add support for XGBoost and LightGBM

Add SHAP-based explainability

Multi-candidate prediction

Cloud deployment (Heroku, Render, etc.)

🖼️ Screenshots
(You can include images or screenshots of the UI here)

🤝 Contributing
Pull requests are welcome! To contribute:

Fork the repo

Create a new branch:

bash
Copy
Edit
git checkout -b feature/your-feature-name
Commit your changes:

bash
Copy
Edit
git commit -m "Your message"
Push to the branch:

bash
Copy
Edit
git push origin feature/your-feature-name
Open a pull request

📄 License
This project is licensed under the MIT License. See the LICENSE file for more details.

📬 Contact
Email: vasawadeayush@gmail.com

GitHub: https://github.com/ayushvasawade/ELECTION-DATA-ANALYSIS
