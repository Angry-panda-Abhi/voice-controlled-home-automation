# 🏠 Voice-Controlled Home Automation using Raspberry Pi

This project implements a **voice-controlled home automation system** that allows users to control everyday electrical appliances such as lights and fans using **simple voice commands**.  
It was developed as part of the **Computer System Organization and Architecture (CSE-201)** course under the guidance of **Dr. Prasenjit Chanak**.

---

## 👨‍💻 Team Members
- Aaroh Rai (24075001)
- **Abhishek Kumar** (24075003)
- Ayush Kumar Barnwal (24075014)
- Kanishk Kumar Gupta (24075042)
- Ankit Kumar (24074010)

---

## 🔍 Project Overview
The project uses a **Raspberry Pi** as the central processing unit and integrates:
- **Google Speech-to-Text API** for voice recognition  
- **Google Text-to-Speech (gTTS)** for voice responses  
- **Relay module** for controlling electrical appliances via GPIO pins  
- A custom-built voice assistant named **Manvi**, capable of understanding both **English and Hindi**  

This setup allows hands-free control of home devices, promoting comfort, convenience, and accessibility — especially for elderly or physically challenged users.

---

## 💡 Novelty
Unlike commercial smart assistants (Alexa, Google Home), this project:
- Works **without external cloud platforms**, ensuring **privacy and data security**
- Offers **low-cost implementation** using affordable hardware components
- Enables **voice control from a distance** via Bluetooth-enabled microphones or earphones
- Is **customizable and scalable**, allowing integration of additional devices and sensors

---

## ⚙️ Hardware Components
- Raspberry Pi 4B (or similar)
- 2-Channel Relay Module
- Microphone
- Speaker / Bluetooth earphones
- Bulb and Fan (AC appliances)
- Jumper wires and power supply

---

## 🧠 Software Components
- **Python 3**
- **SpeechRecognition** library
- **gTTS (Google Text-to-Speech)**
- **Raspberry Pi OS (Linux-based)**
- **GPIO Zero / RPi.GPIO** for controlling relays

---

## 🧩 Working Principle
1. The system continuously listens for voice input through a microphone.  
2. Speech is converted into text using Google Speech API.  
3. The recognized command (e.g., “turn on light”) is matched against predefined instructions.  
4. Corresponding GPIO pin activates the relay to control the connected appliance.  
5. Assistant **Manvi** provides a spoken confirmation of the action.  

Example Commands:
- “Turn on light” → Light ON  
- “Turn off fan” → Fan OFF  
- “Turn on light and fan” → Both ON  

---

## 📈 Results
- Reliable response in low-noise environments  
- Average command execution time: **3–4 seconds**  
- Successfully supports commands in **both English and Hindi**  
- Easily expandable to include more devices or integrate with mobile/IoT apps  

---

## 🚀 Future Enhancements
- Mobile app integration for remote control  
- Cloud-based IoT dashboard for status monitoring  
- Addition of sensors (temperature, motion, etc.)
- Offline speech recognition using Vosk or similar libraries  

---

## 🏁 Conclusion
This project demonstrates how **AI and IoT integration** can create affordable, inclusive, and privacy-friendly smart home solutions.  
By using open-source technologies and simple hardware, we bring automation within reach for everyone.

---

## 🧰 Installation & Setup

1. **Clone the repository:**
   ```bash
   git clone https://github.com/<your-username>/voice-controlled-home-automation.git
   cd voice-controlled-home-automation
