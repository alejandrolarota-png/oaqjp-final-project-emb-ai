# Emotion Detection

Final project for the IBM course "Developing AI Applications with Python and Flask".

## Project name

Emotion Detection - Embeddable AI Final Project

## Description

A web application that analyzes a text and detects the emotions it expresses: anger, disgust, fear, joy and sadness. The analysis is performed by the Watson NLP EmotionPredict library and the result is served to the user through a Flask web server.

## Project structure

EmotionDetection/ - the emotion detection package

EmotionDetection/emotion_detection.py - core function that calls the Watson NLP service

server.py - Flask web server that exposes the application

test_emotion_detection.py - unit tests for the detector

templates/ and static/ - files of the web interface

## How to run

Run the command "python3 server.py" and then open http://localhost:5000 in a browser.

## Author

Alejandro La Rota
