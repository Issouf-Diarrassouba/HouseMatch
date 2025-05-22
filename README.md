🏡 HouseMatch
HouseMatch is a smart, scalable real estate matching iOS application built with SwiftUI, powered by a Vapor backend, and integrated with a FastAPI-based machine learning model. It allows users to discover personalized housing recommendations based on location, preferences, and behavior using a real-time recommendation system.

🚀 Tech Stack
Frontend: SwiftUI (iOS)

Backend: Vapor (Swift), SQLite (Prototype), Firebase

Machine Learning API: FastAPI (Python)

Geolocation: Google Maps API, RapidAPI Realtor Search

Database: Firebase Realtime Database, SQLite (for prototyping)

Deployment: AWS (Backend hosting)

🎯 Core Features
✅ User Account System
Secure authentication (signup, login, logout)

Password recovery

Session validation middleware

✅ Housing Discovery & Recommendations
Swipe-based interface for preference gathering

Personalized property matching using ML model

Real-time property listings pulled from external APIs

✅ Machine Learning Integration
Content-based filtering model

Recommends homes based on user preferences (e.g., price, size)

Refined using user feedback (likes/dislikes)

✅ Geolocation Services
Interactive map UI

Find listings based on current or selected location

Google Maps and RapidAPI integration for property suggestions

🗂 Architecture Overview
🔧 Backend – Issouf
Built RESTful APIs in Vapor

Integrated with external property listing APIs

Designed SQLite database prototype

Added geolocation-based filtering

Built error-handling and data validation layers

🎨 Frontend – Kweku
SwiftUI-based UI with a clean, responsive design

Built swipe card interaction to capture preferences

Integrated authentication flow

Preference setting and session management

🔁 Data Flow – Syl
Modeled and created Firebase tables for users and preferences

Managed backend-to-database integrations

Synced APIs and stored housing data with user filters

🤖 Machine Learning – Treasure
Developed FastAPI service with content-based recommendation engine

Ranked properties by user-defined filters + interaction data

Connected to iOS frontend via REST endpoint

Developed foundational Map UI for geolocation visualizations

📆 Development Timeline
✅ January
Implemented core authentication

Connected frontend to Firebase

Setup backend on AWS

Initial ML integration

Property API pulling and preference saving

✅ February
Improved ML accuracy and filtering

Backend ↔️ database synchronization

✅ March–April
Geolocation + map integration

Real-time property browsing

UI refinements and backend scalability testing

📌 Future Improvements
Multi-language support

Smart clustering on maps

Integration with landlord/agent portals

Real-time chat between users and property providers

🤝 Credits
Issouf Diarrassouba – Backend (Vapor, API integration, Geolocation)

Kweku – Frontend (SwiftUI)

Syl – Data modeling, Firebase integration

Treasure – ML model, FastAPI service, Map UI
