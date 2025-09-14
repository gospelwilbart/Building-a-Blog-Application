# 📝 Building a Blog Application – Built with Django

## 📖 Overview

This project is a **blogging web application** developed using **Python and the Django framework**. It allows users to create, publish, and manage blog posts with support for comments, categories, and tags. The platform is designed to be **lightweight, extensible, and user-friendly**, making it suitable for personal blogs, small businesses, or content creators.

---

## 🚀 Features

* 🔐 User Registration, Login, and Logout
* ✍️ Create, edit, and delete blog posts
* 🗂 Categorize and tag posts
* 💬 Comment system with moderation
* 🔍 Search and filter blog posts
* 🖼 Upload images for posts
* 📰 Pagination for blog listings
* 🛠 Admin dashboard for managing posts, users, and comments
* 📱 Responsive design for mobile and desktop

---

## 🛠 Tech Stack

| Component      | Technology                                     |
| -------------- | ---------------------------------------------- |
| Backend        | Python, Django                                 |
| Frontend       | HTML, CSS, JavaScript, Bootstrap (or Tailwind) |
| Database       | SQLite / PostgreSQL                            |
| Authentication | Django’s built-in auth                         |
| Media Storage  | Django media files                             |
| Deployment     | Heroku / PythonAnywhere / Render (optional)    |

---

## 🗃 Project Structure

```
blog_application/
│
├── blog/                # Main Django app  
│   ├── models.py        # Database models (Post, Comment, Category, Tag)  
│   ├── views.py         # Business logic  
│   ├── urls.py          # App-level URLs  
│   └── templates/       # HTML templates  
│
├── media/               # Uploaded post images  
├── static/              # Static CSS/JS files  
├── db.sqlite3           # Local database (or PostgreSQL in production)  
├── manage.py  
└── requirements.txt  
```

---

## 🧑‍💻 Getting Started

### Prerequisites

* Python 3.9+
* pip
* Virtualenv (optional but recommended)

### Installation

```bash
# Clone the repo
git clone https://github.com/your-username/blog-application.git
cd blog-application

# Create and activate a virtual environment
python -m venv env
source env/bin/activate   # For Windows: env\Scripts\activate

# Install dependencies
pip install -r requirements.txt

# Apply migrations
python manage.py migrate

# Create superuser
python manage.py createsuperuser

# Run development server
python manage.py runserver
```

Visit `http://127.0.0.1:8000/` in your browser.

---

## 📦 Deployment (Optional)

You can deploy this project on:

* [PythonAnywhere](https://www.pythonanywhere.com/)
* [Render](https://render.com/)
* [Heroku](https://www.heroku.com/)
* [Railway](https://railway.app/)

---

## 📸 Screenshots

*Add screenshots of your blog application once built*

---

## 🤝 Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

---

## 📄 License

This project is open-source and available under the [MIT License](LICENSE).

---

## 👨‍💻 Author

**Elias Mang'era Mwita**
Mbeya University of Science and Technology
Email: [eliasmwita86@gmail.com](mailto:eliasmwita86@gmail.com)