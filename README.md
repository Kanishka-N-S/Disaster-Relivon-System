# Disaster-Relivon-System

Disaster Relivon System (DRS) is a real-time web-based platform designed to assist in disaster management and emergency response. It enables users to send SOS alerts with their live location, while volunteers can register and provide help. The system uses geolocation and cloud-based database services to ensure quick coordination during emergencies.

---

## 🎯 Features

### 🚨 SOS Alert System
- Users can send emergency alerts with selected needs:
  - Food
  - Water
  - Medical Aid
  - Shelter
  - Evacuation
- Automatically captures live location
- Stores alerts in real-time database

---

### 🗺️ Live Map Tracking
- Displays:
  - SOS alerts (📍 markers)
  - Volunteers (👤 markers)
- Uses Leaflet.js for map visualization
- Updates automatically every few seconds

---

### 👥 Volunteer System
- Volunteers can:
  - Register with name & phone number
  - Share their live location
  - Update location anytime
- Stored in Firebase for real-time visibility

---

### 📊 Dashboard
- Central monitoring system
- Displays:
  - Live map of alerts and volunteers
  - Emergency contacts
  - Preparedness checklist
- Helps coordinate disaster response efficiently

---

### 📞 Emergency Contacts
- 🚨 112 – National Emergency
- 🚑 108 – Ambulance
- 🚒 101 – Fire Service
- 👮 100 – Police
- 🌊 1070 – Disaster Control

---

## 🛠️ Technologies Used

- Frontend:
  - HTML5
  - CSS3
  - JavaScript

- Libraries:
  - Leaflet.js

- Backend / Database:
  - Firebase Realtime Database

- APIs:
  - Geolocation API

---

## 📁 Project Structure

DRS Project/

├── index.html  
├── dashboard.html  
├── volunteer.html  

├── style.css  
├── dashboard.css  

├── script.js  
├── dashboard.js  

---

## ⚙️ How It Works

1. User opens the system  
2. Selects required help and clicks SEND SOS  
3. Location is captured and stored in Firebase  
4. Dashboard displays alert on live map  
5. Volunteers can view and respond accordingly  

---

## 🚀 Setup Instructions

1. Clone the repository:
   git clone <your-repo-link>

2. Open project folder:
   cd drs-project

3. Open index.html in browser

---

## 🔐 Firebase Setup

- Create a Firebase project  
- Enable Realtime Database  
- Replace config in JS files:

const firebaseConfig = {
  apiKey: "YOUR_API_KEY",
  authDomain: "YOUR_DOMAIN",
  databaseURL: "YOUR_DB_URL",
  projectId: "YOUR_PROJECT_ID"
};

---

## 📜 License
This project is for educational and research purposes.

---

Relivon – Connecting Help to Those Who Need It, Instantly
