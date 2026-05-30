<div align="center">

# 🚀 AROHHAN
**AI-Powered Autonomous Safety & Emergency Response Ecosystem**

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](http://makeapullrequest.com)
[![React](https://img.shields.io/badge/Frontend-React%20%2B%20Vite-61DAFB?logo=react&logoColor=white)](https://reactjs.org/)
[![Node.js](https://img.shields.io/badge/Backend-Node.js-339933?logo=nodedotjs&logoColor=white)](https://nodejs.org/)
[![Python](https://img.shields.io/badge/AI_Engine-Python-3776AB?logo=python&logoColor=white)](https://python.org/)
[![Hardware](https://img.shields.io/badge/IoT-ESP32%20%2B%20Arduino-00979D?logo=arduino&logoColor=white)](https://arduino.cc/)

*An advanced AI + IoT + Robotics safety infrastructure platform designed for campuses and industries.*

[Demo Video](https://drive.google.com/file/d/1I-GsaEnuhVUpobU__CI98upZ1kNSIQ63/view?usp=sharing) • [Architecture](#architecture) • [Documentation](https://drive.google.com/file/d/1O8EUNkS87W9LC7qszqtTBXuaTxcXJNmz/view?usp=sharing)

</div>

---

## 🚨 Problem Statement

Industrial complexes and smart campuses face critical challenges in emergency response:
1. **Delayed Detection**: Traditional alarms rely on single-point sensors and lack context.
2. **Slow Response Times**: Human verification is required before initiating a response, wasting precious minutes.
3. **Hazard Exposure**: First responders enter blindly without real-time data on hazard severity or location.

**AROHHAN solves this by combining IoT sensor fusion, AI severity analysis, and autonomous robotics to eliminate the gap between detection and response.**

---

## ✨ Features

- 📡 **Real-time IoT Monitoring** — Multi-sensor data acquisition (Temp, Gas, Smoke, Motion) via ESP32.
- 🧠 **AI Hazard Severity Analysis** — Predictive algorithms determine risk levels (Low, Medium, High, Critical).
- 🤖 **Autonomous Rover Dispatch** — Auto-deploying robotic units for on-ground verification and mitigation.
- ⚡ **Emergency Response Automation** — Auto-lockdown, evacuation routing, and automated alerts.
- 📊 **Live Dashboard Analytics** — A futuristic React-based mission control panel.
- 🔄 **Sensor Fusion System** — Reduces false positives by correlating multi-modal sensor data.

---

## 🏗️ Architecture Overview

The system operates across four primary layers:
1. **Perception Layer (Hardware)**: IoT nodes continuously stream environmental data.
2. **Intelligence Layer (AI Engine)**: Python-based models classify risk and fuse sensor inputs.
3. **Control Layer (Backend)**: Node.js/Express handles business logic and WebSocket broadcasting.
4. **Presentation Layer (Frontend)**: React dashboard visualizes the hazard state and controls rovers.

![Architecture Diagram](./docs/architecture.png)

*(Note: Architecture diagram placeholder. See `docs/` for details.)*

---

## 🛠️ Tech Stack

| Module | Technologies |
|---|---|
| **Frontend** | React, Vite, Tailwind CSS, Recharts, Lucide Icons |
| **Backend** | Node.js, Express, Socket.io, REST APIs |
| **AI Engine** | Python, Scikit-learn, Pandas, NumPy |
| **Hardware** | ESP32, Arduino C++, DHT11, MQ-2, Ultrasonic |
| **Communication** | WebSockets, MQTT, HTTP/REST |

---

## 🚀 Setup & Installation

### Prerequisites
- Node.js (v18+)
- Python (v3.10+)
- Arduino IDE (for hardware module)

### 1. Clone the Repository
```bash
git clone https://github.com/HackIndiaXYZ/AROHAN-GIT.git
cd AROHAN-GIT
```

### 2. Start the Backend
```bash
cd backend
npm install
npm start
```

### 3. Start the Frontend Dashboard
```bash
cd frontend
npm install
npm run dev
```

### 4. Initialize AI Engine
```bash
cd ai-engine
pip install -r requirements.txt
python mock_inference.py
```

---

## 📸 Demo Workflow & Screenshots

1. **Idle State**: Dashboard shows all sensors nominal.
2. **Event Trigger**: A simulated gas leak is triggered via `simulations/gas-leak.json`.
3. **AI Classification**: AI engine flags the event as **CRITICAL**.
4. **Rover Dispatch**: Dashboard updates to show autonomous rover moving to Sector 4.

![Dashboard Preview](./media/screenshots/dashboard-preview.png)
*(Note: Add screenshot to media folder before submission)*

---

## 🔮 Future Scope

- 🚁 **Drone Integration**: Autonomous aerial overview for outdoor hazard mapping.
- 🔮 **Predictive AI**: Forecasting hazard spread using thermal fluid dynamics models.
- 🏙️ **Smart City API**: Integration with municipal emergency services (Fire/Police).

---

## 🤝 Contributing

We welcome contributions! Please see [CONTRIBUTING.md](CONTRIBUTING.md) for details on our code of conduct and the process for submitting pull requests.

---

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---
<div align="center">
<i>Built with ⚡ for HackIndia</i>
</div>
