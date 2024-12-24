# IoT-Based Drinking Water Quality Monitoring System

## Objective
To ensure the availability of safe and high-quality drinking water by continuously monitoring critical parameters. This system provides a real-time, automated, and efficient alternative to traditional manual water quality testing methods.

![Architecture](https://github.com/fawaz165/IoT-Based-Drinking-Water-Quality-Monitoring-System/blob/main/flowchart.png)

---

## Key Features

1. **Real-Time Monitoring**
   - Continuously measures electrical conductivity (EC) and water temperature to assess water quality.
   - Provides instant feedback and visualization through a 0.96" OLED display.

2. **IoT Integration**
   - Utilizes the ESP32 Wi-Fi module for wireless data transmission to the Thingspeak IoT platform.
   - Enables remote access, trend analysis, and real-time alerts for deviations from safe water standards.

3. **Compliance with Standards**
   - Adheres to World Health Organization (WHO) guidelines for drinking water quality:
     - EC values: ≤ 400 μS/cm
     - Temperature: 6°C – 20°C

---

## Technologies and Components

### **Hardware**
- **ESP32 Wi-Fi Module:** Central microcontroller for data acquisition, processing, and transmission.
- **TDS/EC Sensor:** Measures water conductivity to indicate dissolved solids and contaminants.
- **DS18B20 Waterproof Temperature Sensor:** Provides accurate water temperature readings.
- **0.96" OLED Display:** Displays real-time water quality parameters locally.

### **Software and IoT Integration**
- **Thingspeak IoT Platform:** Stores, visualizes, and analyzes data using customizable graphs and charts.
- **ESP32 ADC:** Converts sensor signals for processing and transmission.

![Components](https://github.com/fawaz165/IoT-Based-Drinking-Water-Quality-Monitoring-System/blob/main/components.png)


---

## System Architecture

![System Architecture](https://github.com/fawaz165/IoT-Based-Drinking-Water-Quality-Monitoring-System/blob/main/architecture.png)

1. **Sensor Module**
   - TDS/EC Sensor to measure electrical conductivity.
   - DS18B20 Temperature Sensor to measure water temperature.

2. **Processing Unit**
   - ESP32 Wi-Fi Module to process data and transmit it wirelessly.
   - OLED Display for local real-time visualization.

3. **IoT Server**
   - Thingspeak platform for remote data visualization and analysis.

---

## Output Graph

![Graph](https://github.com/fawaz165/IoT-Based-Drinking-Water-Quality-Monitoring-System/blob/main/graph.png)

## Impact
This project aligns with global goals for providing clean water and sanitation. It offers a cost-effective, scalable solution for residential, commercial, and industrial water quality monitoring, ensuring safe drinking water for all.

