# flask-login-form
A simple login page built with Flask, Flask-WTF, WTForms validators, and Bootstrap, demonstrating form handling and validation.


Project Structure
flask-login-form/
│
├── app.py
├── README.md
├── requirements.txt
├── .gitignore
│
├── templates/
│   ├── index.html
│   ├── login.html
│   ├── success.html
│   └── denied.html
│
└── static/
    └── css/

📘 README.md (Copy–Paste Ready)
# Flask Login Form 🔐

A simple login page built using **Flask**, **Flask-WTF**, **WTForms**, and **Bootstrap**.  
This project demonstrates form creation, validation, and conditional authentication logic in Flask.

---

## ✨ Features

- Login form with email and password fields
- Form validation using WTForms validators
- Bootstrap-styled UI
- Secure form handling using Flask-WTF
- Conditional login success and failure pages

---

## 🛠️ Tech Stack

- Python
- Flask
- Flask-WTF
- WTForms
- Flask-Bootstrap
- Bootstrap 4

---

## 🚀 How to Run the Application

### 1️⃣ Clone the repository
```bash
git clone https://github.com/your-username/flask-login-form.git

2️⃣ Navigate into the project directory
cd flask-login-form

3️⃣ Install dependencies
pip install -r requirements.txt

4️⃣ Run the app
python app.py

5️⃣ Open in browser
http://127.0.0.1:5000/login

🔐 Login Logic

Validates user input using DataRequired

Compares entered credentials with predefined values

Redirects to:

success.html on correct credentials

denied.html on incorrect credentials

⚠️ This is a demo project and does not implement real authentication or encryption.

📚 What I Learned

Creating forms using Flask-WTF

Using WTForms fields and validators

Handling POST and GET requests

Bootstrap integration with Flask

Basic authentication logic


Add flash messages

Improve UI/UX
