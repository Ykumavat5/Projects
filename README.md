# 🚀 Radar System using I.O.T device & ThingSpeak

This project showcases a real-time radar system built using an **ultrasonic sensor** and **NodeMCU (ESP8266)**. The radar system collects distance data and uploads it to **ThingSpeak**, a cloud-based IoT analytics platform. It can be used for object detection, proximity monitoring, or basic surveillance applications.

---

## 🛠️ Technologies & Components

### Hardware:
- 🧠 **NodeMCU ESP8266** – Wi-Fi-enabled microcontroller
- 📡 **HC-SR04 Ultrasonic Sensor** – Distance measurement
- 🔌 Jumper wires, Breadboard, and Power Supply
- Servo Motor – For rotating the sensor (simulate scanning radar)

### Software:
- 🖥️ **Arduino IDE** – For writing and uploading the firmware
- 🌐 **ThingSpeak** – For cloud-based data storage and visualization
- 📊 **MATLAB (optional)** – For data processing or analysis


---

## 🔧 How It Works

1. The **ultrasonic sensor** measures the distance to nearby objects.
2. The **NodeMCU** collects this data and sends it over Wi-Fi to **ThingSpeak**.
3. ThingSpeak logs the data and displays it on **live charts**.
4. A servo motor is used, To make the radar scan across an arc, emulating a real radar system.

---

## 🧾 ThingSpeak Setup

1. Create a ThingSpeak account: [https://thingspeak.com](https://thingspeak.com)
2. Create a new channel and enable fields (e.g., `Distance`, `Angle`, etc.).
