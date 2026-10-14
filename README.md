<div align="center">

# Sujitha C

### Full-Stack & AI Developer · B.Tech Information Technology

Building real-time web apps, AI-assisted tools and IoT systems with **React, FastAPI and ESP32**.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/sujitha-chandrasekharan-64636233a/)
[![Email](https://img.shields.io/badge/Email-Contact-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:sujitha.c.it@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-sujithac--IT-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/sujithac-IT)

</div>

---

## About

I'm a B.Tech Information Technology student at **Sri Shakthi Institute of Engineering and Technology**. I build end-to-end projects: a web front end, an API behind it, a database, and often hardware or AI in the loop. Most of my work is in teams, including hackathon-style builds, and I document it so others can run it.

**Open to internships and entry-level roles** in full-stack development, AI-enabled products and IoT.

---

## Featured Projects

### [MedTrust AI](https://github.com/sujithac-IT/medtrustAI): AI case sheets from live teleconsultations
A teleconsultation platform for teaching hospitals. Doctors, students and patients meet over video, speech is transcribed live, and Gemini drafts a 17-section clinical case sheet that the doctor reviews, edits and signs. Signed records are locked.

- **Real-time:** WebRTC peer-to-peer video, WebSocket signalling, lobby and live captions
- **Backend:** FastAPI, JWT auth with role guards (doctor / student / patient), rate-limited logins, automatic SQLite schema migrations
- **AI:** Gemini structured extraction, with a local fallback so the app works without an API key
- **Quality:** pytest suite covering the API, the extractor and real-socket realtime tests; Docker Compose setup; written [PRD, API contract and audit](https://github.com/sujithac-IT/medtrustAI/tree/main/docs)

`React` `Vite` `FastAPI` `WebRTC` `WebSockets` `SQLite` `Gemini` `Docker`

---

### [EV Sense (Digital Twin)](https://github.com/sujithac-IT/DigitalTwin): live digital twin of an EV battery
An ESP32 sensor rig measures a 12 V pack and posts readings to a FastAPI service. A React app mirrors the pack live: charge, voltage, current, temperature, position and the nearest charging stations. [Watch the 60-second walkthrough](https://github.com/sujithac-IT/DigitalTwin/blob/main/brag-output/brag.mp4).

- **Firmware:** voltage divider, ACS712 current sensor, DHT11, GPS and SIM800L; sends an SMS with the GPS position when the pack passes 35 °C
- **Backend:** FastAPI, SQLAlchemy, JWT auth, Dockerfile, Render deployment config
- **Web app:** three.js scroll-driven car model, Leaflet map with nearest chargers from OpenStreetMap data
- **Honest docs:** the README lists known limitations and the full API

`ESP32` `C++` `FastAPI` `React` `TypeScript` `three.js` `Leaflet` `Docker`

---

### [Optra AI](https://github.com/sujithac-IT/Optra-AI): AI career platform for students
Brings internships, jobs, hackathons and scholarships into one place, with personalised recommendations, resume analysis and learning roadmaps. Built with a teammate for **Google Gen AI Academy APAC**.

`Next.js` `TypeScript` `Tailwind CSS` `Node.js` `PostgreSQL` `Gemini API` `Firebase Auth`

---

### [Decision Atlas](https://github.com/sujithac-IT/decision-atlas): turning citizen feedback into development priorities
A multilingual public-development platform concept: citizens report needs by voice, text, image or location, and AI helps officials cluster issues, see demand hotspots and rank projects with explainable reasoning.

`React` `TypeScript` `Vite` `Tailwind CSS` `FastAPI` `Firebase` `Docker`

---

### [Smart Sensor Glove](https://github.com/sujithac-IT/smart-sensor-glove): gesture-to-voice for speech-impaired users
A low-cost wearable. Flex sensors feed an ESP32, a Python program recognises predefined gestures over serial, and speech is generated in real time.

`ESP32` `Arduino` `Python` `PySerial` `pyttsx3`

---

## Skills

<div align="center">
  <img src="https://skillicons.dev/icons?i=py,ts,js,cpp,react,nextjs,vite,tailwind,nodejs,fastapi,postgres,sqlite,firebase,docker,git,github,vercel,arduino,threejs&perline=10" alt="Skill icons" />
</div>

<br/>

| Area | What I've used it for |
| :--- | :--- |
| **Languages** | Python, TypeScript, JavaScript, C++ (ESP32 firmware), SQL |
| **Frontend** | React, Next.js, Vite, Tailwind CSS, three.js, Leaflet |
| **Backend & APIs** | FastAPI, Node.js, REST, WebSockets, JWT authentication, SQLAlchemy |
| **Real-time & IoT** | WebRTC, ESP32, sensors (current, voltage, temperature, GPS), serial communication |
| **AI integration** | Gemini API for structured extraction, with graceful fallback when unavailable |
| **Data** | PostgreSQL, SQLite |
| **Tooling** | Git, GitHub, Docker and Docker Compose, Firebase Auth, Render, Vercel, pytest |

---

## Currently

- Building more full-stack projects with real-time features and AI integration
- Improving tests and deployment setup across my repositories
- Looking for an internship or entry-level role where I can ship features in a team

---

<div align="center">

**Let's connect:** [LinkedIn](https://www.linkedin.com/in/sujitha-chandrasekharan-64636233a/) · [Email](mailto:sujitha.c.it@gmail.com)

</div>
