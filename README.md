# 🤖 AI Tracker

A web application for tracking AI models, their architectures, and performance metrics. Built with Django as a portfolio project.

![Dashboard Screenshot](screenshots/dashboard.png)

---

## 📋 Features

- **AI Model Management** — add, edit, and delete AI models with version tracking
- **Performance Metrics** — log accuracy and loss scores for each model over time
- **Architecture Tracking** — organize models by their neural network architecture
- **Researcher Profiles** — each model is linked to its author
- **Search** — search models, researchers, and architectures by name
- **User Authentication** — register, login, and logout
- **Contact Form** — built-in contact page

---

## 🖥️ Screenshots

### Dashboard
![Dashboard](screenshots/dashboard.png)

### Model List
![Model List](screenshots/model_list.png)

### Model Detail
![Model Detail](screenshots/model_detail.png)

---

## 🛠️ Tech Stack

- **Backend:** Python 3, Django
- **Frontend:** Bootstrap 5, crispy-forms
- **Database:** SQLite
- **Auth:** Django built-in authentication + custom `Researcher` user model

---

## 🚀 Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/kacper7-7/ai-tracker.git
cd ai-tracker
```

### 2. Create a virtual environment

```bash
python -m venv venv
source venv/bin/activate        # Linux / macOS
venv\Scripts\activate           # Windows
```

### 3. Install dependencies

```bash
pip install -r requirements.txt
```

### 4. Apply migrations

```bash
python manage.py migrate
```

### 5. Create a superuser (optional)

```bash
python manage.py createsuperuser
```

### 6. Run the development server

```bash
python manage.py runserver
```

Open your browser and go to `http://127.0.0.1:8000/`

---

## 📁 Project Structure

```
ai_tracker/
├── core/                   # Main application
│   ├── models.py           # Researcher, TrainModel, Architecture, PerformanceMetric
│   ├── views.py            # Class-based and function-based views
│   ├── forms.py            # Forms for metrics, contact, registration
│   ├── urls.py             # App URL patterns
│   └── templates/core/     # HTML templates
├── ai_tracker/
│   ├── settings.py
│   └── urls.py             # Root URL config
├── requirements.txt
└── manage.py
```

---

## 👤 Author

Made by **Kacper Kogut** — [github.com/kogutkacper7](https://github.com/kogutkacper7)
