# Night Patrol Robot

### Project Overview
The Night Patrol Robot is an autonomous security system designed for nighttime surveillance. It patrols predefined areas and detects intrusions through sound and infrared sensors. The robot is equipped with a night vision camera to monitor its surroundings and stream real-time video using an IoT server. It uses embedded systems technology, integrating sensors, ESP32 microcontroller, and motor drivers to automate the patrol process with minimal human intervention.

### Features
- **Automation**: Fully automated patrol robot for night surveillance.
- **Real-time Monitoring**: Equipped with an ESP32-CAM for live video streaming.
- **IR and Sound Sensors**: Detects obstacles and movements using infrared and sound sensors.
- **Obstacle Avoidance**: Automatically stops or reroutes when an obstacle is detected.
- **Wireless Communication**: Controlled via an IoT app, allowing remote monitoring and movement control.
- **Night Vision Camera**: Monitors the surroundings with a 360-degree rotating camera.

### Hardware Used
- **ESP32-CAM**: For video streaming and image capturing.
- **L293D Motor Driver**: Controls the robot's movement.
- **Infrared Sensors**: Helps the robot follow predefined paths and detect obstacles.
- **Buzzer**: Sounds an alert when an obstacle or movement is detected.
- **DC Motors**: Powers the movement of the robot’s wheels.
- **Sound Sensors**: Detects unusual sounds in the environment.

### Software
- **Arduino IDE**: Used for programming the microcontroller.
- **Embedded C**: Coding for sensor integration and automation.
- **Express PCB**: For designing the circuit boards.
- **IoT Server**: Used for live video streaming and remote control.

### How It Works
1. **Patrol Mode**: The robot follows a predefined path using IR sensors, scanning the area with its camera.
2. **Intruder Detection**: Upon detecting any movement or sound, the robot stops, activates its buzzer, and alerts the control room.
3. **Live Monitoring**: A 360-degree rotating night vision camera streams real-time video to an IoT server, allowing security personnel to monitor the area remotely.
4. **Obstacle Avoidance**: The robot uses IR sensors to avoid collisions, rerouting its path if needed.

### Installation
1. Clone the repository:
    ```bash
    git clone https://github.com/vaishnavisamboji/Night-Patrol-Robot.git
    ```
2. Open the project in the Arduino IDE.
3. Upload the code to the ESP32-CAM board.
4. Set up the IoT server to receive live video streams.
5. Install the necessary hardware components following the circuit design provided in the repository.

### Future Enhancements
- **GPS Integration**: To enable location-based monitoring and real-time tracking.
- **Gas and Fire Detection**: Adding sensors for enhanced safety monitoring.
- **Mobile Application**: Develop a user-friendly app to control and monitor the robot remotely.
