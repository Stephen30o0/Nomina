# Nomina

## Description
Nomina is a mobile **Augmented Reality (AR) language learning application** that helps users learn new languages by connecting words directly to real-world objects. By pointing a smartphone camera at everyday objects, users can instantly view the object’s name in a selected language along with pronunciation support, making language learning more contextual, intuitive, and engaging.

Nomina focuses on **active learning through real-world interaction**, allowing learners to associate vocabulary with physical objects instead of relying on memorization-based methods. This repository contains the **initial MVP prototype** designed to demonstrate core AR interaction, user interface design, and learning flow.

---

## Project Track
**AR/VR Track**

---

## Project Scope (MVP)
This version of Nomina represents an early-stage prototype and focuses on:
- Augmented reality interaction using a mobile device camera  
- Real-time object labeling in a selected language  
- Pronunciation playback for scanned objects  
- Simple vocabulary saving and review  
- Clear and minimal user interface optimized for AR  

Advanced features such as gamification, analytics, and backend services are outside the scope of this MVP.

---

## User Flow
1. User launches the application  
2. User selects a target language  
3. The camera opens in AR scanning mode  
4. User points the camera at a real-world object  
5. The object is detected and highlighted  
6. An AR label appears showing the object name in the selected language  
7. User taps the audio icon to hear pronunciation  
8. User can save the word for later review  
9. Saved words can be viewed in the vocabulary list  

---

## Design & Prototype
The user interface and interaction flow were designed using **Figma**, with a focus on:
- Camera-first layout  
- Minimal and non-intrusive AR overlays  
- Clear navigation and interaction feedback  
- Accessibility and readability over a live camera feed  

### Design Files
- Figma Prototype: *(insert Figma link here)*  
- Screenshots: `/designs/screenshots/`  

---

## Assets Used
- Camera frame and scan reticle  
- Object highlight overlay  
- Floating AR text labels  
- Audio playback icon  
- Save icon and navigation icons  

These assets support clarity, usability, and effective AR interaction without overwhelming the user.

---

## Hardware Integration
- **Device:** Smartphone (Android / iOS)  
- **Input:** Touchscreen and rear camera  
- **Output:** Screen display and audio speaker  
- **Platform:** Mobile AR (ARCore / ARKit – conceptual)  

No external AR hardware or headsets are required.

---

## Development Tools
- **Design:** Figma  
- **Proposed Implementation:** Unity + AR Foundation  
- **Target Platforms:** Android and iOS  

---

## Deployment Plan
At this stage, Nomina is presented as a **design prototype** and demo.

### Prototype Deployment
- Interactive Figma prototype  
- Screen-recorded demo video  

### Future Deployment
- Unity-based mobile application  
- Android APK for pilot testing  
- iOS TestFlight for limited user testing  

---

## Video Demo
A short demo video (5–10 minutes) demonstrates:
- App navigation  
- Object scanning  
- AR label appearance  
- Pronunciation interaction  
- Vocabulary saving and review  

📹 *(Insert video link here)*

---

## Repository Structure
```text
Nomina/
│
├── README.md
├── designs/
│   ├── figma-mockups/
│   ├── screenshots/
│
├── demo/
│   └── video-demo.mp4
│
└── docs/
    └── deployment-plan.md
