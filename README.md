# Jarvis-AI
An advanced AI assistant inspired by Iron Man’s JARVIS, built with Python,React.js It provides real-time responses, voice interaction, weather updates, and a futuristic UI.
## 🧠 Project Story and Acknowledgements

This project — **JARVIS AI** — was inspired by my fascination with Iron Man’s digital assistant and my desire to build something intelligent, interactive, and futuristic. I wanted to develop a system that could *listen*, *speak*, *analyze*, and *perform tasks* — just like the fictional JARVIS.

While this idea was originally mine, I have to acknowledge that the implementation was deeply inspired by various open-source projects and tutorials that helped me learn and experiment. In particular, I was influenced by a GitHub repository that demonstrated how to create a **Python-based AI assistant** using multiple modules and APIs.

I studied their structure and used it as a learning foundation to build my own version of JARVIS. This project taught me how to integrate **speech recognition**, **voice synthesis**, **API connections**, and **automation** into a single AI system.

---

## ⚙️ Technologies and Requirements

The project uses multiple Python libraries to achieve real-time interaction and automation, including:

* `datetime` — for fetching the current date and time
* `os` — for performing system-level operations
* `pyttsx3` — for text-to-speech voice output
* `wikipedia` — for knowledge-based answers
* `speech_recognition` — for recognizing user voice commands
* `webbrowser` — to open websites using voice
* `sys`, `smtplib`, `requests`, `json`, `difflib`, `geocoder` — for various system and API functions
* `pyjokes`, `psutil`, `pyautogui`, `opencv` — for humor, system monitoring, screen control, and computer vision

### 🔧 Installation

Install all required dependencies with:

```bash
pip install -r requirements.txt
```

For Windows users, install **PyAudio** manually from [https://www.lfd.uci.edu/~gohlke/pythonlibs/#pyaudio](https://www.lfd.uci.edu/~gohlke/pythonlibs/#pyaudio)

```bash
pip install PyAudio-0.2.11-cp<version>-cp<version>m-win_amd<architecture>.whl
```

On Ubuntu-based Linux distributions:

```bash
sudo apt-get update && sudo apt-get install espeak
```

---

## 💬 Features Implemented

* **Optical Face Recognition** for dynamic authentication
* **Email Sending** using SMTP
* **News Headlines** fetched from APIs dynamically
* **Persistent To-Do List** (remembers your tasks!)
* **Voice-Activated Website Access**
* **Music Player** integrated with system directories
* **Wikipedia-powered Question Answering**
* **Smart Dictionary** with spell correction
* **Weather Reports** (temperature, wind, humidity, etc.)
* **Geolocation Tracking** (latitude and longitude)
* **YouTube & Google Maps Voice Search**
* **YouTube Downloader** via URL input
* **Voice Mode Switching** between J.A.R.V.I.S and F.R.I.D.A.Y

---

## 🔊 Sample Commands

* “Jarvis, are you there?” → *At your service, Sir.*
* “Jarvis, what are today’s news headlines?” → Reads and opens source links.
* “Search YouTube” → Asks for topic, opens results in browser.
* “Jarvis, can you send an email to Gaurav?” → Composes and sends automatically.

---

## 🙏 Credits and Acknowledgement

I want to extend full credit to the developers and educators whose open-source contributions and tutorials made this project possible.
I explored multiple **YouTube tutorials**, **GitHub repositories**, and **technical blogs**, adapting different parts to fit my concept.

This project is not an original invention but rather a **learning-based recreation**, built with admiration and curiosity.
It represents my growth in understanding how Python, APIs, and AI components can interact to build something truly intelligent.

Special thanks to the open-source community for their incredible resources — without them, this project would not have come to life.

---

## 🧩 Future Scope

* Integration with OpenAI or other NLP models for conversational responses
* Visual dashboard for voice commands and data tracking
* Smarter automation (system control, reminders, scheduling)
* Advanced neural voice synthesis

---

Developed as a **learning project** — inspired by existing open-source implementations and built with the goal of creating my own intelligent AI assistant experience.
