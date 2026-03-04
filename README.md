# 🌦️ IoT Weather Monitoring System

## 📌 Overview
This project is an IoT-based Weather Monitoring System that collects real-time environmental data using sensors and transmits it to a cloud/database server for storage and monitoring.

The system measures temperature and humidity using an ESP8266/ESP32 microcontroller and sends the data via Wi-Fi to a remote database such as MySQL or Firebase.

---

## 🛠️ Hardware Components
- ESP8266 / ESP32
- DHT11 / DHT22 Sensor
- Breadboard & Jumper Wires
- Power Supply

---

## 💻 Technologies Used
- Arduino IDE
- C++ (Embedded Programming)
- Wi-Fi (HTTP / MQTT)
- MySQL / Firebase
- Optional Web Dashboard

---

## ⚙️ System Architecture
Sensor → Microcontroller → Wi-Fi → Server → Database → Dashboard

---

## 🚀 Features
- Real-time weather monitoring
- Cloud data storage
- Remote access
- Scalable and low-cost design

---

## 🗄️ Database Example (MySQL)

```sql
CREATE TABLE weather_data (
    id INT AUTO_INCREMENT PRIMARY KEY,
    temperature FLOAT,
    humidity FLOAT,
    created_at TIMESTAMP DEFAULT CURRENT_TIMESTAMP
);
```

---

## 🔧 How to Run

1. Connect the DHT sensor to ESP8266/ESP32.
2. Upload the Arduino code using Arduino IDE.
3. Configure Wi-Fi credentials.
4. Set your database or Firebase credentials.
5. Monitor incoming data from your database or dashboard.

---

## 📈 Future Improvements
- Add data visualization charts
- Implement alert system (SMS/Email)
- Deploy on cloud services (AWS, Google Cloud)
- Add more sensors (pressure, air quality)

---

## 👨‍💻 Author
Mahmoud Zahra
