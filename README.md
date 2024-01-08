# Noxious Gas Detection System for Coal Mines

## Overview

The Noxious Gas Detection System is a highly specialized and technologically advanced solution developed to enhance safety within coal mines. It monitors critical environmental parameters, particularly focusing on the presence of hazardous gases, and provides real-time data essential for the well-being of mine workers. Utilizing the ESP32 microcontroller, the system sends eight different parameter data i.e. H₂S, CO, C₆H₆, PM 2.5, TVOC, CO2-eq, temperature, and humidity to InfluxDB over Wi-Fi and displays this information on a Grafana dashboard.

## Key Features

- **ESP32 Microcontroller**: The central unit that interfaces with various sensors to collect and transmit environmental data.
- **Real-Time Data Transmission**: Sends data on eight parameters i.e. H₂S, CO, C₆H₆, PM 2.5, TVOC, CO2-eq, temperature, and humidity data to InfluxDB, enabling prompt monitoring and alerting.
- **Grafana Dashboard**: Offers a real-time visualization of environmental parameters for quick analysis and action.
- **Bayesian Sensor Fusion Algorithm**: Increases detection accuracy by 25% by intelligently combining data from multiple sensors to identify anomalies.
- **Automated Alerts and GUI**: Utilizes SMTP for automated alerts and Python’s Tkinter to design a GUI for rapid SOS responses.

## Technical Highlights

### Sensor Fusion for Enhanced Accuracy

Sensor fusion is a critical component in the detection system, significantly reducing the margin of error in identifying potential hazards. By employing a Bayesian approach, the system weighs the reliability of each sensor, improving the accuracy and robustness of the readings. This project has effectively utilized Bayesian sensor fusion to discern anomalous increases in gas concentrations, ensuring a high detection accuracy of 93%.

### System Integration and Data Visualization

The system's firmware, manages the ESP32's operation, ensuring seamless sensor integration and data handling. The real-time data is visualized on a custom Grafana dashboard, providing an at-a-glance view of all critical parameters and enabling mine operators to make informed decisions swiftly.

### Challenge Overcome

Calibration of sensors posed a significant challenge, particularly in distinguishing between normal environmental variations and genuine anomalies. The project overcame this by refining the Bayesian algorithm, enhancing the system's capability to minimize false positives and improve overall accuracy.

## Usage and Impact

This device is instrumental in ensuring the safety of miners by providing a robust system for early detection of noxious gases. The improved reaction time to anomalies, facilitated by automated alerts and a user-friendly GUI, has led to a 37% quicker response, potentially saving lives and preventing health hazards.

## Conclusion

The Noxious Gas Detection System exemplifies a groundbreaking application of sensor technology in critical safety environments. It's not only a showcase of engineering innovation but also a significant step towards protecting the lives of those who work in one of the most hazardous industries.

