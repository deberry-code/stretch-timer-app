# Stretch Timer App

**Stretch Timer App** is a customizable sequence timer for stretches, specially built for dancers, athletes, and anyone who wants guided stretching sessions.
It uses **sound prompts** and **text-to-speech (TTS)** to guide users through each stretch.

## What the project does
- Allows users to create a personalized sequence of stretches.
- Optionally adjusts durations for each stretch.
- Guides users with audio instructions and relaxing sounds.
- Provides option to start from midway through a session.

---

## Tech Stack
- **Python 3.12**
- **pygame** (for sound playing)
- **gTTS** (Google Text-to-Speech API)
- **IPython.display** (optional visual support)

---

## Screenshots/Diagrams

![image](https://github.com/user-attachments/assets/e20c6bb6-0ad8-4e69-b2d4-7d91f9226134)

![image](https://github.com/user-attachments/assets/fd659823-a328-43e6-a123-d5e5d1eb395b)

![image](https://github.com/user-attachments/assets/3f2c936b-0f50-497a-8cd3-83d0ddb32f17)

![image](https://github.com/user-attachments/assets/4bec201c-e2a2-4597-992c-5a7ae46587ec)

![image](https://github.com/user-attachments/assets/5729bb87-2b9e-46d8-a5bd-901d1c003431)


## How to Install/Run

### 1. Clone the Repository

```bash
git clone https://github.com/yourusername/stretch-timer-app.git
cd stretch-timer-app

```

### 2. Set up a Python Virtual Environment

```bash
python3 -m venv myvenv
source myvenv/bin/activate

```

### 3. Install Requirements

```bash
pip install pygame gTTS

```

### 4. Run the App

```bash
python TIMERAPP.py

```

---

## Features

- Create full custom stretch sequences (hips, torso, arms, pointe, reclining, deep stretches, etc.)
- Adjust stretch durations manually
- Mid-session starting option
- Text-to-Speech (TTS) audio guidance
- Alternating harp sound notifications
- Midpoint encouragement ("You're halfway done!")

---

## Future Improvements

- GUI (Graphical User Interface) version (Tkinter, PyQt, etc.)
- Save/load user-created sequences
- Progress bar or countdown timer visualization
- Multiple language support
- Stretch image display (re-enable PIL/Image)
- Sound customization by user
