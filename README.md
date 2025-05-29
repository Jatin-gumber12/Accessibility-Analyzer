
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
