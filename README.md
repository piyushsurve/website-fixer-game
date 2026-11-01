# Website Fixer – Interactive CSS Coding Game

An interactive web-based CSS debugging game developed using Django. It challenges users to identify and fix CSS styling issues in a pre-built website through hands-on coding challenges.

## 🚀 Live Demo

https://website-fixer-game.onrender.com/

## 📌 About the Project

Website Fixer is an educational coding game designed to help users improve their CSS skills by solving real-world styling challenges.

Users are provided with a website containing CSS issues and must write or modify CSS rules to achieve the expected design. The platform provides an interactive coding environment with a live website preview.

## ✨ Features

- **Interactive CSS Challenges:** Solve different CSS styling problems.
- **Live Website Preview:** See changes while working on CSS challenges.
- **Timed Challenges:** Complete challenges within a given time.
- **CSS Objectives:** Understand the styling requirements for each challenge.
- **Progress Tracking:** Track coding progress and completed challenges.
- **Solution Management:** Save and retrieve submitted CSS solutions.
- **Responsive Interface:** Access the game through a user-friendly web interface.

## 🛠️ Technologies Used

- **Backend:** Python, Django
- **Frontend:** HTML5, CSS3, JavaScript
- **Database:** Django-configured database
- **Tools:** Git, GitHub, VS Code
- **Deployment:** Render

## 📂 Project Structure

```text
Website-Fixer/
│
├── games/
│   ├── settings.py
│   ├── urls.py
│   ├── views.py
│   └── wsgi.py
│
├── templates/
├── static/
├── manage.py
├── requirements.txt
└── README.md
```

*Note: The structure above is illustrative. Your actual folders may differ.*

## ⚙️ Installation and Setup

### 1. Clone the Repository

```bash
git clone https://github.com/piyushsurve/website-fixer-game.git
```

### 2. Navigate to the Project Folder

```bash
cd website-fixer-game
```

### 3. Create a Virtual Environment

```bash
python -m venv venv
```

### 4. Activate the Virtual Environment

**Windows:**

```bash
venv\Scripts\activate
```

### 5. Install Dependencies

```bash
pip install -r requirements.txt
```

### 6. Apply Database Migrations

```bash
python manage.py migrate
```

### 7. Run the Development Server

```bash
python manage.py runserver
```

Open your browser and visit:

```text
http://127.0.0.1:8000/
```

## 🎯 Project Objective

The main objective of Website Fixer is to make learning CSS more interactive and practical. Instead of only studying CSS concepts, users can improve their styling and debugging skills by solving hands-on challenges.

## 👨‍💻 Developer

**Piyush Surve**

- GitHub: https://github.com/piyushsurve
- LinkedIn: https://www.linkedin.com/in/piyush-surve/

## 📄 License

This project is developed for educational and learning purposes.
