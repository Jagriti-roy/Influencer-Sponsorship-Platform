# Influencer-Sponsorship-Platform

A full-stack web application designed to connect influencers and sponsors for collaborative marketing campaigns. This platform enables brands to find suitable influencers based on niche, reach, and engagement, while allowing influencers to discover and apply for sponsorship opportunities.

> 🛠️ Built with Flask for the backend and Vue.js (integrated through JS files, not `.vue` files) for dynamic frontend functionality.

---

## 🌐 Live Demo

Coming soon! (Deploy on platforms like Heroku, Render, or Vercel + backend if desired)

---

## 📌 Features

### 🧑‍💼 Influencer Features
- Create and edit profile
- Browse and apply for campaigns
- Track applications and responses
- Message sponsors directly

### 💼 Sponsor Features
- Register brand and create campaigns
- Browse influencer profiles
- Approve or reject influencer applications
- Direct messaging with interested influencers

### 🔐 Authentication
- Register/login for influencers and sponsors
- Session-based access management
- Profile-type based dashboard and routing

### 📊 Dashboard
- Personalized dashboards for both user types
- Overview of active campaigns, pending applications, and messages

---

## 🛠 Tech Stack

| Layer      | Technology           |
|------------|----------------------|
| Backend    | Flask (Python)       |
| Frontend   | HTML, CSS, JavaScript (Vue.js in JS files) |
| Templates  | Jinja2               |
| Database   | SQLite (default)     |
| Auth       | Flask-Login          |

---

## 📁 Project Structure

Influencer-Sponsorship-Platform-Website/
│
├── app/
│ ├── init.py # App initialization
│ ├── routes.py # All Flask routes
│ ├── models.py # SQLAlchemy models
│ └── forms.py # WTForms definitions
│
├── templates/ # HTML templates with Jinja2
│ ├── layout.html
│ ├── index.html
│ └── dashboard.html
│
├── static/
│ ├── css/
│ ├── js/
│ │ └── vue-components.js # Vue integrated via plain JS
│ └── images/
│
├── database/
│ └── schema.sql # SQL schema or migrations
│
├── requirements.txt
├── app.py # Main app entry
└── README.md


---

## 🚀 Getting Started

### ✅ Prerequisites

- Python 3.7+
- pip
- Git

### 🔧 Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/Influencer-Sponsorship-Platform-Website.git
   cd Influencer-Sponsorship-Platform-Website

Create a virtual environment

python -m venv venv
source venv/bin/activate  # Windows: venv\Scripts\activate
Install dependencies

pip install -r requirements.txt
Run the Flask app

python app.py
Visit in browser

http://localhost:5000
📸 Screenshots
(Add your screenshots here in a /screenshots folder or directly as image links)

🧪 Example Test Accounts
You can add example credentials for testing here (optional):

Influencer:
Username: influencer1
Password: test123

Sponsor:
Username: sponsor1
Password: test123
🧭 Roadmap / To-Do
 Add file upload for influencer portfolio

 Add search and filter system for campaigns

 Mobile responsiveness

 Payment system integration for premium sponsors

 Admin dashboard for platform management

🤝 Contributing
Contributions are welcome! Please open an issue or submit a pull request.

Fork the repo

Create a new branch (git checkout -b feature-x)

Make your changes

Commit and push (git commit -m 'Add feature' && git push origin feature-x)

Create a Pull Request

📬 Contact
For questions or suggestions, feel free to reach out:

Jagriti Kumari
📧 royjagriti2003@gmail.com
🔗 LinkedIn (optional)

