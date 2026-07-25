# 🤖 SmartBot – The Self-Aware Obstacle Avoiding Robot 🚧✨

By: Norah 👩‍💻

> 🥷 "Sees, thinks, dodges." SmartBot never crashes — it senses danger before it even gets close and reroutes on the spot, like a tiny robotic ninja on wheels! 🛞💨

🔗 Try it live on Tinkercad: [SmartBot Simulation 🚀](https://www.tinkercad.com/things/jmxZgXeolib-smart-bot-obstacle-avoiding-robot)

---

## 🌟 Overview
SmartBot is an autonomous robot that scans its surroundings using an ultrasonic sensor 📡 mounted on a rotating servo "head" 🔄. The moment it spots an obstacle 🚧, it slams the brakes 🛑, looks left 👀 and right 👀 to judge the best escape route, and confidently zooms 💨 toward open space — all without any human control!

## 🧰 Components Used
- 🧠 Arduino board
- ⚙️ L293D Motor Driver Shield
- 🔋 2 DC Motors
- 🎯 1 Servo Motor
- 📡 Ultrasonic Sensor (HC-SR04)
- 🚗 Robot chassis + wheels
- 🔌 Battery pack

## ⚡ How It Works
1. 🚗 The robot cruises forward while constantly measuring distance with the ultrasonic sensor.
2. 🚧 If an obstacle is detected within 10 cm, SmartBot springs into action:
   - 🛑 Stops immediately
   - ⏪ Backs up a little
   - 🔄 Spins its servo "head" to scan right and left
   - 🧭 Compares both distances and confidently turns toward the side with more open space
3. ✅ Then it resumes cruising forward — smarter and safer! 😎

## 🖼️ Circuit Diagram
<img width="1377" height="713" alt="لقطة شاشة 2026-07-25 183532" src="https://github.com/user-attachments/assets/ee380b07-cbf0-4948-8d4b-07d2a726eab8" />

<img width="1920" height="828" alt="لقطة شاشة 2026-07-25 183544" src="https://github.com/user-attachments/assets/c6a6ca46-e94a-450d-92a6-d757bc5a2dd0" />

## 🔌 Pin Connections
| Component | Arduino Pin |
|---|---|
| Right Motor Speed | 5 |
| Right Motor Positive | 6 |
| Right Motor Negative | 7 |
| Left Motor Speed | 4 |
| Left Motor Positive | 2 |
| Left Motor Negative | 3 |
| Ultrasonic Trig | 11 |
| Ultrasonic Echo | 12 |
| Servo Signal | 10 |

## 👤 Author
✨ Norah ✨
