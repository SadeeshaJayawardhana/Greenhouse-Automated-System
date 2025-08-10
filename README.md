# Greenhouse Automated System 🌱  
An Arduino-based automated greenhouse project designed to monitor and control environmental factors such as temperature, humidity, and soil moisture. The system automates irrigation and ventilation to ensure optimal plant growth while conserving water and energy.  

---

## Features  
- Automatic irrigation based on soil moisture levels.  
- Temperature and humidity monitoring with real-time response.  
- Automatic fan control for ventilation and climate regulation.  
- Energy-efficient operation for sustainable agriculture.  
- Scalable design for larger greenhouses and more sensors.  

---

## Technologies Used  
- **Arduino Uno:** Central microcontroller for sensor and actuator control.  
- **DHT11 Sensor:** Measures temperature and humidity.  
- **Soil Moisture Sensor:** Monitors soil water content to trigger irrigation.  
- **Relay Module:** Controls water pump and fan operation.  
- **Water Pump:** Automated plant watering.  
- **Fan System:** Maintains proper airflow and temperature.  

---

## Getting Started  

### Prerequisites  
- **Arduino IDE** installed on your computer.  
- Arduino Uno board and compatible USB cable.  
- DHT11 sensor, soil moisture sensor, water pump, fan, and relay module.  
- Breadboard and jumper wires for connections.  

---

### Installation  
1. Clone the repository:  
```bash
git clone https://github.com/SadeeshaJayawardhana/Greenhouse-Automated-System
```
2. Open the Arduino folder and upload the code to your Arduino Uno using the Arduino IDE.  

3. Assemble the hardware according to the wiring diagram in the `/Docs` folder.

---
   
## Usage
- Power on the system and let it start collecting sensor data.
- The system will automatically water plants when soil moisture drops below the set threshold.
- The fan will turn on automatically when temperature or humidity exceeds optimal limits.
- Adjust threshold values in the Arduino code for different plant types or climates.

---

## Project Structure
- /Arduino → Source code for Arduino Uno.
- /Docs → Wiring diagrams, schematics, and documentation.

---

## Future Enhancements
- Add a mobile app for remote monitoring and control.
- Integrate a camera module for plant health monitoring.
- Include data logging and analytics for growth patterns.
- Solar power integration for off-grid operation.

---

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

## Acknowledgments
- Inspiration from IoT-based smart agriculture solutions.
- Support from the developer and maker community.
