# Watmonitor - Water Level Monitoring Web Application

**Watmonitor** is a universal web-based interface for monitoring water levels using IoT sensor nodes. It stores real-time water level data in a centralized database and provides an intuitive, cross-platform interface to monitor water levels in wells, tanks, lakes, and other water sources. Watmonitor is designed to be sensor-agnostic, supporting a variety of sensor technologies such as ultrasonic, optical, radar, and more.

## Key Features:
- **Real-time Monitoring**: Access up-to-date water level and volume data from your sensors.
- **Cross-platform Accessibility**: Use Watmonitor on both desktop and mobile (Android & iOS).
- **Sensor Agnostic**: Compatible with any water level sensor or industrial monitoring system.
- **QR Code Scanning**: Retrieve sensor data quickly by scanning QR codes associated with each sensor node.
- **Affordable & Open-source**: Self-hosted, downloadable graphs, and open-source hardware-friendly.
- **Multilingual Support**: Available in multiple languages including English, Slovak, German, Russian, French, and Spanish.
- **Historical Data & Graphs**: Access full data history, visualize trends, and download or export graph data in various formats.

## Supported Sensors:
Watmonitor supports a variety of water level sensors, including:
- Ultrasonic
- Optical
- Laser
- Radar
- Capacitive
... and many more!

## Usage Scenarios:
Watmonitor is ideal for continuous monitoring of water levels in:
- Wells
- Tanks
- Ponds, lakes, rivers
- Reservoirs
- Sewage systems

## ESP32 Integration:
The system provides automatic source code generation for ESP32-based sensor nodes, compatible with Arduino IDE and supporting WiFi or Ethernet connectivity. The pre-generated code is configured for easy integration with Watmonitor, with support for Over-The-Air (OTA) updates and ultra-low power modes.

## Additional Features:
- **History & Records Pages**: View detailed records, including min/max values over selected timeframes.
- **Line Area Graphs**: Analyze water level data across different time series and download graphs in .csv, .jpg, .png, or .svg formats.
- **Wiring Diagrams**: Simplified wiring diagrams and pin-mapping tables for easy sensor integration.

## FAQ:
- **Do I need web hosting to run Watmonitor?**  
  Yes, local or internet-based hosting is required with PHP support.
  
- **Is the configuration process easy?**  
  The system provides automatic code generation and clear setup instructions for sensors.
  
- **Can I log data into other systems?**  
  Watmonitor allows integration with other systems through configurable data upload routes.

For more details and documentation, check out the full [Watmonitor website](#).
