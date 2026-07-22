# Arduino Environmental Monitoring System 🌿
A low-cost Arduino-based environmental monitoring system designed to measure atmospheric carbon dioxide (CO₂), air temperature, and relative humidity. The system acquires measurements using the Sensirion SCD30 CO₂ sensor and Adafruit SHT40 temperature and relative humidity sensor, displays the readings in real time through the Arduino Serial Monitor, and simultaneously records the data to a microSD card in CSV format for subsequent analysis.

The system is built on a Geekcreit Arduino Uno R3-compatible microcontroller and integrates multiple digital sensors using the I²C communication protocol, while the DFRobot microSD card module communicates via the SPI interface to provide reliable local data logging.

The project demonstrates the development of a low-cost environmental monitoring platform capable of real-time environmental sensing and local data storage.

## About

This project was developed as a mid-semester project to demonstrate the design, assembly, programming, and testing of a low-cost environmental monitoring system.

The main objectives were to:

- Measure atmospheric CO₂ concentration.
- Measure air temperature and relative humidity.
- Display sensor readings in real time.
- Store the acquired measurements on a microSD card.
- Verify successful sensor communication and data logging.

## Hardware

The system consists of:

- Geekcreit Arduino Uno R3-compatible microcontroller
- Sensirion SCD30 CO₂, temperature, and relative humidity sensor
- Adafruit SHT40 temperature and relative humidity sensor
- DFRobot Fermion microSD card module
- 16 GB microSD card


## Repository Files

- `Arduino_Code.pdf` — Arduino program used to operate the system
- `Bill_Of_Materials.pdf` — components, connections, costs, and product references
- `Hardware_Wiring_Diagrams.pdf` — physical wiring diagram and system wiring schematic
- `Final_Project_Report.pdf` — complete mid-semester project report

## System Output

The system records:

- Elapsed time
- CO₂ concentration in ppm
- SCD30 temperature in °C
- SCD30 relative humidity in %
- SHT40 temperature in °C
- SHT40 relative humidity in %

The measurements are saved in CSV format for subsequent analysis.

## Possible Applications

- Indoor air quality monitoring
- Laboratory environmental monitoring
- Greenhouse monitoring
- Educational demonstrations
- Environmental data acquisition

## Future Improvements

Future development may include wireless communication, cloud-based data storage, additional environmental sensors, battery or solar power, and long-term field testing.

## Author

**Mary Mitchell**

Ben-Gurion University of the Negev

## License

This project is available under the MIT License.
