# Smart-Road-Safety-Monitoring-System-
🚧 Smart Road Safety Monitoring System
An IoT-based real-time road hazard detection system designed to enhance road safety by identifying and mapping pavement distresses such as potholes, cracks, unmarked speed breakers, and rough surfaces. The system uses a combination of ultrasonic sensors, a vibration sensor, and a GPS module to detect anomalies and report their geolocation.

🔧 Features
📡 Real-time data transmission using ESP8266 to Firebase Realtime Database

📍 GPS-based location tracking for detected road issues

📊 Road hazard classification (e.g., less severe, moderate, highly severe)

📈 Mapped visualization of hazard locations using Google Maps API

🔔 Dashboard warning alerts for the driver (visual + sound-based)

🔌 Low power consumption and compact hardware design

✅ Follows IRC guidelines for road safety

🧠 Technologies & Concepts Used
IoT (Internet of Things)

Embedded C++

Sensor Integration: Ultrasonic, vibration

GPS & Geo-tagging

Wireless communication (ESP8266 Wi-Fi module)

Firebase Realtime Database

Google Maps API (for frontend mapping)

⚙️ Hardware Components
ESP8266 NodeMCU (Wi-Fi enabled microcontroller)

Ultrasonic Sensors (HC-SR04) – for measuring road surface irregularities

Vibration Sensor – to detect vehicle shocks from potholes

GPS Module (e.g., NEO-6M) – for geo-tagging

Buzzer / LED (optional) – for in-vehicle alerts

🛠 How It Works
Ultrasonic sensors detect surface irregularities by measuring distance from the road.

Vibration sensor detects jerks caused by potholes or road damage.

GPS module captures the location of the detected issue.

The ESP8266 compiles the data and sends it to Firebase in real-time.

The data can be visualized on a Google Maps interface for maintenance and alerting purposes.

📌 Use Cases
Real-time road condition monitoring

City/municipal road maintenance planning

Smart vehicle dashboard alerts

Accident prevention in poorly maintained roads

📷 Screenshots / Demo (optional)
(Add images or videos showing your circuit, serial monitor output, or mapped results.)

📁 Repository Structure
vbnet
Copy
Edit
/SmartRoadSafetyMonitoringSystem
│
├── ArduinoCode/        → ESP8266 C++ code (.ino)
├── Firebase/           → Firebase DB structure or rules (if needed)
├── WebInterface/       → (Optional) Google Maps visual dashboard
├── README.md           → Project documentation
└── images/             → Circuit diagrams, output screenshots, etc.
✅ Future Improvements
Integrate machine learning for automated pattern recognition of road damages

Add camera module for visual confirmation

Mobile app interface for real-time alerts

SMS/Email alerts for municipal authorities

#################################################### IMAGES ##################################################
1. FIREBASE UI
![image](https://github.com/user-attachments/assets/b847ab84-8178-44d4-9ace-d675016f68a4)

2. WORKFLOW :
![image](https://github.com/user-attachments/assets/c90be1dc-8a67-4cd1-948c-c686558a107c)

DASHBOARD FOR ALERTING :
3.![image](https://github.com/user-attachments/assets/4c8c0cf9-2067-48df-9447-e005df775091)

4.SERIAL MNONITOR :
![image](https://github.com/user-attachments/assets/a706a3f4-990a-4b4b-8620-ce98e42810dd)

5.MODULE IMAGES:
![image](https://github.com/user-attachments/assets/1f2539f2-be1e-43da-a6e6-3a635ed124bc)

6.CONNECTION :
![image](https://github.com/user-attachments/assets/fefdcbfa-9bbd-4164-8be4-8276b72f00a4)






