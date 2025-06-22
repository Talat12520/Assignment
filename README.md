# 🩺 Doctor Time Checker – Flask Web App

This is a simple Flask-based web app that lets you upload a specific login time and returns the list of doctors who logged in at that time. The results can be downloaded as a CSV.

---

## 📁 Project Structure

doctor-time-checker/

├── app.py # Main Flask app

├── doctors_data.xlsx # Original dataset

├── filtered_doctors.csv # (Optional) Pre-filtered file

├── requirements.txt # Python dependencies

├── Procfile # For deployment (Gunicorn)

├── templates/

│ ├── index.html # Input form page

│ └── results.html # Message page for no results

└── static/

└── styles.css # Custom CSS styling


## 🚀 Features

- Upload a time (e.g. 10:30 AM)
- Get list of doctors who logged in at that time
- Download results as CSV
- Styled with custom CSS

---

## 💻 link of website
https://assignment-ytao.onrender.com/


## Demo

![image](https://github.com/user-attachments/assets/25dd10f1-fd5c-4b03-b6d9-55ecf9ea1016)


## 🌐 Deploying to Render

Push your code to GitHub
Go to https://render.com

Click "New Web Service"
Connect your GitHub repo.
Fill the deploy form:
Build Command: pip install -r requirements.txt
Start Command: gunicorn app:app
Environment: Python 3.x
Instance Type: Free
Click Create Web Service

## ⚙️ Notes

The file filtered_doctors.csv is generated dynamically after filtering.
Time format should be entered as HH:MM (e.g., 09:00 or 15:30)





