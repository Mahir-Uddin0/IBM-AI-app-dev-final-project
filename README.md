# Emotion Detection Web App

## 📖 Project Description

📖 Project Description  
This project is part of the IBM *Developing AI Applications with Python and Flask* course (Module 3 assignment). IBM provided the base project skeleton, HTML/CSS templates, and a testing framework, while I implemented the emotion detection functionality by writing the API integration with the Watson NLP Library, processing the responses to extract the dominant emotion, and connecting the backend logic with Flask routes and unit tests.  
  
The goal of the project is to build a simple **Emotion Detection Web Application** using Python and Flask.  

The application allows users to enter a text sentence, which is then sent to the **Watson NLP Library API** via a REST API call. The API returns emotion scores, and the Flask backend processes this response to identify the dominant emotion (such as joy, sadness, anger, fear, or neutral). The result is then displayed on the web interface in real time. This project demonstrates how to integrate a pre-trained AI model into a Flask web application, handle user input through a front-end interface, and show predictions seamlessly.
 
This project demonstrates how to:  
- Use a cloud NLP API (Watson) for emotion detection  
- Integrate external APIs with Flask  
- Structure a Python web app (routes, request/response)  
- Handle user input and output formatting  
- Write unit tests and include error handling  
- Deploy a simple, AI-powered Flask application locally

## ⚙️ Tech Stack

- **Frontend:** HTML, CSS, JavaScript  
- **Backend:** Python, Flask  
- **Version Control:** GitHub  
- **Testing:** Python `unittest`  
- **Code Quality:** PyLint (Static Code Analysis)  
- **AI / NLP:** Watson NLP Library (via IBM Cloud IDE)  
- **Environment:** IBM Cloud IDE


## ▶️ How to Run the Project  
1. Clone the repository
```
   - git clone https://github.com/Mahir-Uddin0/IBM-AI-app-dev-final-project.git 
   - cd IBM-AI-app-dev-final-project
```

2. Install dependencies
``` 
   - pip install -r requirements.txt
``` 

3. Run the Flask app
```
   - python server.py
``` 

4. Access the app in your browser
```
   - Go to: http://127.0.0.1:5000/
``` 

---
## ⚠️ Important Note on API Access  
This project uses the **Watson NLP Library API** provided within the IBM Skills Network Labs environment.  
- The API endpoint (`sn-watson-emotion.labs.skills.network`) is **specific to the IBM Cloud IDE** used in the course.  
- If you run this project outside the Skills Network Lab, the API call may **not return results**, since public access is not available.  

### 🔧 To replicate outside IBM Skills Network Labs  
- You can adapt the project to use IBM’s official Watson Natural Language Understanding (NLU) API, which requires creating an IBM Cloud account and generating an API key.  
- Update the `emotion_detector()` function with your API key and endpoint from IBM Cloud.  
