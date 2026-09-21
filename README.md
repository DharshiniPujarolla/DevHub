DevHub

DevHub is a full-stack GitHub intelligence platform that helps developers discover projects, analyze repositories, explore developer profiles, and compare GitHub entities using live GitHub data.

✨ Features
🔍 Repository Search — Search and explore GitHub repositories.
👨‍💻 Developer Search — Find and explore GitHub developers.
📊 Repository Analysis — View repository statistics, technologies, and activity.
🧑‍💻 Developer Snapshot — Explore developer profiles, repositories, languages, and activity.
⚖️ Smart Comparison — Compare repositories and developers side-by-side.
🚀 Project Discovery — Discover projects based on categories, languages, topics, stars, and other filters.
🛠️ Technology Explorer — Explore projects based on their technology stack.
🔄 Live GitHub Data — Uses GitHub API data instead of static/mock GitHub datasets.
🛠️ Tech Stack

Frontend

React
TypeScript
Vite
Tailwind CSS

Backend

Python
FastAPI

Data Source

GitHub REST API
🏗️ Architecture
React + TypeScript
        │
        ▼
   FastAPI Backend
        │
        ▼
    GitHub REST API
        │
        ▼
    Live GitHub Data
🚀 Getting Started
Frontend
npm install
npm run dev
Backend
pip install -r requirements.txt
uvicorn app.main:app --reload

Make sure the required environment variables are configured before running the backend.

🔐 Environment Variables

If a GitHub token is required, store it in an environment variable:

GITHUB_TOKEN=your_github_token

Never commit real API keys or tokens to the repository.

🎯 Purpose

DevHub brings multiple GitHub exploration capabilities into one platform, making it easier to discover, analyze, compare, and understand GitHub repositories and developers.

🔮 Future Scope
Advanced project recommendations
GitHub API caching
Contribution analytics
Saved repositories and developers
Intelligent project matching
👩‍💻 Author

Dharshini Pujarolla

Built as a full-stack project using React, Python/FastAPI, and the GitHub REST API.
