
# Ultrasonic Security System using Arduino

A smart proximity-based security system using **Arduino UNO** and **HC-SR04 ultrasonic sensor** for real-time intrusion detection. Developed as part of a coursework project by students of **Manipal University Jaipur**.

## 📁 Project Structure

This is a hardware-software project involving the following components:

- 📦 HC-SR04 Ultrasonic Sensor  
- 📦 Arduino UNO  
- 📦 Buzzer
- 📦 LEDs (Red, Yellow, Green)  
- 📦 Breadboard, Jumper Wires, Resistors
- 📦 Jumper Wires
- 📦 Resistors (221Ω for each LED)
- 💻 Arduino IDE for code development and uploading  
- 💻 Embedded C (Arduino language)



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


### 🔌 Hardware Setup
- Ultrasonic Sensor (HC-SR04):
  - VCC → 5V (Arduino)
  - Trig → Pin 2 (Arduino)
  - Echo → Pin 3 (Arduino)
  - GND → GND (Arduino)
- LED Connections (via 221Ω resistors):
  - Red LED Anode → Pin 4 (Arduino)
  - Yellow LED Anode → Pin 5 (Arduino)
  - Green LED Anode → Pin 6 (Arduino)
  - Cathodes (shorter leg) of all LEDs → GND (Arduino)
- Buzzer Connection:
  - Positive (longer) pin → Pin 7 (Arduino)
  - Negative (shorter) pin → GND (Arduino)
- Power Supply:
  - Arduino powered via USB cable or external 9V adapter

## Uploading and Running the Code:

- Install Arduino IDE: If you haven't already, download and install the Arduino Integrated Development Environment (IDE) from the Arduino website.
-  Open the Code: Copy the code you provided in your previous question and paste it into the Arduino IDE.
- Select Board: In the Arduino IDE, go to "Tools" > "Board" and select "Arduino/Genuino Uno" as the target board.
- Select Port: Go to "Tools" > "Port" and select the port where your Arduino is connected. This is typically a COM port on Windows or a /dev/ttyUSB port on Linux.
- Upload Code: Click the "Upload" button (right-arrow icon) in the Arduino IDE to compile and upload the code to your Arduino UNO. Make sure your Arduino is connected to your computer during this process.
- Monitor Serial Output: Open the Serial Monitor in the Arduino IDE by clicking "Tools" > "Serial Monitor." You should see distance measurements in centimeters displayed on the Serial Monitor.
- Testing:
  - Place obstacles or objects at various distances from the ultrasonic sensor to test the system.
  - The LEDs and the buzzer will provide visual and auditory alerts based on the proximity of objects.
  - The green LED represents a safe zone, the yellow LED indicates caution, and the red LED and buzzer are triggered in the presence of nearby objects.

### 📌 NOTE:
```bash
1. Ensure that the necessary Arduino libraries for the ultrasonic sensor has been installed if required.
2. Double-check connections to avoid loose wires or incorrect wiring.
3. Test the system in various lighting conditions and adjust the sensor's sensitivity if necessary.
4. Customize the code as needed to fit the specific requirements.
```


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


