# Accessibility-Analyzer

accessibility-analyzer/

├── backend/

├── frontend/
                                   # Proxy to backend
├── start.bat                    # Script to start both frontend and backend
├── README.md                    # Project documentation
├── .gitignore                   # Ignore node_modules, .env, etc.
└── LICENSE                      # Optional: Add license
Suggested .gitignore
gitignore
Copy
Edit
# Global
node_modules/
.env
.DS_Store

# Frontend
frontend/build/

# Logs
*.log
npm-debug.log*

# OS
Thumbs.db
Suggested README.md
markdown
Copy
Edit
# Accessibility Analyzer 🔍

A full-stack web app to check accessibility of websites, featuring scan history, sample URLs, and a polished UI.

## Features
- ✅ URL accessibility scanning
- ✅ Scan history with delete
- ✅ Sample URLs for quick tests
- ✅ Stylish UI with background video
- ✅ Frontend-backend integration

## Setup

# Start both servers (Windows)
start.bat
Or manually:


--bash
# Backend
cd backend
npm install
npm start

# Frontend
cd ../frontend
npm install
npm start


API
POST /api/scan – Scan a given URL

GET /api/scan – Get scan history

DELETE /api/scan/:id – Delete a scan entry
