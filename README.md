# ⚡ Power System Predictive Maintenance System

A **Predictive Maintenance System** designed to monitor and analyze critical engine parameters such as **temperature**, **humidity**, **noise levels**, and **vibrations** using Arduino and AI-based analysis. This helps in early detection of anomalies and improves overall system reliability.

---

## 🛠️ Components Used

- Arduino board (e.g., Arduino Uno)
- Sound sensor module
- Vibration sensor module
- DHT11 temperature and humidity sensor
- Breadboard
- Jumper wires
- USB cable
- Computer with Arduino IDE installed

---

## 🚀 How It Works

This system continuously collects data from environmental and mechanical sensors connected to the engine and sends it to a machine learning model trained to identify **healthy** and **faulty** engine conditions.

---

## 📌 Step-by-Step Implementation

### 🔌 Step 1: Connect the Sound Sensor
- **Pins:** VCC → 5V, GND → GND, AOUT → A0 (Analog)
- Detects ambient noise levels near the engine.

### 🔩 Step 2: Connect the Vibration Sensor
- **Pins:** VCC → 5V, GND → GND, SIG → A1 (Analog)
- Measures mechanical vibrations.

### 🌡️ Step 3: Connect the DHT11 Sensor
- **Pins:** VCC → 5V, GND → GND, DATA → D2 (Digital)
- Captures temperature and humidity levels.

### 🧠 Step 4: Write Arduino Code
- Open the **Arduino IDE**.
- Write code to read from all sensors and transmit data to the **Serial Monitor (COM6)**.

### 🤖 Step 5: Train the Model with Python + Generative AI
- Use Python to read data from **serial port COM6**.
- Collect both **Good Engine** and **Bad Engine** sensor data.
- Train a **Generative AI model** to learn patterns from the data.

### 🔍 Step 6: Predict Engine Health
- Read real-time data from **COM6** using Python.
- Pass data to the trained AI model.
- Output: **Predicted Engine State** (e.g., Normal, Warning, Critical)

---

## 💡 Future Improvements
- Add real-time dashboard for monitoring.
- Integrate with cloud for remote access and alerting.
- Use more advanced sensors for accuracy.



