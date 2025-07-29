<h1 align="center">🤖 Jarvis - AI Virtual Assistant</h1>

<p align="center">
  <img src="https://img.shields.io/github/languages/top/Ayush-Goel20/Jarvis?style=for-the-badge" />
  <img src="https://img.shields.io/github/license/Ayush-Goel20/Jarvis?style=for-the-badge" />
  <img src="https://img.shields.io/github/repo-size/Ayush-Goel20/Jarvis?style=for-the-badge" />
  <img src="https://img.shields.io/badge/PRs-Welcome-green?style=for-the-badge" />
</p>

<p align="center">
  A futuristic AI-powered voice assistant with face recognition, smart command execution, and a sleek frontend.
</p>

---
## 🖼️ Screenshots
![Jarvis](./frontend/assets/img/jarvis.jpg)

---

## 🧠 Overview

> Jarvis is your AI-powered virtual assistant that understands your **voice**, recognizes your **face**, and performs tasks like a pro. Built using Python, OpenCV, and custom logic, Jarvis is more than a script — it's an experience.

---

## ✨ Key Features

- 🎤 **Voice Command Interface**
- 👁️ **Face Detection & Recognition** (Haar Cascades)
- 📂 **Modular Backend** (commands, auth, DB, etc.)
- 🎨 **Beautiful Web UI** (HTML, CSS, JS)
- 🔐 **User Authentication Layer**
- ⚡ **Fast & Lightweight**

---

## 🛠 Tech Stack

| Layer     | Tech Used                          |
|-----------|------------------------------------|
| Backend   | `Python`, `OpenCV`, `SQLite`       |
| Frontend  | `HTML`, `CSS`, `JavaScript`        |
| UI Assets | `Texllate`, `Animate.css`, `jQuery`|
| Tools     | `Git`, `VS Code`, `GitHub`         |

---

<details>
<summary>##📁 <b>Project Structure</b></summary>

<br>

```bash
├── __pycache__/                          # Compiled Python files
│   └── main.cpython-*.pyc
│
├── backend/                              # Backend logic and services
│   ├── auth/                             # Face recognition module
│   │   ├── samples/                      # Sample images for training
│   │   ├── trainer/                      # Trained face data
│   │   │   └── trainer.yml
│   │   ├── haarcascade_frontalface_default.xml  # Face detection model
│   │   ├── recognize.py                  # Face recognition logic
│   │   ├── sample.py                     # Image capture script
│   │   └── trainer.py                    # Training script
│   │
│   ├── command.py                        # Voice command processing
│   ├── config.py                         # Configuration file
│   ├── cookie.json                       # Session or cookie storage
│   ├── db.py                             # Database (e.g., SQLite) operations
│   ├── feature.py                        # Feature extraction or analysis
│   └── helper.py                         # Common utility functions
│
├── env.jarvis/                           # Python virtual environment (ignored)
│
├── frontend/                             # Web frontend files
│   ├── assets/
│   │   ├── audio/                        # Audio feedback files
│   │   ├── img/                          # Image assets for UI
│   │   └── vendor/
│   │       └── texllate/
│   │           ├── animate.css
│   │           ├── jquery.fittext.js
│   │           ├── jquery.lettering.js
│   │           └── style.css
│   │
│   ├── controller.js                     # JS controller for UI logic
│   ├── index.html                        # UI entry page
│   ├── main.js                           # Main logic script
│   ├── script.js                         # Additional scripts
│   └── style.css                         # Frontend styles
│
├── run.py                                # Main launcher script
├── .gitignore                            # Files/folders ignored by Git
└── README.md                             # Project documentation
</details>
---

## 🚀 Getting Started

### 🔧 Requirements

- Python 3.8+
- OpenCV
- PyAudio
- Flask

### 🧪 Setup Instructions

```bash
# 1. Clone the Repository
git clone https://github.com/Ayush-Goel20/Jarvis.git
cd Jarvis

# 2. Install Dependencies
pip install -r requirements.txt

# 3. Run the Assistant
python run.py
