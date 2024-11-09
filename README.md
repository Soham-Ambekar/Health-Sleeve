
# Health Sleeve - IoT-Based Health Monitoring System

**Health Sleeve** is an IoT-based project designed to monitor human health metrics such as heart rate, pulse, and oxygen levels in real-time. The data is captured through sensors embedded in the sleeve and sent to ThingSpeak, a cloud platform for real-time analytics and monitoring. A dedicated bootstrapped website provides a user-friendly interface for visualizing the monitored health data.

## Features

- **Real-Time Monitoring**: Monitors heart rate, pulse, and oxygen levels continuously.
- **IoT Integration**: Uses IoT devices to collect health data and sends it to the ThingSpeak platform for real-time analysis and display.
- **Web Interface**: Provides a dedicated, responsive website to display real-time health data in a user-friendly dashboard.
- **Data Logging**: Logs data on ThingSpeak for historical analysis and trend visualization.
- **Alerts and Notifications**: Can be extended to send alerts when abnormal health readings are detected.

## Technologies Used

- **Sensors**: Pulse sensor, heart rate sensor, and oxygen sensor (e.g., MAX30100 or similar).
- **Microcontroller**: Arduino, ESP8266/ESP32 (for wireless connectivity).
- **Cloud Platform**: ThingSpeak for data logging and real-time visualization.
- **Web Technologies**: HTML, CSS, JavaScript, Bootstrap (for creating the user interface).

## Project Components

1. **Health Sleeve**:
   - A wearable sleeve equipped with sensors to monitor heart rate, pulse, and oxygen levels.
   
2. **Microcontroller**:
   - The microcontroller processes sensor data and transmits it to ThingSpeak via Wi-Fi.

3. **ThingSpeak**:
   - Cloud platform for storing and analyzing sensor data.
   - Provides real-time data visualization tools for monitoring.

4. **Bootstrapped Website**:
   - A simple, responsive website that fetches and displays health data from ThingSpeak.
   - Built using HTML, CSS, JavaScript, and Bootstrap to make it accessible on any device.

## Installation

### Hardware Setup
1. **Connect Sensors to the Microcontroller**:
   - Heart Rate Sensor (MAX30100) – Connect to the appropriate pins.
   - Pulse and Oxygen Sensor – Connect to the microcontroller.
   
2. **Microcontroller**: 
   - Use an ESP8266 or ESP32 board to enable Wi-Fi connectivity.
   - Program the microcontroller to read the sensor data and send it to ThingSpeak via Wi-Fi.

### Software Setup

1. **ThingSpeak Setup**:
   - Create a ThingSpeak account and set up a new channel.
   - Note down the API key for writing data to the channel.
   
2. **Upload Code to Microcontroller**:
   - Write a program to read sensor data and send it to ThingSpeak.
   - Use the Arduino IDE or PlatformIO to upload the code to the microcontroller.

3. **Web Interface**:
   - Clone or download the provided web code.
   - Set up the website to fetch data from ThingSpeak using ThingSpeak API calls.
   - Deploy the website using a server or locally.

### Dependencies

- **Arduino IDE**: For programming the microcontroller.
- **ThingSpeak API**: For sending and receiving data.
- **Bootstrap**: For the responsive website layout.
- **JavaScript (AJAX)**: To fetch real-time data from ThingSpeak.

## Usage

1. **Start the Health Sleeve**:
   - Wear the sleeve and power on the microcontroller.
   
2. **Real-Time Data**:
   - The microcontroller will collect heart rate, pulse, and oxygen data and send it to ThingSpeak.
   
3. **Monitor Data**:
   - Use the web interface to view real-time health data visualized as graphs and statistics.
   
4. **Analyze Historical Data**:
   - View past health data trends through ThingSpeak’s analytics tools.

## Future Enhancements

- **Mobile App**: Develop a mobile app for easier access and notifications.
- **Alert System**: Implement an alert system to notify users of abnormal readings.
- **Additional Sensors**: Integrate additional sensors for more comprehensive health monitoring.
  
## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgements

- Thanks to the ThingSpeak platform for providing an easy-to-use cloud service for IoT projects.
- Special thanks to Bootstrap for providing an open-source framework for the website interface.

---

Feel free to modify this according to your exact needs!
