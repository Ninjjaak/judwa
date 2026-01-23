# 🌌 SGSentinel – Autonomous AI Street Surveillance Drone

<p align="center">
  <img src="https://img.shields.io/badge/AI%20Powered-%23FF3366?style=for-the-badge&logo=ai&logoColor=white" alt="AI Powered">
  <img src="https://img.shields.io/badge/Night%20Vision-%2300D4FF?style=for-the-badge&logo=eye&logoColor=black" alt="Night Vision">
  <img src="https://img.shields.io/badge/Onboard%20YOLO-%237B2CBF?style=for-the-badge&logo=brain&logoColor=white" alt="YOLO">
  <img src="https://img.shields.io/badge/Defense%20Tech-%23FF6B6B?style=for-the-badge&logo=shield&logoColor=white" alt="Defense">
</p>

<p align="center">
  <strong>Project #1</strong> of 9 defense & military-focused projects to be completed by end of Polytechnic Year 3
</p>

---

## 🎯 Project Goal

Build a **low-cost, student-accessible** autonomous surveillance drone using off-the-shelf hardware + edge AI  
Core missions:

- **Crime deterrence** in urban / HDB / residential streets
- Reliable **24/7 night-time monitoring**
- Conceptual foundation for future **military / wartime applications**  
  → low-observable reconnaissance, early-warning perimeter patrol

---

## ✨ Current Features

- 🔄 Autonomous linear patrol (forward → backward loop)
- 🌙 Real-time night vision / low-light camera feed
- 🧠 Onboard object & person detection using **YOLOv8**
- ⚡ Active deterrence: LED strobe flash + audible warning buzzer
- 📸 Timestamped detection logging + screenshot capture

---

## 🛠 Tech Stack

| Layer                | Technology / Tool                              | Theme Colour |
|----------------------|------------------------------------------------|--------------|
| Drone base           | DJI Mini 4 Pro / Ryze Tello EDU                | <span style="color:#00D4FF">Cyan</span> |
| Night vision         | Built-in low-light + optional IR/thermal add-on| <span style="color:#00D4FF">Neon Cyan</span> |
| Onboard compute      | Raspberry Pi Zero 2 W                          | <span style="color:#7B2CBF">Purple</span> |
| Programming          | Python 3                                       | <span style="color:#FFD93D">Yellow</span> |
| Computer Vision      | OpenCV                                         | <span style="color:#FF3366">Magenta</span> |
| Object Detection     | YOLOv8 (Ultralytics)                           | <span style="color:#7B2CBF">Electric Purple</span> |
| Drone control        | DJI SDK / Tello SDK                            | <span style="color:#00D4FF">Cyan</span> |
| Deterrence hardware  | WS2812 RGB LEDs + piezo buzzer via GPIO        | <span style="color:#FF6B6B">Alert Red</span> |

---

## 📊 Project Progress (Jan 2026)

```mermaid
gantt
    title SGSentinel Development Timeline
    dateFormat  YYYY-MM
    axisFormat %b %Y
    section Phase 1
    Hardware selection & purchase   :done, 2026-01, 2026-02
    Basic flight + camera test      :active, 2026-02, 14d
    Path following (forward-back)   :         2026-02, 14d
    Night vision processing         :         2026-03, 14d
    AI detection (YOLO integration) :         2026-03, 21d
    Deterrence activation           :         2026-03, 14d
    Outdoor testing & tuning        :         2026-04, 21d
    Documentation + demo video      :         2026-04, 14d
