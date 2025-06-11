
# Ultrasonic Security System using Arduino

A smart proximity-based security system using **Arduino UNO** and **HC-SR04 ultrasonic sensor** for real-time intrusion detection. Developed as part of a coursework project by students of **Manipal University Jaipur**.

## 📁 Project Structure

This is a hardware-software project involving the following components:

- 📦 HC-SR04 Ultrasonic Sensor  
- 📦 Arduino UNO  
- 📦 Buzzer & LEDs (Red, Yellow, Green)  
- 📦 Breadboard, Jumper Wires, Resistors  
- 💻 Arduino IDE for code development and uploading  
- 🧠 Embedded C (Arduino language)

## ✨ Features

- Distance-based intrusion detection
- Visual (LED) and auditory (buzzer) feedback
- Real-time monitoring via Serial Monitor
- Modular and cost-effective design
- Customizable threshold alerts

## 🛠️ Technologies Used

| **Category**   | **Technologies**                                                                                                  |
|----------------|--------------------------------------------------------------------------------------------------------------------|
| **Microcontroller** | ![Arduino](https://img.shields.io/badge/Arduino-00979D?style=for-the-badge&logo=arduino&logoColor=white)        |
| **Sensors**         | HC-SR04 Ultrasonic Sensor                                                                                      |
| **Programming**     | Arduino C / Embedded C                                                                                         |
| **Prototyping**     | Breadboard, Jumper Wires, Resistors                                                                            |


## ⚙️ Setup Instructions

### 1. Hardware Setup
- Connect HC-SR04 to Arduino (Trig: Pin 2, Echo: Pin 3)
- Connect LEDs to Pins 4 (Red), 5 (Yellow), 6 (Green) with resistors
- Connect buzzer to Pin 7
- Power the Arduino via USB or 9V supply

### 2. Code Upload
- Open Arduino IDE
- Paste the project code
- Select correct board and COM port
- Click **Upload**

### 3. Test System
- Use Serial Monitor to verify distance readings
- Place objects at different distances to test LED & buzzer behavior

## 📈 Output Logic

- **> 50 cm**: Green LED (Safe Zone)
- **20–50 cm**: Yellow LED (Caution Zone)
- **< 20 cm**: Red LED + Buzzer (Danger Zone)

## 📚 References

- [Arduino Official Site](https://www.arduino.cc/)
- [Ultrasonic Security System Project](https://projecthub.arduino.cc/Krepak/ultrasonic-security-system-a6ea3a)
- Simon Monk, *Arduino Programming for Beginners*, McGraw-Hill Education, 2018
- [YouTube Video: Frustrated Engineer](https://www.youtube.com/watch?v=-EjveSCYQOM)

---


