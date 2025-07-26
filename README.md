## Conversational AI Bot 

A simple AI-powered chatbot web application built using Flask (Python) for the backend and HTML/CSS/JavaScript (with jQuery) for the frontend. It uses Google Gemini (Generative AI) for generating chat responses.

## 🚀 Features

Real-time messaging with AI responses

Clean and responsive chat UI

Integrated with Gemini 1.5 Flash model via Google Generative AI API

Uses AJAX for smooth, asynchronous communication

## 📁 Project Structure

├── app.py             # Flask backend logic
├── templates/
│   └── index.html     # Frontend UI
├── static/            # (Optional) For custom CSS/JS
├── README.md          # Project documentation

## ⚙️ Requirements

Python 3.7+

Flask

google-generativeai

Install dependencies:

pip install flask google-generativeai

## 🔑 Setup Google API Key

Replace the placeholder in app.py with your actual Google Generative AI API key:
Google_API_KEY = "YOUR_API_KEY"

## ▶️ How to Run

1.Clone or download the repository

2.Navigate to the project directory

3.Run the app:
python app.py

4.Open your browser and go to: http://127.0.0.1:5000/

## 💬 Example Chat Flow

User: "Hello"

Bot: "Hi there! How can I assist you today?"

## 📌 Notes

Ensure your API key has access to Gemini models.

The UI uses Bootstrap 5 and jQuery via CDN for simplicity.



