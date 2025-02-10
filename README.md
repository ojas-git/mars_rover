# Mars Rover Navigation Optimization System 🛰

The Mars Rover Navigation Optimization System is a passion project by [Tejas Gupta]() and [Ojas Gupta](). This system is designed for indoor environments, focusing on data mining and analysis rather than mobility. Obstacles will be placed to test its functionality while gathering and processing key environmental data like temperature and humidity.

## Objectives

- Collect and transmit thermal data wirelessly to a computer.
- Detect obstacles using ultrasonic sensors.
- Indicate path changes via buzzer and LED.
- Safeguard navigation based on temperature and obstacles.
- Log and analyze data on a laptop using ThingSpeak.

## Components

| Category | Component |
|-|-|
| Microcontroller and Communication |ESP32 / Wroom 32D |
| Sensors | HC-SR04 Ultrasonic Sensor (Obstacle detection), DHT22 (Temperature sensor) |
| Circuit and Indicators | PCB (For circuit connections), Buzzer & LED (For warnings and path indication) |
| Power Supply | Lithium-ion battery (18650), Battery charger |
| Display | OLED Display (0.96" or 1.3", SSD1306/SH1106, I2C/SPI) |
| Data Handling | Data will be transmitted and analyzed using ThingSpeak. The Arduino API will be used for interfacing and control. |

## Future Enhancements

- Implementing autonomous navigation.
- Adding more sensors for enhanced environmental data collection.
- Visualizing data with advanced analytics and machine learning.

## License

This project is open-source under the MIT License.

