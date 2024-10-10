Voice Assistant using Python
Overview

This is a voice-activated assistant built in Python that allows users to execute various commands using voice input. The assistant can perform tasks such as searching the web, playing music, opening applications, and more, using a simple graphical user interface (GUI) built with Tkinter.
Features

    Voice Recognition: Uses the SpeechRecognition library to convert speech to text.
    Web Browsing: Opens Google or YouTube and executes searches.
    Media Control: Plays music from a specified directory and can play videos.
    System Commands: Can shut down, restart, or lock the system.
    Screen Capture: Takes screenshots and saves them with user-defined names.
    Custom Commands: Allows for typing, dragging windows, and drawing shapes.
    Logging: Displays executed commands in a scrollable log area.

Requirements

To run the assistant, you'll need:

    Python 3.x
    Required libraries:
        pyautogui
        speech_recognition
        wikipedia
        requests
        opencv-python
        tkinter

You can install the required libraries using pip:

bash

pip install pyautogui speech_recognition wikipedia requests opencv-python

Usage

    Clone the repository or download the script.
    Run the script using Python:

    bash

    python voice_assistant.py

    Click on the "Start" button to begin using the voice assistant.
    Speak your commands clearly. The assistant will respond based on the recognized command.

Example Commands

    "Open YouTube"
    "Search on YouTube for [query]"
    "Play music"
    "What is the time?"
    "Take a screenshot"
    "Who are you?"

GUI Interface

The GUI consists of:

    A welcome label.
    A "Start" button to activate the voice command listener.
    An "Exit" button to close the application.
    A log area to display executed commands.

Troubleshooting

    Ensure that your microphone is working properly.
    Make sure you have a stable internet connection for speech recognition.
    If using cv2 for the camera, ensure your camera is connected and accessible.

Contributing

Feel free to contribute to this project! Submit issues or pull requests to improve functionality or add features.
License

This project is open-source and available under the MIT License.