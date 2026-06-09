# 🏥 InfantGuard
### A Point-of-Care Pneumonia Early Warning System for Rural Child Survival



![Status](https://img.shields.io/badge/Status-Active-green)




![Competition](https://img.shields.io/badge/Competitions%20Won-2%20🏆-gold)




![University](https://img.shields.io/badge/University-LAUTECH-blue)



---

## 📌 About InfantGuard
InfantGuard is a portable, low-cost, offline diagnostic device designed to empower Community Health Extension Workers (CHEWs) with accurate, real-time assessment of respiratory distress in children aged 1–5 years in rural Nigeria.

---

## 🚨 The Problem
- Pneumonia kills **140,000 children annually** in Nigeria
- Over **60% of Nigeria's population** lives in rural areas
- Fewer than **30% of PHCs** have functional diagnostic tools
- Health workers rely on **manual breath counting** — inaccurate and unreliable
- **Silent hypoxia** goes undetected until it becomes life-threatening

---

## 💡 Our Solution
InfantGuard combines sensor fusion and WHO-aligned decision logic to deliver instant triage decisions:

| SpO₂ Reading | Status | Alert |
|---|---|---|
| ≥ 95% | 🟢 NORMAL | Green LED |
| 92% – 94% | 🟡 MONITOR | Yellow LED |
| < 92% | 🔴 REFER NOW | Red LED + Buzzer |

---

## ⚙️ Hardware Components
- ESP32 Development Board
- MAX30102 Pulse Oximeter Sensor
- INMP441 MEMS Omnidirectional Microphone
- SSD1306 OLED Display
- Active Buzzer
- Green / Yellow / Red LEDs
- LiPo Battery + TP4056 Charger Module
- MT3608 Boost Converter
- Perfboard (Permanent Circuit)

---

## 🧠 How It Works
1. Health worker places child's finger on MAX30102 sensor
2. INMP441 microphone captures breath sounds near child's nose
3. ESP32 processes SpO₂ and respiratory rate in real time
4. WHO iCCM thresholds applied automatically
5. Result displayed on OLED — correct LED lights up instantly
6. Buzzer sounds if REFER NOW status detected

---

## 📁 Repository Contents
- `/code` — Arduino/ESP32 source code
- `/diagrams` — Circuit wiring diagrams
- `/docs` — Project proposal and pitch deck
- `/photos` — Prototype photos

---

## 👥 Team Excel
| Name | Department | Role |
|---|---|---|
| **Goodness Oladele** | Civil Engineering | Embedded Systems Lead |
| **Mayowa Rojaiye** | Surveying & Geoinformatics | Data Analysis |
| **Shekinah Okanlawon** | Human Anatomy | AI & ML |

**University:** Ladoke Akintola University of Technology (LAUTECH), Ogbomosho, Nigeria

---

## 🏆 Competition Record
- 🥇 1st Place — Competition 1 (2026)
- 🥇 1st Place — Competition 2 (2026)

---

## 🎯 Target Impact
- Reduce preventable pneumonia deaths by **40%** in target rural clusters within 2 years
- Deploy across **10 Primary Health Care centers** in rural Nigeria
- Equip **70,000+ CHEWs** across Nigeria with objective diagnostic support

---

## 📄 License
MIT License © Team Excel 2026# InfantGuard-project
A Point-of-Care Pneumonia Early Warning System for Rural Child Survival
