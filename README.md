this is the beginning of this project
# Network Engineering & Automation Portfolio

A production-ready portfolio web application built to showcase network automation, infrastructure configuration, and systems architecture. Built with **Python (Flask)** and **Vanilla CSS**, designed to bridge the gap between traditional networking and software engineering.

---

## 🛠️ Tech Stack & Architecture

* **Backend:** Python, Flask (Lightweight WSGI web application framework)
* **Frontend:** HTML5, CSS3 (Custom responsive styling)
* **Version Control:** Git & GitHub (CI/CD ready structure)
* **Infrastructure / Deployment:** Linux (Ubuntu VPS), Nginx, Gunicorn, Docker (Planned)

---

## 🚀 Key Features & Roadmap

- [x] **Core Portfolio Framework:** Flask server routing dynamic HTML/CSS templates.
- [ ] **Python Subnet Calculator:** A backend API tool calculating netmasks, wildcard masks, and host ranges.
- [ ] **Configuration Drift Monitor:** Automated script checking device states against a Git "Source of Truth".
- [ ] **NetBox IPAM Integration:** REST API script synchronizing IP address management.

---

## 📂 Project Structure

```text
neteng-portfolio/
│
├── app.py                  # Main Flask application and server routes
├── requirements.txt        # Python dependency manifest
├── .gitignore              # Excludes virtual environments and cache
├── static/
│   └── style.css           # Custom stylesheets and layout definitions
└── templates/
    └── index.html          # Portfolio homepage template