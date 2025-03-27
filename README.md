# Tea Leaf Quality Classification Project

## Overview
This project focuses on real-time tea leaf quality classification using machine learning. The system utilizes **moisture, temperature, and humidity sensors** connected to an **Arduino Mega**, while the AI model runs on a **local server** via **USB serial communication**. The interface is built using **Tkinter**.

## Features
- **Real-time Data Collection:** Sensors measure moisture, temperature, and humidity of tea leaves.
- **Machine Learning Model:** Classifies tea leaf quality based on collected sensor data.
- **Localhost Deployment:** The AI model runs on a local device instead of being embedded in the Arduino.
- **USB Serial Communication:** Data is transmitted from Arduino to the local server.
- **Tkinter-based UI:** Provides a simple graphical interface for data display and classification results.

## Components Used
### Hardware:
- **Arduino Mega** (for sensor data collection)
- **Moisture Sensor**
- **Temperature Sensor**
- **Humidity Sensor**

### Software:
- **Python (Tkinter for UI, scikit-learn for ML)**
- **Google Cloud (for model training and testing)**
- **PySerial (for USB communication with Arduino)**

## Installation
### Prerequisites:
- Install Python and required libraries:
  ```sh
  pip install numpy pandas scikit-learn pyserial tkinter
  ```
- Connect the Arduino Mega and upload the sensor reading script.

### Running the Project:
1. **Connect Arduino** via USB.
2. **Start the Python script** to receive sensor data and classify tea leaves:
   ```sh
   python main.py
   ```
3. **View the results** in the Tkinter interface.

## Data Flow
1. **Sensors collect data** → 2. **Arduino sends data via USB** → 3. **Python script processes data** → 4. **ML model classifies tea quality** → 5. **Tkinter UI displays results**

## Future Enhancements
- Improve model accuracy with more training data.
- Deploy on a cloud-based server for remote access.
- Add mobile app integration.

## Contributors
Hrishikesh Choudhury
Aariyan Krishnatria
Ayushmaan Krishna


