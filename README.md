# Emotion Detector

 

Final Project — **Emotion Detector**

 

An AI-based web application that detects the emotion expressed in a piece of text using the

Watson NLP Emotion Predict library, packaged as a Python package and deployed with Flask.

 

## Project structure

 

```

.

├── EmotionDetection/

│   ├── __init__.py

│   └── emotion_detection.py

├── static/

│   └── mywebscript.js

├── templates/

│   └── index.html

├── server.py

├── test_emotion_detection.py

└── README.md

```

 

## What the application does

 

- Sends the user's text to the Watson NLP `EmotionPredict` service.

- Returns the scores for **anger, disgust, fear, joy and sadness** plus the **dominant emotion**.

- Handles blank / invalid input (HTTP status code 400) by returning `None` for every value, and

  the web page then shows `Invalid text! Please try again!`.

 

## How to run

 

```bash

python3.11 server.py

```

 

Then open `http://localhost:5000` in the browser.

 

## Tasks completed

 

1. Clone the project repository

2. Create an emotion detection application using the Watson NLP library

3. Format the output of the application

4. Package the application

5. Run unit tests on the application

6. Web deployment of the application using Flask

7. Incorporate error handling

8. Run static code analysis (pylint 10/10)
