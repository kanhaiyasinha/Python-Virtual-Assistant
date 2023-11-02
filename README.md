# Python-Virtual-Assistant

This is a Python-based virtual assistant capable of performing various tasks using speech recognition and text-to-speech functionalities.

## Overview

The virtual assistant is designed to perform multiple tasks by processing voice commands from the user. It interacts with the user through speech and can execute various commands, such as retrieving information from Wikipedia, opening web browsers, playing music, providing the current time, sending emails, and opening specific applications or projects.

## Features

- **Voice Interaction:** Utilizes speech recognition for user input and speech synthesis for responses.
- **Wikipedia Search:** Retrieves information from Wikipedia based on user queries.
- **Web Browser Control:** Opens popular websites like YouTube, Google, and Stack Overflow.
- **Music Player:** Plays music from a specified directory.
- **Time Reporting:** Provides the current time on request.
- **Email Sending:** Sends emails based on user input.
- **Application Launching:** Opens specific applications or projects.

## Requirements

To run this virtual assistant, you need to install the following Python libraries:

- `pyttsx3`
- `speech_recognition`
- `wikipedia`
- `webbrowser`
- `smtplib`

Also, ensure to have the necessary dependencies such as `PyAudio` and Microsoft Visual C++ 14.0 for `PyAudio`.

## Usage

1. Run the Python script.
2. The virtual assistant will greet the user and wait for voice commands.
3. Speak commands such as "Open YouTube," "What is the time," or "Play music" to execute tasks.

## Configuration

For functionalities like sending emails, ensure to provide your email credentials in the `sendEmail()` function.

## Customization

Feel free to expand the capabilities by adding more functions based on your requirements. You can modify the code to include additional commands or integrate more services.
