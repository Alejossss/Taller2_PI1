# 🎬 Movie Reviews

A Django + Bootstrap web application to explore, search and review movies.  
Users can browse a catalog, search by title, view details such as description, year and genre, and even check simple statistics.

---

## ✨ Features

- 🔍 **Movie search** with dynamic filtering by title/description.  
- 🖼️ **Movie cards** with consistent poster sizing.  
- 📰 **News page** with demo articles (animal-related, for practice).  
- ℹ️ **About page** describing the project and stack.  
- 📊 **Statistics page** with matplotlib charts:
  - Movies per year.
  - Movies per first genre.  
- 📧 **Mailing list sign-up** with email capture.  
- 🎨 Modern responsive UI using **Bootstrap 5** and custom styling.

---

## 🚀 Tech Stack

- **Backend:** Django (Python)
- **Frontend:** HTML, Bootstrap 5, Bootstrap Icons
- **Database:** SQLite (development)
- **Charts:** Matplotlib
- **Other:** Pillow (for images), Django template system

---

## ⚙️ Installation

Clone the repo and set up the environment:

```bash
git clone https://github.com/Alejossss/Taller2_PI1.git
cd moviereviewsproject

# Create virtual environment
python -m venv venv
# On Linux/MacOs: source venv/bin/activate    
# On Windows: venv\Scripts\activate

# Install dependencies
pip install -r requirements.txt

# Run migrations
python manage.py migrate

# Start development server
python manage.py runserver
