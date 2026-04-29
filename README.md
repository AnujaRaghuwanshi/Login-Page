# Phishing Simulation Web App (Security Awareness Demo)

## 📌 Overview
This project is a simple Flask-based web application designed for **security awareness training and red team simulations**.  
It demonstrates how phishing pages can be structured and how easily user credentials can be submitted if proper caution is not exercised.

> ⚠️ **Important:** This project is strictly for **educational and authorized security testing purposes only**. It must never be used to collect real user credentials or deployed in any unauthorized environment.

---

## 🎯 Objective
The goal of this project is to:
- Demonstrate common phishing page behavior
- Raise awareness about credential theft risks
- Support cybersecurity training and red teaming exercises
- Help users understand the importance of secure credential handling

---

## 🛠️ Tech Stack
- Python 3
- Flask (Backend Framework)
- HTML (Frontend Templates)

---

## ⚙️ How It Works
1. The user lands on a login page (`/`)
2. The user submits a form with credentials
3. The backend captures the submitted data (for simulation purposes only)
4. A warning page is displayed indicating a phishing simulation

---

## 🚀 Setup & Installation

### 1. Clone the repository
```bash
git clone <your-repo-url>
cd <repo-folder>
2. Install dependencies
pip install flask
3. Run the application
python app.py
4. Open in browser
http://127.0.0.1:5000/
📁 Project Structure
├── app.py
├── templates/
│   └── index.html
├── credentials.txt   (generated during runtime - simulation only)
└── README.md





