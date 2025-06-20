## Setup Guide

> For detailed hardware setup and required components, please refer to the project report.

![Pet Robot Screenshot](https://raw.githubusercontent.com/Ilmaa2003/Pet-Robot/main/Images/Screenshot%202025-02-20%20092318.png)

![Pet Robot Screenshot](https://raw.githubusercontent.com/Ilmaa2003/Pet-Robot/main/Images/Screenshot%202025-02-20%20092806.png)

---

### Software Setup (Arduino IDE)

1. **Install Arduino IDE**  
   Download and install the latest version of the Arduino IDE from:  
   [https://www.arduino.cc/en/software](https://www.arduino.cc/en/software)

2. **Open the Project**  
   Launch the Arduino IDE and open the provided project folder containing the `.ino` source file.

3. **Install Required Libraries**  
   Navigate to **Sketch → Include Library → Manage Libraries**, and install the following libraries if not already installed:
   - `Servo`
   - `NewPing`
   - `SoftwareSerial`

4. **Connect the Arduino Board**  
   Connect your Arduino board to your computer using a USB cable.

5. **Select the Board and Port**  
   - Go to **Tools → Board** and choose the correct Arduino model (e.g., Arduino Uno).  
   - Then go to **Tools → Port** and select the COM port associated with your device.

6. **Upload the Code**  
   Click the **Upload** button or press `Ctrl + U` to compile and upload the sketch to the Arduino board.

7. **Bluetooth Communication**  
   To control the robot wirelessly, use a Bluetooth terminal app (on a smartphone or PC) to send commands to the Arduino over Bluetooth.

---
