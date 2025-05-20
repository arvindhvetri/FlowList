# 🌊 FlowList — Your Elegant To-Do Companion

FlowList is a minimalist, beautifully-crafted to-do list web application built with **Flask**, **MySQL**, **HTML**, and **CSS**. Designed with clean aesthetics and seamless user experience in mind, FlowList helps you stay organized, focused, and productive.

![Flask](https://img.shields.io/badge/Flask-000000?style=for-the-badge&logo=flask&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-005C84?style=for-the-badge&logo=mysql&logoColor=white)
![HTML](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)

---

## ✨ Features

- ✅ **Add / Edit / Delete Tasks** — Stay in control of your day.
- 📌 **Mark as Completed** — Visual satisfaction with a click.
- 🕶️ **Beautiful UI/UX** — Clean, minimal, and distraction-free interface.
- 📁 **Persistent Storage** — Backed by MySQL to save your tasks.

---

## 🖼️ Preview

![Preview](https://github.com/user-attachments/assets/86f1587f-b62f-45f3-91dc-d4b21ada8b0c)

  
<sub>*A glimpse into the clean interface of FlowList*</sub>

---

## 🛠️ Tech Stack

| Technology | Description                    |
|------------|--------------------------------|
| Flask      | Lightweight Python web framework |
| MySQL      | Relational database management |
| HTML/CSS   | Structure and styling          |
| Jinja2     | Templating engine for Flask    |

---

## 🚀 Getting Started

### 1. Clone the Repository
```bash
git clone https://github.com/yourusername/flowlist.git
cd flowlist
```

### 2. Set Up Virtual Environment
```bash
# On Windows:
py -3 -m venv .venv
.venv\Scripts\activate  
```

### 3. Install Dependencies
```bash
pip install -r requirements.txt 
```

### 4. Configure Database
- Create a MySQL database named `tododb`.
- Create a Table named `tasks`.

### 5. Configure .env
```bash
mkdir config
sudo nano db.env

# Replace the values and save it.
DB_HOST=localhost
DB_USER=root
DB_PASSWORD=<password>
DB_NAME=tododb
```

### 6. Run the App
```bash
python app.py
```
Visit http://127.0.0.1:5000 in your browser.

---

## 🚀 Output
[FlowList Output.pdf](https://github.com/user-attachments/files/20358018/FlowList.Output.pdf)

