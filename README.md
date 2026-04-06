# 🚗 Arduino Obstacle Avoiding Car

An autonomous robot car built using Arduino that detects obstacles using an ultrasonic sensor and navigates without human intervention.

## 📌 Features
- Automatic obstacle detection
- Real-time navigation
- Simple and cost-effective design
- Beginner-friendly robotics project

## 🛠️ Components Used
- Arduino UNO
- Ultrasonic Sensor (HC-SR04)
- L298N Motor Driver
- DC Motors (2/4)
- Servo Motor (optional)
- Chassis + Wheels
- Battery Pack

## ⚙️ Working Principle
The ultrasonic sensor continuously measures the distance of objects ahead.  
- If no obstacle → car moves forward  
- If obstacle detected → car stops and changes direction  

## 🔌 Circuit Diagram
![Circuit](circuit_diagram.png)

## ▶️ How to Run
1. Connect all components as per circuit diagram
2. Upload the code using Arduino IDE
3. Power the car using battery
4. Place the car on ground and observe autonomous movement

## 📽️ Demo
See demo video in `media/demo_video_link.txt`

## 📁 Folder Structure
- `code/` → Arduino code
- `docs/` → Documentation
- `media/` → Demo links/videos

## 🚀 Future Improvements
- Add Bluetooth/WiFi control
- Implement path memory
- Use AI for smarter navigation

## 👨‍💻 Author
Tilak Nema
