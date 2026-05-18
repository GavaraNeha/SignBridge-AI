# SignBridge AI 🤟
### Real-Time Sign Language Interpreter for Inclusive Communication

![SignBridge AI](https://img.shields.io/badge/AI-Sign%20Language%20Interpreter-purple)
![MediaPipe](https://img.shields.io/badge/MediaPipe-Hands-blue)
![Status](https://img.shields.io/badge/Status-Live-green)

## 🔗 Live Demo
👉 [https://gleeful-trifle-007b00.netlify.app](https://gleeful-trifle-007b00.netlify.app)

---

## 🎯 Problem Statement
Millions of deaf and hard-of-hearing individuals use sign language as their primary 
mode of communication. However, most people around them — in hospitals, schools, 
and public spaces — cannot understand sign language. This creates serious 
communication barriers in everyday life.

---

## 💡 Our Solution
SignBridge AI is a browser-based, AI-powered application that:
- Detects hand gestures in real time using your webcam
- Recognizes ASL (American Sign Language) letters A–Z
- Converts signs into text and spoken speech
- Requires zero installation — works directly in any browser

---

## ✨ Features

| Feature | Description |
|---|---|
| 🖐️ Real-Time Detection | MediaPipe 21-point hand landmark tracking at 30fps |
| 🔤 A–Z Recognition | Full ASL alphabet with rule-based + trained classifier |
| 🔵 Hold-to-Confirm Arc | Visual arc fills as sign is held — prevents false detections |
| 🏷️ Candidate Signs | Shows top sign candidates with confidence scores |
| 🔊 Text to Speech | Speak recognized sentences aloud via Web Speech API |
| 🧩 Sentence Builder | Build full sentences from individual signs |
| 🌐 Multi-Language | Translate to Telugu, Hindi, Spanish, French, Arabic & more |
| 📋 History & CSV Export | Save all recognized signs with timestamps |
| 📖 Learn Mode | 97+ lessons with XP system and live camera practice |
| 🧠 Self-Training | Correct wrong detections — model adapts to your hand |
| 🚨 Emergency SOS | One-tap emergency voice alerts |
| 🌙 Dark / Light Mode | Full theme support |

---

## 🛠️ Tech Stack

- **MediaPipe Hands** — Hand landmark detection
- **Web Speech API** — Text to speech
- **MyMemory API** — Multi-language translation
- **Claude AI (Anthropic)** — AI sentence formation from signs
- **Vanilla JS / HTML5 / CSS3** — Frontend
- **Netlify** — Deployment

---

## 🚀 How to Run Locally

1. Download `index.html`
2. Open it in **Chrome** or **Edge**
3. Allow camera access when prompted
4. Go to **Communicate** → Click **Start Camera**
5. Show ASL signs to the camera

> ⚠️ Camera requires HTTPS or localhost. Use a local server if needed:
> ```
> python -m http.server 8080
> ```
> Then open: `http://localhost:8080`

---

## 📸 How It Works

1. **Camera captures** your hand in real time
2. **MediaPipe** detects 21 hand landmarks (joints)
3. **Classifier** matches landmark geometry to ASL letters
4. **Arc fills** as you hold the sign steady (~1 second)
5. **Letter added** to sentence builder
6. **AI forms** a natural sentence from detected letters
7. **Speech API** reads the sentence aloud

---

## 🌍 Real-World Impact

- 🏥 Hospitals — deaf patients communicating with doctors
- 🏫 Schools — inclusive classrooms
- 🏢 Public services — accessible government offices
- 👨‍👩‍👧 Families — communication with deaf family members

---

## 👥 Team SignBridge

| Name | Role |
|---|---|
| Gavara Neha | AI & Frontend Lead |
| Gundu Iswarya Lakshmi | UI/UX Design |
| Ganesam Parthasaradhi Reddy | Model & Logic |
| Vanka Namratha Amanigreeva | Testing & Documentation |

**Institution:** Aditya University

---

## 🏆 Hackathon Submission

- **Event:** FlowZint AI Hackathon 2026
- **Track:** Open Innovation
- **Category:** AI-Powered Accessibility Tool

---

## 📄 License
MIT License — free to use and build upon.
