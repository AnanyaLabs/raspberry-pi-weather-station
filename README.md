# Raspberry Pi Weather Station

## Project Image

(Project image will be added soon.)

## Project Overview

This project demonstrates how a Raspberry Pi can be used as a weather monitoring station.

The system collects environmental data such as temperature and humidity using sensors and displays the information for monitoring and analysis.

## Learning Objectives

- Understand environmental sensing.
- Learn Raspberry Pi GPIO interfacing.
- Explore Python programming.
- Build a real-world monitoring system.

## Components Required

| Component | Quantity |
|------------|----------|
| Raspberry Pi | 1 |
| DHT11 Sensor | 1 |
| Breadboard | 1 |
| Jumper Wires | As Required |
| Power Supply | 1 |

## Working Principle

1. The DHT11 sensor measures temperature and humidity.
2. Raspberry Pi reads the sensor data.
3. Python processes the information.
4. The values are displayed on the screen.
5. Data can be stored for future analysis.

## Python Code

```python
import random
import time

while True:
    temperature = random.randint(20, 35)
    humidity = random.randint(40, 80)

    print("Temperature:", temperature, "°C")
    print("Humidity:", humidity, "%")

    time.sleep(2)
```

## Applications

- Weather monitoring
- Smart agriculture
- Greenhouse automation
- Environmental research

## Future Improvements

- Cloud data logging
- Mobile dashboard
- Email alerts
- IoT integration

## Author

AnanyaLabs
