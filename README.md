# NeuroFlight – Quad-Vision 1.0  
> *AI-ready FPV drone platform for modular experimentation and computer-vision research.*

---

## Overview

**NeuroFlight / Quad-Vision 1.0** is an experimental, open-source FPV drone platform  
designed for **AI-based real-time vision**, **telemetry**.  

The goal is to build a compact, lightweight 5″ quadcopter capable of running  
**YOLO-based object detection** on an onboard **Raspberry Pi Zero 2 W**,  
while remaining fully flyable through a **Betaflight** flight controller.  
It serves as a research-friendly edge-compute platform for combining classic FPV flight with AI inference.  
Altough its frame and motors allow for high speed maneuvers, this UAV shines the most during cruising,
using its onboard Pi camera modul to analyse and recognise objects.

---

## Key Features

- 🧱 **Modular hardware design:** replaceable AI, camera, and power modules  
- 🎥 **HD FPV system:** Walksnail Avatar HD Nano V3  
- 🧮 **Edge AI:** Raspberry Pi Zero 2 W + Camera Module 3 (wide or normal)  
- 🧭 **Sensor suite:** u-blox M10 GNSS, ICM-42688-P IMU, DPS310 barometer  
- ⚙️ **Flight controller:** GEPRC / Matek F405 HD V2 (Betaflight 4.5)  
- 🔋 **Power:** 4S LiPo 1500 mAh
- 🔧 **AI pipeline:** YOLO-n Tiny @ 416 p (20–30 FPS on Pi Zero 2 W)

---

## Current Status (2025 November)

| Module | Status | Notes |
|---------|:------:|-------|
| Frame / assembly | ⚙️ | 5″ carbon frame + 3D-printed body parts done, landing gears in progress |
| Electronics | ✅ | Done |
| Edge Image Recognition (Pi Zero 2 W + Cam) | ⚙️ | getting started with YOLO |
| Power distribution / UBEC | ⚙️ | after Pi is finished |
| AI OSD overlay | ⚙️ | in concept, will be developed in future |

---

## List of Components

- Frame: TBS Source One 5" Frame V5.1
- Motors: T-motor Pacer V2 P2207 1750KV Freestyle Motor
- Props: HQProp ETHIX P3B Peanut Butter & Jelly 5.1x3x2
- Stack (FC & ESC): Kakute F722 Tekko32 F4 50A Stack By Holybro - Refurbished
- Digital camera: Avatar HD Nano Kit V3 By Walksnail
- Receiver: ELRS 2.4G RP1 V2 Nano Receiver By RadioMaster
- Controller: RadioMaster - Zorro-ELRS
- FPV goggles: Avatar HD Goggles L By Walksnail
- GPS and compass modul: GNSS & Compass M10Q-5883 By Matek
- Battery: CNHL Black Series V2.0 - 1500mAh 4S 130C
- Current limiter (with a fuse): TBS Smoke Stopper
- Others: XT60 cable, noise filtering capacitor (35V 1000uF)

Weight: ~367g/542g (AUW)  
*Weight WILL CHANGE, after the landing gears and Pi are added.*

## Contact  
Feel free to contact me via email or Instagram, if you have any suggestions, or just want to take part in and/or follow this project.  
Email: contact@neuroflight.hu
Instagram: @neuroflight_
