# 🤖 Obstacle Avoidance Challenge Bot – RPA Domain

**Team Name:** KALKI  
**Members:** Roshesh Chaware, Shweta Pawar, Siddesh Sambhare, Ritika Pandey, Purva Rathi, Pranay Pathekar  
---

## 🌟 Domain

**Domain:** Robotic Process Automation (RPA)  
Our project demonstrates **autonomous robotic automation**, where the bot navigates environments and avoids obstacles without human intervention, simulating real-world industrial or service automation tasks.  

---

## 📝 Problem Statement

Traditional obstacle-avoiding robots in automation systems face limitations:  

- ❌ Fail to detect **transparent surfaces** (like glass partitions)  
- ❌ Miss **thin or small obstacles** (wires, rods, narrow objects)  
- ❌ Struggle with **angled surfaces** or unusual geometries  

These failures can cause automation downtime, collisions, or errors in workflow environments.

---

## 💡 Solution

We designed a **hybrid RPA bot** that overcomes these challenges:  

- **Sensor Fusion:** Combines 2 ultrasonic sensors + 2 IR sensors + 1 servo for precise navigation  
- **AI Vision Integration:** Uses camera-based depth estimation to detect transparent, thin, and angled obstacles  
- **Autonomous Decision-Making:** Fusion algorithm processes sensor + vision data to move safely  
- **Prototype Simulation:** Works entirely in software for presentation and testing 

---

## 🛠️ Features

- ✅ **Autonomous Navigation:** Moves without human intervention  
- ✅ **Robust Obstacle Detection:** Detects tricky obstacles traditional robots miss  
- ✅ **AI + Sensor Fusion:** Ensures accurate real-time decision-making  
- ✅ **Software Prototype:** Demonstrates automation without hardware  


---
## ⚡ How It Works

1. **Sensing:** Ultrasonic and IR sensors continuously gather distance data  
2. **AI Processing:** Camera-based depth estimation detects invisible or angled obstacles  
3. **Fusion Decision:** Combines sensor + AI data to determine movement  
4. **Action:** Servo adjusts path; bot avoids obstacles autonomously  

---

## 🧰 Tech Stack

- **Programming Language:** C++ / Python (Simulation)  
- **AI/ML:** Depth estimation using TensorFlow / OpenCV  
- **Simulation/Visualization:** Python GUI or optional React + Tailwind for UI  
- **Sensors & Hardware Models:** Ultrasonic, IR, Servo (simulated)  

---

## 🚀 Unique Value Proposition

- Detects **transparent, thin, and angled obstacles**  
- Combines **AI vision + sensors** for accurate autonomous navigation  
- Demonstrates **RPA capabilities** in a safe, hardware-free prototype  

