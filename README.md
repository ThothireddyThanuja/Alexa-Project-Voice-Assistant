# Alexa-Project-Voice-Assistant

An interactive voice assistant project coded in Python, offering a range of tasks like answering questions, playing music on YouTube, giving the current date and time, telling jokes, providing weather updates, opening applications, and more. This project mimics the functionality of popular voice assistants and provides a hands-free experience using voice commands.

# Table of Contents

1.	Project Overview
2.	Features
3.	Technologies Used
4.	Setup 
5.	Commands
6.	Future Enhancements

# Project Overview

The Alexa Project Voice Assistant listens to voice commands, processes them, and performs various tasks such as playing music, telling jokes, giving the current time, or even calculating mathematical expressions. Developed in Python, it utilizes libraries like SpeechRecognition for input, pyttsx3 for speech synthesis, and pywhatkit to interact with YouTube.

# Features

1. Natural Language Processing: Uses Google Speech Recognition to interpret voice commands.
2. Voice Feedback: Responds audibly using text-to-speech.
3. Multi-Functionality: Can play music, retrieve information from Wikipedia, give weather updates, tell jokes, open applications, and more.
4. Simple Integration: Easily extensible to add more commands and responses.

# Technologies Used

1. Python Libraries:
    * speech_recognition: For voice command recognition
    * pyttsx3: For text-to-speech conversion
    * pywhatkit: For playing music on YouTube
    * wikipedia: To retrieve brief summaries of topics
    * pyjokes: To generate jokes
    * datetime: To get the current date and time
    * Os and random: For additional functionality, like opening applications and random tasks
      
2. External API: Py_Weather for weather updates

# Setup 

  # Prerequsites
  
*	Python 3.x installed on your system.
*	Internet connection for certain commands (e.g., YouTube, Wikipedia, weather updates).

# Commands
Here are some commands you can try:

•	Greeting and Status:
  *	"Alexa, how are you?" - Check on the assistant’s status.
  *	"Alexa, what are you doing?" - Find out what the assistant is currently processing.
    
•	Play Music:
  *	"Alexa, play [song name]" - Plays the specified song on YouTube.
    
•	Information Queries:
  *	"Alexa, who is [name]?" - Provides a brief Wikipedia summary of the person.
  *	"Alexa, tell me a joke" - Tells a random joke.
    
•	Utilities:
  *	"Alexa, what is the time?" - Provides the current time.
  *	"Alexa, what is today’s date?" - Provides the current date.
  *	"Alexa, open notepad" - Opens the Notepad application.
  *	"Alexa, roll a dice" - Rolls a virtual dice and provides the result.
  *	"Alexa, square root of [number]" - Calculates and returns the square root of a number.
  *	"Alexa, set a timer for [seconds]" - Sets a timer.
    
•	Farewell:
  *	"Alexa, bye" - Ends the session with the assistant.

# Future Enhancements

Potential future features to enhance the assistant’s functionality include:
  *	Adding more applications it can open.
  * Expanding language options for more inclusive usage.
  *	Adding the ability to handle more complex queries and perform internet searches.
  *	Implementing continuous listening mode without needing to re-activate.
