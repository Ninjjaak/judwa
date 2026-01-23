# SGSentinel - Autonomous Street Surveillance Drone

AI-powered surveillance drone that patrols a street segment forward and backward, uses night vision camera + onboard AI to detect suspicious activity and actively deter crime.

**First project** of long-term plan → build **9 defense & military related projects** by end of Poly Year 3.

<br>

## Project Goal

Create a **low-cost, student-buildable** autonomous surveillance system using off-the-shelf drone + simple AI  
Main purposes:
- Crime deterrence in urban/residential streets
- Night-time monitoring capability
- Future military / wartime extension → low-signature reconnaissance / early warning

<br>

## Current Features

- Autonomous forward-backward street patrol
- Real-time night vision camera feed
- Onboard object detection using YOLO (people / suspicious objects)
- Basic deterrence system (LED flash + buzzer warning)
- Simple logging of detections (time + screenshot)

<br>

## Tech Stack

| Layer              | Technology / Tool                                 |
|--------------------|---------------------------------------------------|
| Drone base         | DJI Mini 4 Pro / Ryze Tello EDU                   |
| Night vision       | Built-in low-light + optional IR/thermal module   |
| Onboard computer   | Raspberry Pi Zero 2 W                             |
| Programming        | Python                                            |
| Computer Vision    | OpenCV                                            |
| Object Detection   | YOLOv8                                            |
| Drone control      | DJI SDK / DJI Python API / Tello SDK              |
| Deterrence         | WS2812 LEDs + piezo buzzer via GPIO               |

<br>

## Project Status

Phase          | Status     | Last Updated
---------------|------------|-----------------
Hardware selection & purchase   |In progress | Jan 2026
Basic flight + camera test      | ────────   |
Path following (forward-back)   | ────────   |
Night vision processing         | ────────   |
AI detection (YOLO)             | ────────   |
Deterrence activation           | ────────   |
Outdoor testing & tuning        | Not started   |
Documentation + demo video      | Not started   |

<br>
