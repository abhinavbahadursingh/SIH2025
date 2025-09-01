🚦 Traffic Management System

A comprehensive Traffic Management System designed to monitor, analyze, and manage traffic data in real-time. This system combines a web-based PHP/HTML frontend for live monitoring and geofencing with a Python/Node.js backend for traffic analytics and vehicle classification.

🌟 Features
Frontend (PHP / HTML / JavaScript)

Live Camera Feeds: View multiple live camera feeds (from YouTube) on a single dashboard.

Accident Detection & Reporting: Detect vehicle accidents and send notifications to Telegram with Google Maps location.

Geofencing & Vehicle Tracking:

Live Map showing real-time vehicle locations

Create, edit, and delete geofences

Maintain history logs of vehicle movements

Dashboard: Central dashboard for navigation across all modules

Backend (Python / Node.js)

Real-time Traffic Monitoring: Collect and analyze traffic data in real-time

Vehicle Counting & Classification: Categorize vehicles (bus, car, truck)

Traffic Congestion Analysis: Identify congestion hotspots

Interactive Data Visualization: Charts and graphs for traffic metrics

Alerts: Real-time notifications for unusual traffic patterns

🛠 Technology Stack

Frontend: PHP, HTML, CSS, JavaScript, Chart.js
, Leaflet.js
, Google Maps API

Backend: Python / Node.js / Java

Database: Firebase Realtime Database, MySQL / MongoDB / PostgreSQL

Libraries & Tools: OpenCV, TensorFlow, APIs for traffic data, Telegram Bot API

⚙️ Setup Instructions
Frontend (PHP / HTML / JS)

Clone the repository:

git clone https://github.com/your-username/your-php-frontend.git


Configure Firebase:

Create a project on Firebase Console

Create a Realtime Database

Replace placeholders in HTML/PHP files with Firebase config

Configure Google Maps API:

Get an API key from Google Cloud Console

Replace placeholders in geo/*.php files

Configure Telegram Bot:

Create bot using BotFather

Replace token & chat ID in send_sms.php

Deploy to a web server (Apache/Nginx with PHP support)

Backend (Python / Node.js)

Clone the repository:

git clone https://github.com/abhinavabahdursingh/SIH2025.git


Navigate to project folder:

cd traffic-project


Install dependencies:

npm install  # for Node.js backend
pip install -r requirements.txt  # for Python backend


Run the backend application:

python app.py  # or node server.js

🚀 Usage

Access the frontend dashboard via your web browser

Monitor live camera feeds and geofenced vehicles

View real-time traffic analytics from the backend

Customize alerts and reports based on traffic data

📸 Screenshots

Add your project screenshots here for dashboard, live feeds, charts, and maps:




🤝 Contributing

Fork the repository

Create a new branch for your feature/bugfix

Submit a pull request

🔮 Future Improvements

Implement authentication to secure admin dashboard

Improve error handling and logging

Refactor code to reduce duplication and improve maintainability

Store API keys in a separate configuration file excluded from version control

Document traffic data sources and analytics flow

📄 License

This project is licensed under the MIT License.
