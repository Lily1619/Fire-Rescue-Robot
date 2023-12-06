# Fire-Rescue-Robot
This project implements a Fire Rescue robot with Bluetooth control and a mounted camera. The robot is designed to move forward, backward, turn left, and turn right. 
The camera can pan left, pan right, tilt up, and tilt down. The entire system is controlled via Bluetooth communication.

**Hardware Requirements**:
1.Arduino board

2.18 servo motors (3 servos per leg for hexapod movement, 2 servos for camera control)

3.Bluetooth module

4.Camera module

5.Power supply for servos

6.Hexapod chassis and structure

**Software Requirements:**

Arduino IDE

**Installation and Configuration:**
1.Connect the servo motors to the designated pins on the Arduino board.

2.Connect the Bluetooth module to the designated pins for RX and TX on the Arduino board.

3.Connect the camera module to the Arduino board.

4.Open the Arduino IDE and upload the provided code (hexapod_with_camera.ino) to the Arduino board.

5.Power on the hexapod robot and ensure that all connections are secure.

6.Pair your Bluetooth device with the Bluetooth module on the hexapod.

7.Use a serial terminal on your Bluetooth-connected device to send commands for controlling the hexapod and camera.

**References:**
1.The Bluetooth app is  https://electronoobs.com/eng_robotica...

2. code reference is  https://electronoobs.com/eng_robotica...
