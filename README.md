# 🪟 Smart Solar Window System with Integrated Solar Tracking

This project presents a sustainable and intelligent solar window that generates electricity while also responding to environmental conditions like rain and smoke. It integrates solar tracking, automation, and transparent photovoltaic technology to enhance energy efficiency in buildings.

---

## 🔍 Key Features

### 1️⃣ Transparent Photovoltaic Glass
- Uses transparent thin-film PV to convert **UV and IR light** into electricity.
- Maintains **daylight visibility** while generating solar energy.

### 2️⃣ Single-Axis Solar Tracking
- Dynamically adjusts the **window angle** using **LDR sensors** to follow the sun’s path.
- Increases energy generation throughout the day.

### 3️⃣ Automation & Safety
- **Rain Sensor** triggers auto-closing of the window.
- **Smoke Sensor** triggers full opening for ventilation in emergencies.
- Built-in **PID control** for accurate panel positioning.

### 4️⃣ Manual & Scheduled Operation
- User-defined **open/close positions**.
- Option to run on a **pre-set schedule** for daily ventilation.

### 5️⃣ Precision with Chain Actuation
- Smooth and reliable **chain-driven actuator** for window movement.
- Integrates a **rotary motor** for solar alignment with minimal mechanical error.

---

## ⚙️ System Components

| Component | Description |
|----------|-------------|
| **Microcontroller** | Arduino Uno (ATmega328P) |
| **Sensors** | LDRs, YL-83 (rain), MQ-2 (smoke) |
| **Actuation** | Chain actuator, servo motor |
| **PV System** | Transparent photovoltaic glass |
| **Control Logic** | PID controller (P=240, I=180) |

---

## 📊 Simulations & Results

- Designed & simulated in **MATLAB Simulink**
- Verified **panel response** to torque and sun motion
- Used **unit step function** to simulate LDR response
- Results show **panel tracks sun smoothly and stabilizes** without overshoot

---

## 🧪 Tools Used

- `Simulink` – for simulation
- `SolidWorks` – for design modeling
- `Arduino IDE` – for automation control
- `Proteus` (optional) – for circuit design simulation


## 👥 Team Members

- **Hushan Ridmika** 
- **Dinithi Ravisha**   
- **Sunath Rodrigo**  
- **Sivakumar Sajeevan**  
- **Sasini Sachika**

---

## 🚀 Future Enhancements

- Implement a **dual-axis tracking system** for finer solar alignment  
- Integrate **machine learning** for predictive scheduling based on environmental data  
- Develop a **mobile/web app interface** for remote monitoring  
- Expand energy storage capacity using **Li-ion battery packs**  

---

## 📄 License

This project is licensed under the **MIT License** – free to use, modify, and distribute with attribution.

---

## 🙌 Acknowledgements

Thanks to the **Department of Electrical Engineering, University of Moratuwa**, for support and guidance during this final-year research project.

---

📬 **Feel free to fork, star ⭐, or raise issues for improvements!**  
🔗 For collaboration inquiries, contact us through our GitHub profiles or university emails.


