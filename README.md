# project-carrier-pigeon 🕊️

> **Project Start:** April 8, 2026  
> **Hardware:** RadioMaster Pocket (ELRS) + ESP32/Arduino Receiver  
> **Status:** Phase 1 (Connectivity)

---

## 📝 Overview
**Carrier-Pigeon** is a multi-stage project aimed at mastering the **ExpressLRS (ELRS)** protocol for remote vehicle control. We are developing a custom pipeline that translates gimbal inputs from a RadioMaster Pocket into actionable data for various platforms.

### 👥 Team
* [@Utkarsh](https://github.com/dragenair)
* [@Rishaab](https://github.com/rishaab-uppaal)

---

## 🚀 Development Roadmap

### Phase 1: The Handshake (Current)
* [x] **Learning:** Watching the tutorials #8th april
* [ ] **Binding:** Establish a solid link between the RadioMaster Pocket and the ELRS receiver.
* [ ] **Telemetry:** Verify link quality (LQ) and RSSI feedback.
* [ ] **Serial Bridge:** Output raw CRSF packet data to a laptop via Serial for monitoring.

### Phase 2: Ground Control (Buggy)
* [ ] Map CH1-CH4 to PWM outputs for steering and ESC (Electronic Speed Controller).
* [ ] Implement a "Failsafe" mode (stop motor on signal loss).
* [ ] Field test low-latency maneuvering on a 4-wheel buggy chassis.

### Phase 3: Flight Operations (Drone)
* [ ] Integrate with a Flight Controller (Betaflight/Ardupilot).
* [ ] Configure RX/TX UART ports for CRSF protocol.
* [ ] Arming sequence and PID tuning for stable flight.

---

## 🛠️ Technical Stack
* **Transmitter:** RadioMaster Pocket (Internal/External ELRS)
* **Protocol:** CRSF (Crossfire / ExpressLRS)
* **Processing:** ESP32 / Arduino Framework
* **Data Logging:** Python (for laptop data analysis)

---

## 🔧 Setup & Installation
1. **Clone the Repo:**
   ```bash
   git clone [https://github.com/](https://github.com/)[user]/project-carrier-pigeon.git
