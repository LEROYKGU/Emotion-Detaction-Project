![Python](https://img.shields.io/badge/Python-3.10-blue)
![Scikit-Learn](https://img.shields.io/badge/ML-ScikitLearn-orange)
![Status](https://img.shields.io/badge/Status-Completed-success)

# Emotion Detection Web Application

## Overview
This project was developed as part of the IBM certification:

**Developing AI Applications with Python and Flask**

The application is an AI-powered emotion detection web application that analyzes user-provided text and predicts the associated emotion using Natural Language Processing (NLP) techniques.

The project demonstrates the integration of:
- Artificial Intelligence
- Natural Language Processing
- Python backend development
- Flask web framework
- Frontend-backend interaction

---

# Project Objectives

The main objectives of this project are:

- Build an AI-powered text emotion detection system
- Develop a Flask-based web application
- Process user text inputs dynamically
- Integrate AI inference into a web interface
- Demonstrate deployment-ready AI application architecture

---

# Features

## Emotion Detection
The system analyzes textual input and predicts emotions such as:
- Joy
- Sadness
- Anger
- Fear
- Disgust
- Surprise

---

## Interactive Web Interface
Users can:
- Enter text directly into the web application
- Submit text for emotion analysis
- Receive real-time prediction results

---

## REST API Integration
The backend server exposes AI functionalities through Flask routes and APIs.

---

# Project Structure

```bash
EmotionDetection/
│
├── EmotionDetection/          # Core emotion detection package
│   ├── __init__.py
│   ├── server.py              # Flask backend server
│   └── .text                  # Model or text resources
│
├── static/
│   └── mywebscript.js         # Frontend JavaScript logic
│
├── index.html                 # Main frontend interface
├── README.md                  # Project documentation
├── LICENSE
└── .gitignore
```
---

# Technologies Used
## Programming Language
* Python
## Frameworks
* Flask
## AI & NLP Libraries
* Natural Language Processing techniques
* Machine Learning-based emotion analysis
## Frontend
* HTML
* JavaScript
---

# Application Architecture

The application follows a client-server architecture:

### Frontend

The frontend interface:

- Captures user text input
- Sends requests to the backend server
- Displays emotion prediction results dynamically

Main file:

* index.html
* static/mywebscript.js
* Backend

The Flask backend:

* Receives user requests
* Processes text input
* Executes emotion detection logic
* Returns prediction results as responses

Main backend file:

* `EmotionDetection/server.py`
---
# Installation

Clone the repository:
```bash
git clone https://github.com/LEROYKGU/Emotion-Detaction-Project.git
```
Navigate to the project directory:
```bash
cd Emotion-Detaction-Project
```
Install required dependencies:
```bash
pip install -r requirements.txt
```
---
# Running the Application

Start the Flask server:

```bash
python EmotionDetection/server.py
```
The application will run locally on:

```bash
http://localhost:5000
```
Open the URL in your browser to interact with the application.

# Example Workflow
1. User enters text into the web interface
2. Frontend sends request to Flask backend
3. Backend processes text using emotion detection logic
4. Predicted emotion is returned
5. Result is displayed dynamically on the webpage

---
# Learning Outcomes

This project demonstrates practical skills in:

- AI application development
- Flask backend engineering
- API integration
- NLP workflow integration
- Frontend-backend communication
- Interactive AI systems

---
# IBM Certification Context

This project was completed as part of the IBM course:

#### Developing AI Applications with Python and Flask

The course focuses on:

- Building AI-powered applications
- Integrating machine learning into web systems
- Flask development
- REST APIs
- Deployment-ready architectures

Provided by:
IBM Skills Network

# Future Improvements

Potential enhancements include:

* Deep learning-based emotion classification
* Transformer models (BERT, RoBERTa)
* Speech emotion recognition
* Real-time chatbot integration
* Cloud deployment
* Docker containerization
* User authentication system

---
# Author

KGU
Data Science Enthusiast | AI & NLP Practitioner

GitHub: https://github.com/LEROYKGU

# License

This project is licensed under the MIT License.
