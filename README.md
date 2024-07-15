# Line-Following-Robot
A Line-Following Robot (LFR) is an autonomous mobile robot designed to follow a predefined path, usually marked by a visible line on the ground. The line is typically a dark-colored strip on a lighter surface or vice versa, which the robot detects using sensors. The main goal of an LFR is to navigate along this path by continuously adjusting its movements based on sensor readings. These robots are commonly used in industrial automation, logistics, and educational projects to demonstrate concepts of robotics and control systems.

![Line-Following Robot](https://github.com/aryan17-coder/Line-Following-Robot/blob/main/Line-Follower-Robot.jpg)


Components Needed
To build a basic Line-Following Robot, you'll need the following components:

1. Robot Chassis: A platform or frame to hold the components.
2. Microcontroller: Arduino Uno.
3. Line Sensors: Infrared or reflective sensors to detect the line.
4. Motor Driver: L293D to control the robot's motors.
5. Motors and Wheels: To move the robot.
6. Power Source: Batteries to power the robot.


Steps to Build
1. Assemble the Chassis
• Mount the Motors: Secure the DC motors to the chassis using screws or mounting brackets. Ensure they are firmly attached.
• Attach the Wheels: Fix the wheels to the motor shafts. Make sure the wheels are aligned and can rotate freely.
2. Attach Motors and Wheels
• Motor Wiring: Connect the wires from the motors to the motor driver (L293D). The L293D can control the direction and speed of the motors.
• Motor Driver Placement: Secure the motor driver to the chassis, ensuring that it's easily accessible for wiring.
3. Connect Line Sensors
• Sensor Placement: Attach the IR sensors beneath the robot, facing the ground. The sensors should be placed in a line across the front of the robot to detect the line's position.
• Sensor Wiring: Connect the sensors to the microcontroller. Typically, the sensors have three pins: VCC, GND, and OUT. Connect VCC to 5V, GND to ground, and OUT to the digital input pins of the Arduino.
4. Wire the Circuit
• Microcontroller Connections:
    • Connect the motor driver's input pins to the Arduino's digital output pins.
    • Connect the motor driver's power pins to the battery.
    • Connect the sensors' output pins to the Arduino's digital input pins.
    • Ensure all grounds (motor driver, sensors, Arduino) are connected to a common ground.
• Power the Circuit: Connect the battery to the power input of the motor driver and the Arduino. Ensure the voltage is within the acceptable range for all components.
5. Code: Upload the Source Code
Upload the Code: Connect the Arduino to your computer using a USB cable and upload the code using the Arduino IDE.


Testing and Calibration

1. Test the Robot: Place the robot on a track with a visible line. Observe its behavior and ensure it follows the line correctly.
2. Calibrate the Sensors: Adjust the position and sensitivity of the sensors if necessary to improve line detection and following accuracy.


Troubleshooting

1. Check Connections: Ensure all wires are securely connected and there are no loose connections.
2. Power Issues: Verify that the battery is charged and providing sufficient power to the components.
3. Code Adjustments: Modify the code if the robot's behavior is not as expected. Fine-tune the motor control logic and sensor thresholds.
