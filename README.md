# Emotion Detection Web App

## 📖 Project Description

This project is part of the **IBM Developing AI Applications with Python and Flask** course (Module 3 assignment).  
The goal of the project is to build a simple **Emotion Detection Web Application** using Python and Flask.  

The application allows users to enter a text sentence, which is then sent to the **Watson NLP Library API** via a REST API call. The API returns emotion scores, and the Flask backend processes this response to identify the dominant emotion (such as joy, sadness, anger, fear, or neutral). The result is then displayed on the web interface in real time. This project demonstrates how to integrate a pre-trained AI model into a Flask web application, handle user input through a front-end interface, and show predictions seamlessly.
 
This project demonstrates how to:  
- Use a cloud NLP API (Watson) for emotion detection  
- Integrate external APIs with Flask  
- Structure a Python web app (routes, request/response)  
- Handle user input and output formatting  
- Write unit tests and include error handling  
- Deploy a simple, AI-powered Flask application locally  

## ▶️ How to Run the Project  
1. Clone the repository
```
   - git clone https://github.com/<your-username>/<repo-name>.git  
   - cd <repo-name>
```

3. Install dependencies
``` 
   - pip install -r requirements.txt
``` 

5. Run the Flask app
```
   - python app.py
``` 

7. Access the app in your browser
```
   - Go to: http://127.0.0.1:5000/
``` 

---
