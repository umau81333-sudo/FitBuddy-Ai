# FitBuddy - AI Fitness Plan Generator

FitBuddy is a FastAPI + Jinja2 + SQLite web application that generates a personalized 7-day wellness/activity plan, a nutrition/recovery tip, and an AI-assisted revised plan from user feedback.

## Technologies

- Python
- FastAPI
- Uvicorn
- Jinja2
- SQLAlchemy
- SQLite
- Google GenAI SDK
- HTML
- CSS

## Folder structure

```text
FitBuddy/
│
├── app/
│   ├── __init__.py
│   ├── main.py
│   ├── config.py
│   ├── database.py
│   ├── models.py
│   ├── schemas.py
│   ├── gemini_client.py
│   ├── gemini_generator.py
│   ├── gemini_flash_generator.py
│   ├── updated_plan.py
│   └── routes.py
│
├── templates/
│   ├── index.html
│   ├── result.html
│   └── all_users.html
│
├── static/
│   └── css/
│       └── style.css
│
├── tests/
│   └── test_app.py
│
├── requirements.txt
├── .env.example
├── .gitignore
├── README.md
└── run.bat