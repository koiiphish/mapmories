# mapmories
Mapmories
# 🌍 TravelMap Social App

Welcome to **TravelMap**, a social web app where users can:
- Track the countries they've visited on a personal world map
- Add location-tagged memories with photos, titles, and descriptions
- View their travel history and share it with others (future features)

Think of it as **Instagram meets Google Maps**, personalized for globetrotters!

---

## 📸 Features

- 🔐 **User Authentication** (Sign Up / Login via Firebase)
- 🗺️ **Interactive World Map** (Click to mark visited countries)
- 📍 **Geo-Tagged Memories** (Text + Photo + Location)
- 📁 **Profile Page** with user-specific map and memory list
- ☁️ **Firebase Integration** for:
  - Authentication
  - Firestore (user data & memories)
  - Storage (photos)

---

## 📦 Tech Stack

| Frontend        | Backend / Cloud         | Map & Geo          |
|-----------------|--------------------------|--------------------|
| React.js        | Firebase Auth            | React-Leaflet      |
| React Router    | Firebase Firestore (DB)  | GeoJSON            |
| Styled-Components / CSS | Firebase Storage (images) | Country Codes        |

---

## 🚀 Getting Started

### 🛠️ Prerequisites

- Node.js v18+
- Firebase project setup (Auth, Firestore, Storage)

### 📂 Installation

```bash
git clone https://github.com/yourusername/travelmap-app.git
cd travelmap-app
npm install
