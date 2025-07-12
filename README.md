# Choose Your Own Adventure AI

An AI-powered interactive storytelling web application that allows users to generate, play, and explore dynamic stories based on their choices.

## Project Overview
This project leverages generative AI to create unique, branching narratives. Users can input themes or prompts, and the system generates storylines that adapt to their decisions, providing a personalized adventure each time.

## Features
- **AI Story Generation:** Dynamic stories generated using AI models and custom prompts.
- **Interactive Gameplay:** Users make choices that influence the direction and outcome of the story.
- **Full Stack Application:** React frontend with a FastAPI backend.
- **Persistent Storage:** Stories and user progress are stored in a SQLite database.
- **RESTful API:** Modular backend with clear separation of concerns (routers, schemas, models).

## Technologies Used
- **Frontend:** React, Vite, JavaScript (ES6+), CSS
- **Backend:** Python, FastAPI
- **Database:** SQLite
- **Other:** ESLint, modern dependency management (pyproject.toml, requirements.txt, package.json)

## Getting Started

### Prerequisites
- Node.js & npm
- Python 3.8+

### Setup

#### Backend
```bash
cd backend
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
pip install -r requirements.txt
uvicorn main:app --reload
```

#### Frontend
```bash
cd frontend
npm install
npm run dev
```

The frontend will be available at `http://localhost:5173` and the backend at `http://localhost:8000` by default.

## Project Structure
- `backend/` - FastAPI backend, database, and API logic
- `frontend/` - React frontend and UI components

## License
This project is for educational and demonstration purposes. 