# SLR_Model_Salary_prediction


#  Salary Prediction using Simple Linear Regression  

![Machine Learning](https://img.shields.io/badge/ML-Linear%20Regression-blueviolet?style=for-the-badge)
![Python](https://img.shields.io/badge/Python-3.8+-yellow?style=for-the-badge)
![Flask](https://img.shields.io/badge/Framework-Flask-red?style=for-the-badge)
![Status](https://img.shields.io/badge/Status-Deployed-success?style=for-the-badge)

A simple yet powerful **Machine Learning Web Application** that predicts an employee's **Salary based on Years of Experience** using **Simple Linear Regression (SLR)**.  
This project demonstrates **Data preprocessing, Model training, Serialization, and Flask-based deployment**.

---

##  Live Demo  
🔗 **Application Link:** (https://slr-model-salary-prediction-1.onrender.com)

---

##  Project Overview  

This project uses a **Supervised Machine Learning Algorithm** called **Simple Linear Regression** to analyze the relationship between **Years of Experience** and **Salary**.  

The model was trained on a dataset of real-world employee salary data and deployed using **Flask** and hosted publicly.

---

##  Features  
- Clean and user-friendly UI  
- Enter experience and get predicted salary instantly  
- Model trained using `scikit-learn`  
- Model serialized using `pickle`  
- Fully deployed on **Render**  
- Easy to understand & beginner-friendly project  

---

##  Tech Stack  

| Component | Technology |
|----------|------------|
| Programming Language | Python |
| ML Library | scikit-learn |
| Backend Framework | Flask |
| Frontend | HTML, CSS, Bootstrap |
| Model Storage | Pickle (`.pkl`) |
| Deployment | Render |

---

##  Folder Structure  

SLR_Model_Salary_Prediction/
│-- app.py # Flask application
│-- SLR.pkl # Trained ML model
│-- requirements.txt # Dependencies list
│-- Procfile # For deployment
│-- templates/
│ └── index.html # Frontend UI
│-- static/
└── css/style.css # Styling (if available)

yaml
Copy code

---

##  Model Working Flow  

| Step | Description |
|------|-------------|
| 1️) Load dataset | Contains years of experience vs salary |
| 2️) Data preprocessing | Cleaning and formatting |
| 3️) Train Model | Simple Linear Regression |
| 4️) Save Model | Using pickle to create `SLR.pkl` |
| 5️) Deploy Model | Flask backend + HTML UI |
| 6️) User Input | User enters experience |
| 7️) Output | Predicted salary displayed |

---

##  Web UI Preview  

| Input Years of Experience | Click Predict | Output Shows Estimated Salary |
|---|---|---|
| ![](https://dummyimage.com/300x100/000/fff&text=Enter+Experience) | → | ![](https://dummyimage.com/300x100/007bff/fff&text=Predicted+Salary) |

> *(Replace with actual screenshots later if you want)*

---

##  Run Locally  

Clone the repo:

> git clone https://github.com/karthik-vana/SLR_Model_Salary_prediction.git
cd SLR_Model_Salary_prediction

> Install dependencies:

> pip install -r requirements.txt
 
> Run the application:

> python app.py
 
> Open in browser:(http://127.0.0.1:5000)


#  Dataset Visualization Example

> The regression line between Experience & Salary looks like:

- Salary = m * Experience + c
Where

- m = slope

- c = intercept

This shows how salary increases with experience.

#  Future Enhancements

🔹 Multiple Linear Regression using more features

🔹 Deploy with Streamlit UI

🔹 Add charts and interactive analytics

🔹 Convert to API for mobile usage

 # Project Developed By

 ## ` Karthik Vana`
 ### ` Data Analyst | ML Engineer | Data Engineer`
 

> For more Enquery
 
🔗 GitHub: (https://github.com/karthik-vana)
 
🔗 LinkedIn: (https://www.linkedin.com/in/karthik-vana/)


---






