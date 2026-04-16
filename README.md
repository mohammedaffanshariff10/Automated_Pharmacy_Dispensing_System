# 💊 Automated Pharmacy Dispensing System

## 📌 Overview
The Automated Pharmacy Dispensing System is an embedded solution designed to ensure accurate and efficient medicine dispensing. This system automates the process of delivering the correct dosage at the right time, reducing human error and improving reliability in medical environments.

---

## 🎯 Objectives
- Automate medicine dispensing process  
- Ensure accurate dosage control  
- Reduce manual errors in pharmacies/hospitals  
- Provide a cost-effective and efficient solution  

---

## ⚙️ Tech Stack
- **Microcontroller:** Arduino UNO  
- **Programming Language:** C/C++ (Arduino IDE)  
- **Components:**  
  - IR Sensors  
  - Servo Motor  
  - LCD Display (16x2)  
  - Push Buttons (optional)  
  - Power Supply  

---

## 🚀 Features
- 🔹 Automated medicine dispensing mechanism  
- 🔹 Precise control of dosage using servo motor  
- 🔹 Real-time status display on LCD  
- 🔹 Sensor-based detection for accuracy  
- 🔹 User-friendly interface  

---

## 🧠 Working Principle
1. The system stores predefined dosage instructions.  
2. When triggered, the IR sensor detects the presence of a container.  
3. The Arduino processes the input and activates the servo motor.  
4. The servo rotates to dispense a fixed quantity of medicine.  
5. The LCD displays system status and instructions.  

---

## 🔌 Hardware Connections

### IR Sensor
- VCC → 5V  
- GND → GND  
- OUT → Digital Pin (e.g., D2)  

### Servo Motor
- VCC → 5V  
- GND → GND  
- Signal → PWM Pin (e.g., D9)  

### LCD Display (16x2)
- Connected via 4-bit mode or I2C module  

---

## ▶️ How to Run

1. Install Arduino IDE  
2. Connect Arduino board to your system  
3. Upload the code using Arduino IDE  
4. Power the circuit  
5. Place container under dispensing unit  
6. System will automatically dispense medicine  

---

## 📷 Output / Results
- Accurate dispensing of medicine using servo mechanism  
- Real-time feedback displayed on LCD  
- Reduced manual intervention  



https://github.com/user-attachments/assets/abbb9e3b-f95e-4b7a-9248-8087eb34885f


<img width="1024" height="768" alt="ard_circuit" src="https://github.com/user-attachments/assets/78791a81-dc8b-45dc-95ab-a345217e7d5b" />

<img width="1024" height="768" alt="ardui_placement" src="https://github.com/user-attachments/assets/54eb5d2a-d912-402c-882d-e316d686ce0d" />

<img width="768" height="1024" alt="ardui_look" src="https://github.com/user-attachments/assets/43902c38-c3a1-4a48-bf35-571bc1dd25f6" />


---

## 🔍 Applications
- Hospitals  
- Pharmacies  
- Elderly care systems  
- Automated healthcare solutions  

---

## ⚠️ Limitations
- Fixed dosage (not dynamically adjustable)  
- Requires manual refill of medicines  
- Basic prototype (can be enhanced with IoT integration)  

---

## 🔥 Future Enhancements
- IoT-based remote monitoring  
- Mobile app integration  
- Voice assistant support  
- AI-based dosage recommendations  
- Multi-medicine dispensing system  

---

## 👨‍💻 Author
**Mohammed Affan Shariff**  
B.Tech CSE (Big Data)  
