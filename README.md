# 6-Dot-Haptic-Grade-1
Mobile Application: Two-Way Communication &amp; Safety System for Deafblind Individuals

## 🏆 Awards & Recognition

This application was developed as a comprehensive Final Year Project for the Faculty of Information Technology (FoIT) at City University Malaysia, where it received top honors for its technical architecture and impact on accessibility:

* 🥇 **1st Place - Best Project Award** (Project 2 - Final Implementation)
* 🏅 **4th Place - Excellent Award** (Project 1 - System Design & Architecture)

---

![Flutter]([https://img.shields.io/badge/Flutter-%2302569B.svg?style=for-the-badge&logo=Flutter&logoColor=white](https://icon-icons.com/icon/flutter/130936))
![Firebase]([https://img.shields.io/badge/firebase-%23039BE5.svg?style=for-the-badge&logo=firebase](https://www.figma.com/community/file/1385937632199027400/firebase))

**Globally, up to 0.2% of the population experiences some form of dual sensory loss**. Current communication tools are often inaccessible, relying on bulky and costly external hardware. This project bridges that gap by providing a mobile-based Relative Braille Input and Two-Way Tactile Translation System to eliminate the need for bulky external hardware.

---

## 📱 About The Project

**6-Dot Haptic** is an Android and iOS application that provides high-speed, proximate communication and personal safety to deafblind users. Developed using the Agile methodology and the Flutter framework, the app operates on a two-interface model: Deafblind Mode and Caregiver Mode. 

This project directly champions the United Nations Sustainable Development Goals:
* 🩺 **SDG 3:** Good Health and Well-being
* 📚 **SDG 4:** Quality Education
* ⚖️ **SDG 10:** Reduced Inequalities

---

### ✨ Core Features

### 🖐️ 1. Relative 6-Dot Braille Input
I replaced standard static keyboards with a gesture-based "Relative 6-Dot Braille Input" system. Virtual Braille dots dynamically "float" to match the user's natural finger placement, allowing for fast, simultaneous multi-finger typing without visual cues.

### 📳 2. Two-Way Tactile Translation
The system provides zero-delay translation. It converts Grade 1 Braille inputs into text for the sighted caregiver. When the caregiver replies with text, the app translates it into a "Custom Haptic Pulse Code" delivered to the deafblind user via precise Morse-based vibrations.

### 🚨 3. Emergency Location Sharing (ELS)
Safety is integrated directly into the input canvas. A continuous 6-finger hold triggers the ELS protocol. The app instantly fetches real-time GPS coordinates and pushes a full-screen Red Alert and Google Maps Deep Link directly to the linked caregiver. The deafblind user receives a distinct three-pulse haptic confirmation that help is on the way.

### 🔗 4. Linked Account Architecture
To prevent accidental lockouts and ensure secure data routing, caregivers can establish a "Linked Account" using sighted-assisted email verification. This automatically authorizes the caregiver to receive ELS alerts and manage credential recovery.

### 📖 5. Caregiver Learning Modules
Accessibility starts with education. The Caregiver interface includes interactive "Learn, Quiz, and Write" modules. Caregivers can tap Braille keys to feel the corresponding Morse haptic vibrations, bridging the gap between visual learning and physical tactile communication.

---

## 🛠 Tech Stack

* **Frontend:** Flutter SDK (Dart) for high-performance, cross-platform UI.
* **Backend:** Firebase Authentication & Cloud Firestore (NoSQL) for real-time ELS syncing and secure account management.
* **Hardware Integrations:**
  * `Geolocator` / Android Location API for precise SOS tracking.
  * Native Haptic Feedback APIs for custom Morse vibration sequencing.
  * `url_launcher` / Google Maps API for hardware-level navigation handoffs.
* **Architecture:** Hybrid MVVM Model with asynchronous Publish-Subscribe listeners.

---

## 🚀 Future Roadmap

Based on user acceptance testing and technical evaluations, future development will focus on:
* **Offline ELS SMS Fallback:** Automatically rerouting ELS alerts via standard cellular SMS if the device has no internet connection.
* **Grade 2 Braille Integration:** Implementing a contracted Braille translation engine to increase communication speed for advanced users.
* **Customizable Haptic Settings:** Allowing users to manually adjust the speed and interval gaps of the Morse pulses for better personalization.

---

## 👨‍💻 Author

**Tamil Selvi A/P Sandiran**  
Bachelor of Computer Science (Software Engineering) (Hons)  
City University Malaysia  
