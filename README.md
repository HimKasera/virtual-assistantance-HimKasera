# VISIGUIDE: A Voice Assistant with OpenAI Integration

## Overview

VISIGUIDE is a voice assistant application built using Python that allows you to interact with various services, including OpenAI for generating stories, poems, and more. It also integrates functionalities like web browsing, email sending, Wikipedia search, and more—all controlled by your voice commands.

## Features

- **Voice Interaction**: The assistant listens to your voice and performs tasks like opening websites, generating text, and sending emails.
- **OpenAI Integration**: It can generate short stories, poems, and answers based on your voice queries using OpenAI's GPT model.
- **Wikipedia Search**: Allows you to search Wikipedia and read the summaries.
- **Email Functionality**: The assistant can send emails on your behalf (requires email setup).
- **Customizable Commands**: Add new commands as needed.

## Technologies Used

- Python
- OpenAI API
- pyttsx3 (Text to Speech)
- SpeechRecognition
- Wikipedia API
- smtplib (Email Sending)
- Web Browser Automation

## Installation

### Prerequisites

Make sure you have the following installed:

- Python 3.x
- Required libraries:
  - `pyttsx3`
  - `speechRecognition`
  - `wikipedia`
  - `openai`
  - `pyttsx3`
  - `smtplib` (for email functionality)

To install the dependencies, run:

```bash
pip install pyttsx3 speechRecognition wikipedia openai
