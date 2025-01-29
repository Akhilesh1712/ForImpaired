
# ForImpaired – AI-Powered Accessibility System

🌟 Overview

ForImpaired is an AI-driven accessibility platform designed to assist individuals with hearing, visual, and speech impairments through real-time sound detection, object recognition, and sign language translation. The system enhances independence and safety using AI-powered notifications, adaptive communication, and real-time monitoring.


---

🎯 Key Features

🦻 For Hearing-Impaired Users

Sound Recognition: Detects household sounds (e.g., cooker whistle, doorbell, phone notifications) and converts them into alerts.

Speech-to-Text: Captures spoken words and presents them as text notifications.


👁️ For Visually Impaired Users

AI-Powered Object Detection: Identifies objects in a room and provides positional awareness.

Text-to-Speech Assistance: Reads out detected objects for easy navigation.


✋ For Speech-Impaired Users

Sign Language Translation: Converts hand gestures into text for smooth communication.


🏥 Smart Healthcare & Appointments

Health Tracking: Monitors vitals via smartwatches and wearable devices.

Doctor Appointment Booking: Simplifies scheduling for easy healthcare access.


📲 Cross-Device Compatibility

Notifications sent to mobile devices and wearables for real-time updates and accessibility.



---

🛠️ Tech Stack

Frontend (React.js)

React.js – Interactive UI for a seamless user experience

Bootstrap – Ensures responsive design and accessibility

WebSockets – Enables real-time communication


Backend (Flask & Express.js)

Flask – Handles AI models & API services

Express.js – Manages authentication & data

MongoDB – Stores user data and preferences


AI/ML Technologies

TensorFlow – AI-based object detection & sign language translation

OpenCV – Image processing for visually impaired users

SpeechRecognition API – Converts speech to text



---

📦 Installation & Setup

1️⃣ Clone the Repository

git clone https://github.com/Akhilesh1712/ForImpaired.git
cd ForImpaired

2️⃣ Backend Setup

cd backend
pip install tensorflow flask flask-socketio
python app.py

3️⃣ Frontend Setup

cd frontend

npm init -y

npm install @tensorflow-models/coco-ssd @tensorflow/tfjs bootstrap express express-ws mongoose jsonwebtoken bcrypt hbs dotenv

npm start


---

🚀 Usage Guide

1️⃣ Run the frontend and backend servers.
2️⃣ Open the main application page (http://localhost:3000).
3️⃣ Explore features:

Chatbot: Bottom-right for instant assistance.

"Join Us" Page: Access the main service page for all accessibility tools.

Real-Time Alerts: Sound detection, object recognition, and sign language translation.



---

🎯 Impact & Future Enhancements

🚀 Making everyday life easier for individuals with impairments.
💡 Upcoming Features:

Voice Synthesis: Real-time AI-generated speech for blind users.

Advanced AI Recommendations: Tailored accessibility suggestions based on usage patterns.

Smart Home Integration: AI-powered control of household devices for enhanced accessibility.



---

🤝 Contributing

We welcome contributions! Here's how you can help:

1. Fork the repo.


2. Create a new branch (feature-branch).


3. Commit your changes.


4. Submit a Pull Request.




---

📝 License

This project is open-source and available under the MIT License.

