# 🏢 UrbanRise Connect — Smart Community Management System

[![Status](https://img.shields.io/badge/Status-Live%20%26%20Deployed-brightgreen)]()
[![AI](https://img.shields.io/badge/AI-Claude%20API-blueviolet)]()
[![WhatsApp](https://img.shields.io/badge/Alerts-WhatsApp%20Business%20API-25D366)]()
[![Built In](https://img.shields.io/badge/Built%20In-7%20Days-orange)]()

> UrbanRise is a large high-rise residential community with 500+ flats.
> They had zero digital system for visitors, parking, maids, or couriers.
> We built and deployed a complete AI-powered solution in just 7 days.

---

 🔴 The Problem We Solved

Before our system, this is what was happening at UrbanRise every single day:

- Security guards were writing visitor names **by hand in a paper register**
- Residents had **no idea** when their courier arrived — packages were stolen
- Maids and domestic workers entered and exited with **zero record**
- Cars were parked in wrong slots with **no way to notify the owner**
- Pre-approving a guest meant **calling the security guard on his personal number**

**This was a 500+ flat community running on paper and phone calls in 2024.**

We fixed all of it.

---

 * What We Built

 1. Visitor Pre-Approval System
- Resident opens the app and types their guest's name and phone number
- Guest automatically receives a **one-time QR code on WhatsApp**
- At the gate the guard scans the QR — entry is logged instantly
- Resident gets a WhatsApp message: *"Your visitor has arrived at Gate 2"*
- No more phone calls to the security guard

 2. Courier Boy Photo Alert
- Camera at the delivery entrance is connected to our AI model
- The moment a delivery person walks in, the system **captures their photo**
- Resident gets a **WhatsApp message with the photo attached** instantly
- *"A delivery has arrived for your flat. Courier photo attached."*
- Zero missed deliveries. Zero stolen packages.

 3. Maid & Domestic Help Tracking
- Every maid is registered once with their photo and flat number
- Face recognition automatically **logs every entry and exit**
- Residents can see the full weekly log on their app
- If a maid enters but never exits — the system **sends an alert automatically**

 4. Smart Parking with Alarm & WhatsApp Alert
- Every parking slot has an **ultrasonic sensor** installed
- If someone parks in a slot that is not theirs:
  - A **buzzer alarm triggers** at the parking bay immediately
  - The registered slot owner gets a **WhatsApp message** with bay number and time
  - The incident is logged in the admin dashboard
- Residents can check real-time parking availability from their phone

---

* We Built This in 7 Days

| Day | What We Did |
|-----|-------------|
| Day 1 | Visited UrbanRise. Understood every problem. Designed full system architecture. Split work between teammates. |
| Day 2 | Set up Raspberry Pi nodes. Connected ultrasonic sensors and cameras at parking bays and gates. |
| Day 3 | Built the backend — FastAPI, PostgreSQL database, Kafka message queue, Docker setup. |
| Day 4 | Integrated YOLOv8 for person detection at gates. Integrated DeepFace for maid face recognition. |
| Day 5 | Connected Claude AI API for smart natural language alerts. Integrated WhatsApp Business API. |
| Day 6 | Built the React dashboard — live parking map, visitor logs, maid tracking, courier photo panel. |
| Day 7 | Deployed on live server. End-to-end testing at the actual community. Fixed bugs. Went live. ✅ |

---

* System Architecture

We used a **Microservices Architecture** — each feature runs as its own independent service.


* AI Models & Technologies Used

| Model / Tool | What It Does In Our System |
|---|---|
| **YOLOv8** | Detects people and vehicles at building gates in real time |
| **DeepFace** | Recognises maid faces for automatic entry/exit logging |
| **Claude API** | Generates human-friendly WhatsApp alert messages |
| **OpenCV** | Processes live camera feed and captures courier photos |
| **WhatsApp Business API** | Delivers all alerts and photos to residents instantly |
| **Custom LSTM Model** | Predicts peak visitor hours to help schedule security guards |

---

* Full Tech Stack

| Layer | Technology Used |
|-------|----------------|
| Frontend | React.js, Tailwind CSS |
| Mobile App | React Native |
| Backend | Python FastAPI, Node.js |
| AI & Vision | YOLOv8, DeepFace, OpenCV, Claude API |
| Database | PostgreSQL, Redis, TimescaleDB |
| Hardware | Raspberry Pi 4, Ultrasonic Sensors, IR Sensors, Pi Camera Module |
| Messaging | WhatsApp Business API, Firebase Push Notifications |
| DevOps | Docker, Docker Compose, Nginx, GitHub Actions |
| API Gateway | Kong |
| Message Queue | Apache Kafka |

---

* Real Impact After Deployment

| What We Measured | Before | After |
|---|---|---|
| Visitor entry time | 3 to 5 minutes | 18 seconds |
| Parking misuse incidents | 12 per week | 0 per week |
| Courier complaints | 4 per month | 0 per month |
| Guard manual errors per day | ~30 mistakes | 0 |
| Resident satisfaction score | No system | 4.8 out of 5 |

---

* Screenshots

* Dashboard
![Dashboard](assets/screenshots/dashboard.png)

* Parking Sensor Setup
![Parking](assets/screenshots/parking.png)

* WhatsApp Alerts
![Alerts](assets/screenshots/whatsapp.png)

* Visitor Gate System
![Gate](assets/screenshots/gate.png)

*Team Working
![Team](assets/screenshots/team.png)

---

* Team

| Name | Role |
|------|------|
| Smithal | AI Integration, Claude API, System Architecture |
| harsha | IoT Hardware, Sensor Firmware, Raspberry Pi Setup |
| charan | Frontend Dashboard, React Native Mobile App |

---

* Currently Live

This system is **deployed and actively running** at UrbanRise Community.
Hosting: Ubuntu VPS · Docker · Cloudflare SSL · Nginx

---

* License

MIT License — open to use and build upon.

