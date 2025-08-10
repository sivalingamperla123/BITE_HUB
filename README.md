# 🍽️ BITE HUB

BITE HUB is an online food ordering and restaurant management system built using **Django**.  
It allows customers to browse dishes, place orders, and manage their profiles, while the admin can handle categories, dishes, orders, and team members.

---

## 📌 Features
- User registration & login
- Profile management with profile pictures
- Categories & dishes listing
- Search and filter dishes
- Order placement & order status tracking
- Admin panel for managing all data
- Responsive design with a clean UI

---

## 🛠️ Tech Stack
- **Backend:** Django (Python)
- **Frontend:** HTML, CSS, JavaScript, Bootstrap
- **Database:** SQLite (Default) / Can be switched to PostgreSQL
- **Others:** jQuery, Owl Carousel, Tempus Dominus

---

## 🚀 Installation & Setup

### 1. Clone the repository

```bash
git clone https://github.com/sivalingamperla123/BITE_HUB.git
cd BITE_HUB

Create and Activate Virtual Environment
python -m venv venv
venv\Scripts\activate (for Windows)
source venv/bin/activate (for macOS/Linux)

Install Django
pip install django

Run Migrations
python manage.py makemigrations
python manage.py migrate

Start the Server
python manage.py runserver

Access the App
Visit http://127.0.0.1:8000/ in your browser

🛠 Tech Stack
Backend: Django, Python

Frontend: HTML, CSS, JavaScript, Bootstrap

Database: SQLite (default)

Other: Pillow for image handling

