# Iron Man Jarvis AI Desktop Voice Assistant

This project demonstrates how to build a voice-controlled personal assistant like Iron Man's J.A.R.V.I.S. using Python. This assistant can perform tasks like sending emails, playing music, performing Wikipedia searches, opening websites, and more, all through voice commands.

## Features

- **Send Emails**: Send emails via voice commands.
- **Play Music**: Play music from your specified directory.
- **Wikipedia Searches**: Get information directly from Wikipedia.
- **Open Websites**: Open websites like Google and YouTube in your browser.
- **Open Applications**: Launch applications like VS Code with a single command.
- **Check Time**: Get the current system time.

## Prerequisites

Before running the project, ensure you have the following dependencies installed:

- Python 3.x
- `pyttsx3`: Text-to-speech conversion library.
- `speechRecognition`: To take commands from the user's microphone.
- `wikipedia`: For fetching search results from Wikipedia.
- `pypiwin32`: To resolve certain Windows-specific issues.

## Installation

1. **Clone the Repository**:
   ```bash
   git clone <git@github.com:Sadique110/Desktop-AI-Assistant.git>
   cd <Desktop-AI-Assistant>
   
2. **Install Required Dependencies**:
 ```bash
   pip install pyttsx3 speechRecognition wikipedia
```
3. **Install Additional Requirement (if needed for Windows users):** If you encounter errors like No module named win32com.client or No module named win32api, install the following::
   ```bash
   pip install pypiwin32

2. **Install Required Dependencies**:
 ```bash
   pip install pyttsx3 speechRecognition wikipedia
```

# Iron Man Jarvis AI Desktop Voice Assistant

This project demonstrates how to build a voice-controlled personal assistant like Iron Man's J.A.R.V.I.S. using Python. This assistant can perform tasks like sending emails, playing music, performing Wikipedia searches, opening websites, and more, all through voice commands.

## Setup

### 1. Create a New Python File

Create a file called `jarvis.py`.

### 2. Setup Text-to-Speech

Import `pyttsx3` and define the `speak()` function to convert text into speech.

### 3. Greeting the User

Define the `wishMe()` function to greet the user based on the current time.

### 4. Taking User Input via Microphone

Define the `takeCommand()` function to recognize and process voice commands.

### 5. Command Execution

Implement logic to respond to different commands like Wikipedia searches, playing music, etc.

## Usage

Run the program and start using the voice assistant.

```bash
python jarvis.py
```

## Commands
**You can use the following voice commands:**

**Search Wikipedia:** "Search Wikipedia for [topic]"
**Open YouTube:** "Open YouTube"
**Open Google:** "Open Google"
**Play Music:** "Play music"
**Check Time:** "What's the time?"
**Open Code Editor:** "Open code"
**Send Email:** "Email to [recipient]"
## Email Functionality
For sending emails, the sendEmail() function uses the SMTP protocol. Make sure to enable "Less secure app access" in your Gmail account for this to work.

## Contributing
Feel free to fork this project, make improvements, and submit pull requests. For any issues or suggestions, you can open an issue on GitHub.

## Contact
Feel free to contact me at **mohammadsadique110786@gmail.com** for any questions or feedback.
