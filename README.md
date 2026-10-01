# 🌱 AI Green Campus – Smart Sustainability Management System

**Team:** GreenMinds AI

AI Green Campus is a web-based sustainability management prototype designed to help educational institutions monitor campus sustainability indicators and receive practical improvement recommendations.

## Features

- 📊 Sustainability dashboard
- ⚡ Energy monitoring
- 💧 Water monitoring
- ♻️ Waste-management monitoring
- 🌳 Green-cover tracking
- 🤖 AI-style sustainability recommendations
- ✅ Sustainability action tracker
- 🗄️ SQLite database
- 📱 Responsive web interface
- 🔌 REST API for dashboard data

## Technology Stack

- Frontend: HTML, CSS, JavaScript
- Backend: Python + Flask
- Database: SQLite
- AI layer: rule-based recommendation engine (prototype)
- Version control: Git + GitHub

## Project Structure

```text
AI-Green-Campus-Smart-Sustainability-Management-System/
├── app.py
├── requirements.txt
├── .gitignore
├── README.md
├── templates/
│   └── index.html
└── static/
    ├── css/
    │   └── style.css
    └── js/
        └── app.js
```

## How to Run

### 1. Install Python

Use Python 3.10+.

### 2. Create a virtual environment

Windows:

```bash
python -m venv venv
venv\Scripts\activate
```

### 3. Install dependencies

```bash
pip install -r requirements.txt
```

### 4. Start the application

```bash
python app.py
```

### 5. Open in your browser

```text
http://127.0.0.1:5000
```

The SQLite database is created automatically when the application starts.

## API Endpoints

| Method | Endpoint | Purpose |
|---|---|---|
| GET | `/api/dashboard` | Get dashboard data |
| POST | `/api/reports` | Add sustainability data |
| POST | `/api/recommend` | Generate recommendation |
| PUT | `/api/actions/<id>` | Update action status |

## Demo Flow

1. Open the dashboard.
2. Show the four sustainability indicators.
3. Add a new Energy/Water/Waste/Green Cover reading.
4. Generate a recommendation.
5. Update an action from Pending to In Progress/Completed.
6. Explain how future versions can connect IoT sensors and ML models.

## Future Enhancements

- IoT sensors for real-time electricity and water readings
- Machine-learning forecasting
- Carbon-footprint calculation
- Smart-bin integration
- Solar-energy monitoring
- Automated alerts
- Student sustainability participation points
- Admin authentication
- Cloud deployment
- Advanced analytics and reports

## SDG Alignment

The project can support campus-level initiatives related to:

- **SDG 6:** Clean Water and Sanitation
- **SDG 7:** Affordable and Clean Energy
- **SDG 11:** Sustainable Cities and Communities
- **SDG 12:** Responsible Consumption and Production
- **SDG 13:** Climate Action
- **SDG 17:** Partnerships for the Goals

## Team

**GreenMinds AI**:
Annapoorna K,
Jayasri A,
Abisha S,
Hemavathi E

Project: **AI Green Campus – Smart Sustainability Management System**
