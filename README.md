# Daddy - Voice Assistant for VS Code
![Voice Assistant](https://private-user-images.githubusercontent.com/68538700/293602152-d70af9e7-ed43-4aa6-98a5-4dada2aad798.png?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3MjY5MzI1NjMsIm5iZiI6MTcyNjkzMjI2MywicGF0aCI6Ii82ODUzODcwMC8yOTM2MDIxNTItZDcwYWY5ZTctZWQ0My00YWE2LTk4YTUtNGRhZGEyYWFkNzk4LnBuZz9YLUFtei1BbGdvcml0aG09QVdTNC1ITUFDLVNIQTI1NiZYLUFtei1DcmVkZW50aWFsPUFLSUFWQ09EWUxTQTUzUFFLNFpBJTJGMjAyNDA5MjElMkZ1cy1lYXN0LTElMkZzMyUyRmF3czRfcmVxdWVzdCZYLUFtei1EYXRlPTIwMjQwOTIxVDE1MjQyM1omWC1BbXotRXhwaXJlcz0zMDAmWC1BbXotU2lnbmF0dXJlPTQwMjBhMjdlOTA3NTZiZjcyZjk5MjI2NjJhN2Q1MjE1ZGY0ZWE4MjQ0Njg0NjU2ZGRhYzk5Njc5ZWI2ZDU0ODUmWC1BbXotU2lnbmVkSGVhZGVycz1ob3N0In0.BkjRV8fEZNaCcSyr1IgftrrbyrpWbDRrumcDJBt9tSo)

Daddy is a Voice Assistant built using Python. It can perform various tasks such as opening websites, playing songs, getting the current time and date, sending emails, checking the weather, and more.

## Features

- **Voice Recognition:** Sudha uses the SpeechRecognition library to recognize voice commands.
- **Text-to-Speech:** Pyttsx3 is employed for converting text responses to speech.
- **Task Execution:** The assistant can perform tasks based on user commands, such as opening websites, playing songs, and more.
- **Email Functionality:** Sudha can send emails with a specified recipient, subject, and body.
- **Weather Information:** Get real-time weather updates for a specific city using the OpenWeatherMap API.
Greetings: Sudha greets you based on the time of the day.

## **Configure the assistant:**

1. Set your Gmail credentials in the send_email function.
2. Replace 'your_openweathermap_api_key' with your OpenWeatherMap API key.

## Usage

1. **Greetings: Sudha greets you based on the time of the day.**
2. **Commands: Speak commands such as:**

- Hello
- Open YouTube
- Play a song
- Get the time
- Send an email
- Check the weather

3. **Exit: Say "Exit" or "Bye" to end the interaction with Sudha.**

## Prerequisites
Before running the program, ensure you have the required Python libraries installed. You can install them using the following commands:

```bash
pip install pyttsx3
pip install SpeechRecognition
pip install datetime
pip install pyowm
pip install webbrowser
