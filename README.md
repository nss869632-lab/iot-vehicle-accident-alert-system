 IoT Vehicle Accident Alert System

 Overview
The IoT Vehicle Accident Alert System is designed to reduce the delay between a vehicle accident and emergency response. It automatically detects accidents using a gyrosensor and sends real-time alerts using the ESP8266 microcontroller.

---

 Objective
- To detect vehicle accidents automatically  
- To send alerts to registered contacts instantly  
- To reduce human dependency and response time  
- To improve road safety and survival rate  

---
Components Used
 Hardware
- ESP8266 Microcontroller  
- MPU6050 Gyrosensor  
- L298N Motor Driver  
- DC Motor  
- Power Supply  

Software
- Arduino IDE  
- Embedded C / Arduino Programming  
- Blynk IoT Platform  

---
Working Principle
1. The gyrosensor detects sudden motion or impact  
2. Sensor data is sent to ESP8266  
3. ESP8266 processes the data  
4. If threshold exceeds → accident detected  
5. Alert message is sent via WiFi  
6. Motor action is triggered (optional demonstration)  

---

 System Architecture
Sensor → ESP8266 → WiFi → Alert System  
                     ↓  
                Motor Driver → DC Motor  

---

 Features
- Automatic accident detection  
- Real-time alert system  
- Low-cost and efficient  
- Easy to implement  
- Reduces response time  

---

Limitations
- Requires internet connection  
- Possible false alerts if threshold not calibrated properly  
- No GPS tracking (can be added in future)  

---

 Future Scope
- Integration with GPS for location tracking  
- Cloud data analytics (ThingSpeak / Firebase)  
- AI-based accident prediction  
- Smart city integration  
- Mobile application support  

---


---

 References
- Arduino Official Documentation  
- ESP8266 Datasheet  
- MPU6050 Sensor Datasheet  
- Research Papers on Accident Detection Systems  

---
 Authors
- K. Nagarani  
- E. Nithya Shree  
- Hameed  
- Sheema Begum  

---

Acknowledgement
We thank our guide for continuous support and guidance in completing this project successfully.

---

 Conclusion
This project demonstrates how IoT technology can be used to enhance road safety by automatically detecting accidents and sending alerts, thereby saving lives.
