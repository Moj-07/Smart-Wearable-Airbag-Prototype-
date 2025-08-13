# Smart-Wearable-Airbag-Prototype

A wearable airbag system designed to protect **elderly people** and **small children** from injury during falls.  
The system uses **MPU6050** for fall detection, **NodeMCU** for processing, and integrates with **Blynk IoT** for real-time monitoring.  
This is a **prototype version** built for demonstration purposes.

---

## 📌 Features
- **Fall Detection** using MPU6050 accelerometer + gyroscope.
- **Automatic Airbag Deployment** using relay-controlled inflation (fan-based prototype).
- **Wireless Data Transmission** via NodeMCU (ESP8266).
- **Real-time Monitoring** using Blynk IoT on Android.
- **Compact & Wearable** design for elderly and children.

---

## 🛠 Components Used
| Component | Quantity | Purpose |
|-----------|----------|---------|
| NodeMCU ESP8266 | 1 | Main control unit |
| MPU6050 | 1 | Detects angle & motion |
| Relay Module | 1 | Controls airbag inflation mechanism |
| Fan (prototype) / CO₂ Canister (future) | 1 | Airbag inflation |
| Power Source | 1 | Battery for portability |
| Blynk IoT App | - | Monitoring & data logging |

---
## ⚙ How It Works
1. **Detection** – MPU6050 continuously measures tilt and acceleration.
2. **Decision** – If fall angle exceeds the threshold, NodeMCU triggers the deployment.
3. **Activation** – Relay turns on inflation system (fan in prototype).
4. **Monitoring** – Data sent to Blynk IoT for remote viewing.

---

## 🚀 Future Improvements
- Replace fan with **CO₂ canister mechanism** for instant inflation.
- Add **Pulse Oximeter** for vitals monitoring.
- Implement **LoRa communication** for long-range alerting.
- Compact 3D-printed housing for better wearability.

---

## 📄 License
This project is licensed under the **MIT License** – see the [LICENSE](LICENSE) file for details.

---

## 🤝 Contributing
Pull requests are welcome! If you want to improve the design or code,  
please fork the repository and submit a PR.

Contact on insta: https://www.instagram.com/moses.john07?igsh=Z3lxbG40ZmduOHVm
