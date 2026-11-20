# 🤖 AI Tracker

A web application for tracking AI models, their architectures, and performance metrics. Built with Django as a portfolio project.

<img width="1917" height="943" alt="dashboard" src="https://github.com/user-attachments/assets/6dcea816-50f1-49ac-82ee-3d38bcb1fecb" />

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
<img width="1917" height="943" alt="dashboard" src="https://github.com/user-attachments/assets/6dcea816-50f1-49ac-82ee-3d38bcb1fecb" />

### Model List
<img width="1917" height="947" alt="train-models-list" src="https://github.com/user-attachments/assets/eebe8ebe-6c36-4508-86bb-ddabb53496d6" />

### Model Detail

<img width="1917" height="947" alt="train-model-detail" src="https://github.com/user-attachments/assets/b6386b4d-f7cc-4729-a18b-bfae98652916" />

### Register
<img width="1917" height="943" alt="register" src="https://github.com/user-attachments/assets/41a2b1ec-da20-4dc0-b8a5-cd927e498eeb" />

### Login
<img width="1917" height="943" alt="login" src="https://github.com/user-attachments/assets/01bcf887-b91b-44c7-861d-73923d6544a8" />

### Contact us
<img width="1907" height="948" alt="contact-us" src="https://github.com/user-attachments/assets/0c6b3fcd-19bb-4853-a437-05d2bab6e98e" />

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
