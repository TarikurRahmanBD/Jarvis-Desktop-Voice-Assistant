# Jarvis Desktop Voice Assistant

A desktop voice assistant built with Python that listens for commands, performs simple automation, and responds with speech. Jarvis is designed to help users check the time and date, search Wikipedia, open websites, play music, capture screenshots, tell jokes, and more.

## Project Overview

This project is a beginner-friendly desktop assistant that uses voice recognition and Python automation libraries to perform common tasks. It runs from the `Jarvis/jarvis.py` script and can work with speech input when a microphone is available. If voice input is not available, the assistant can also accept typed commands.

## How to Install & Run

Follow these steps to get Jarvis running on your machine.

### 1. Clone the repository

```powershell
git clone <repository-url>
cd Jarvis-Desktop-Voice-Assistant-main
```

### 2. Set up a Python virtual environment

```powershell
python -m venv .venv
.venv\Scripts\activate
```

### 3. Install project dependencies

```powershell
pip install -r requirements.txt
```

### 4. Install PyAudio for microphone support (Windows)

Jarvis uses `speech_recognition`, which typically requires `PyAudio` for microphone input. On Windows, you can install it with `pipwin` or from a wheel file.

```powershell
pip install pipwin
pipwin install pyaudio
```

> If microphone support is not available, Jarvis will fall back to typed commands.

### 5. Run the assistant

```powershell
python .\Jarvis\jarvis.py
```

### 6. Use Jarvis

When the assistant starts, speak a command or type one if prompted. Common commands include:

- `time`
- `date`
- `open google`
- `open youtube`
- `play music`
- `tell me a joke`
- `screenshot`
- `offline`

## Features

- **Voice-based command input** with a text fallback option
- **Current time and date reporting**
- **Search Wikipedia** for quick summaries
- **Open websites** such as Google and YouTube
- **Play music** from the local `Music` directory
- **Capture screenshots** and save them automatically
- **Tell jokes** using the `pyjokes` library
- **Change assistant name** and save it for future sessions

## Project Structure

- `Jarvis/jarvis.py` - Main assistant script
- `requirements.txt` - Python dependencies
- `Jarvis/data.txt` - Data file used by the assistant
- `Jarvis/README.md` - Additional project notes
- `Images/` - Project image assets
- `Presentation/` - Presentation materials

## About the Developer

**Tarikur Rahman**

- GitHub: https://github.com/tarikurrahmanbd
- Portfolio: https://yourtarikur.vercel.app/
- Social/Handle: `tarikurrahman08`
- Email: tarikurrahman2008@gmail.com

## License

This project is licensed under the **MIT License**.

---

Thank you for exploring Jarvis Desktop Voice Assistant. If you have improvements or new features in mind, contributions are welcome!
