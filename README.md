# Ambulance Tracker System

🚑 **Real-time ambulance tracking and ETA prediction**

This project is a prototype for tracking ambulances in real-time using GPS, predicting ETA with a machine learning model, and displaying their locations on an interactive map. Built with Flask, React, and Leaflet.

---

## Features
- Display user’s location on a map
- Show active ambulances with live markers
- Predict ETA using a trained ML model
- Auto-refresh ambulance positions every 5 seconds
- Compatible with offline-first designs (to be implemented)

---

## Tech Stack
- Backend: Flask (Python)
- ML: Pickle-trained Random Forest model for ETA prediction
- Frontend: React + Leaflet.js
- Maps: OpenStreetMap (free alternative to Google Maps)
- Communication: REST API (GET/POST)

---

## Installation

1. Clone the repository
```bash
git clone https://github.com/username/ambulance-tracker-system.git
cd ambulance-tracker-system
