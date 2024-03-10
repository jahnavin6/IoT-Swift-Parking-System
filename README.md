# Swift Parking System

## Introduction

Swift Parking System (SPS) is designed to alleviate parking challenges in public places and shopping malls by enabling users to find and book vacant parking slots through a mobile application. This IoT-based solution focuses on reducing the time spent searching for parking spaces, thereby cutting down on fuel consumption and carbon emissions. The system uses sensors to detect car presence and a display unit to indicate the availability of each parking space.

## Objectives

- Develop both hardware and software components to detect parking slot occupancy.
- Utilize Arduino for programming and MIT App Inventor 2 for creating an Android application to interface with users.
- Implement a smart parking system using IoT technologies, focusing on ease of use and efficiency.

## Technologies Used

- **Arduino Mega**: Acts as the project's microcontroller.
- **Ultrasonic Sensor**: For detecting the presence of vehicles in parking slots.
- **Servo Motor**: To control the parking barriers.
- **Bluetooth Module (HC-05)**: Enables wireless communication between the system and the user's mobile application.
- **MIT App Inventor**: Used to create the user-facing Android application.

## Features

- **Real-time Parking Availability**: Users can check the availability of parking slots in real-time through the Android app.
- **Automated Parking Barriers**: Controlled entry and exit using servo motors based on parking slot occupancy.
- **Environmentally Friendly**: Reduces unnecessary driving, cutting down on carbon emissions.
- **User-friendly Application**: Easy-to-use mobile application for checking and booking parking slots.

## System Architecture

The Swift Parking System consists of a network of sensors and microcontrollers integrated with an Android application. Ultrasonic sensors are placed in each parking slot to detect the presence or absence of vehicles. The system's status is communicated to the user through a Bluetooth-connected mobile application, providing a seamless and efficient parking experience.

## Getting Started

To set up the Swift Parking System in your location, follow these steps:

1. Install the Arduino IDE and configure the Arduino Mega with the provided code.
2. Assemble the hardware components according to the electrical wiring diagram included in the project documentation.
3. Compile and upload the Arduino sketch to the microcontroller.
4. Install the Swift Parking System application on an Android device.
5. Pair the Android device with the Bluetooth module to start monitoring and booking parking slots.

## Future Enhancements

- Expanding the system to cover more parking lots and integrate with city-wide smart parking solutions.
- Incorporating payment and reservation functionalities into the mobile application.
- Enhancing the system's scalability and reliability for broader deployment.

## Acknowledgements

Special thanks to the G. Narayanamma Institute of Technology & Science (For Women) for supporting this project, and to all faculty members and friends who contributed to its success.

---

For more information and updates, please visit our GitHub repository.
