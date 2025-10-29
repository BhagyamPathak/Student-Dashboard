# 🎓 Student Marks Dashboard

A Flask-based web application that allows users to **upload a CSV file** containing student marks and view it in a clean, interactive dashboard.

Built with ❤️ by students of **Kendriya Vidyalaya RDSO, Lucknow (Class XII PCM)**.

---

## 🚀 Features

- 📂 Upload any `.csv` file directly from your device.
- 📊 View marks data instantly in a responsive dashboard.
- ⚡ Built with Flask + Pandas for fast data handling.
- 💡 Auto-generates visual student records in a clean UI.

---

## 🧠 Tech Stack

- **Frontend:** HTML, Tailwind CSS, Jinja2 (Flask templating)
- **Backend:** Python (Flask)
- **Data Handling:** Pandas
- **Deployment:** Render / PythonAnywhere

---

## 🧩 Folder Structure

student_dashboard/
│
├── app.py # Flask main app
├── requirements.txt # Dependencies
├── templates/
│ ├── upload.html # File upload page
│ └── index.html # Dashboard view
├── static/ # (Optional: CSS, JS, images)
├── uploads/ # Uploaded CSV files
└── README.md

yaml
Copy code

---

## ⚙️ Installation & Running Locally

1. Clone this repository:
   ```bash
   git clone https://github.com/YOUR_USERNAME/student-dashboard.git
   cd student-dashboard
Create a virtual environment:

bash
Copy code
python -m venv venv
source venv/bin/activate  # for macOS/Linux
venv\Scripts\activate     # for Windows
Install dependencies:

bash
Copy code
pip install -r requirements.txt
Run the app:

bash
Copy code
python app.py
Open your browser and visit:

cpp
Copy code
http://127.0.0.1:5000
🌐 Deployment (Render.com)
Create a requirements.txt file:

nginx
Copy code
Flask
pandas
gunicorn
Add a render.yaml file:

yaml
Copy code
services:
  - type: web
    name: student-dashboard
    env: python
    buildCommand: pip install -r requirements.txt
    startCommand: gunicorn app:app
    plan: free
Push to GitHub, then go to Render.com, connect your repo, and deploy 🚀

👨‍🎓 Credits
Team Members (Class XII PCM):
Bhagyam Pathak
Aftab Alam
Hansvi Pandey
Palak Singh

Our Teachers:
Mr. Vishal Srivastava (Physics)
Mr. Anil Gaudh (Chemistry)
Mr. Barbuddin Khan (Mathematics)

School:
📍 Kendriya Vidyalaya RDSO, Lucknow

🖋 License
This project is open-source and free to use for educational purposes.




