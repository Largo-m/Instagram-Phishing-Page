> [!NOTE]
> **This repository is a fork of [Largo-m/Instagram-Phishing-Page](https://github.com/Largo-m/Instagram-Phishing-Page).**
> Releases, issues, documentation and pull requests live in the upstream repository; use it
> unless you specifically need this copy. Refresh with `git fetch upstream && git merge upstream/main`.

# 🎯 Flask Educational Login Page – Credential Capture Simulation

## ⚠️ Legal Disclaimer

> This project is strictly for **educational and ethical testing purposes only**.  
> It is intended to help developers, penetration testers, and security researchers understand how phishing works so they can protect users from real-world attacks.  
> **Any unauthorized, malicious, or illegal use of this project is strictly prohibited.**  
> The author is not responsible for any misuse or damage caused by this tool.

---

## 📚 About This Project

This is a simple Flask-based web application that simulates a fake login page.  
It accepts user credentials (username and password) and writes them to a local file (`credentials.txt`).  
The primary goal is to raise awareness about phishing risks and help improve defensive strategies through ethical demonstrations.

---

## 🧠 Educational Use Cases

- Security awareness training  
- Ethical hacking demonstrations  
- Capture-the-flag (CTF) exercises  
- Simulated phishing tests in controlled environments  

---

## 📁 Project Structure

- `static/` – Contains static assets like CSS, JS, and images  
- `templates/` – Includes the `index.html` file for the fake login UI  
- `app.py` – Flask backend logic  
- `credentials.txt` – Stores submitted usernames and passwords  
- `requirements.txt` – Python dependencies  
- `README.md` – This file  

---

## 🚀 How to Run

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/educational-login-sim.git
cd educational-login-sim


## 2. Set Up a Virtual Environment (Recommended)

python -m venv venv
source venv/bin/activate

## 3. Install Dependencies
pip install -r requirements.txt


## 4. Start the Flask Server
python app.py


### 🛠 Technologies Used
Python 3

Flask Web Framework

HTML, CSS, JavaScript

JSON APIs

Local text file logging


### 📜 License
This project is licensed under the MIT License – feel free to use, modify, and distribute with attribution.





