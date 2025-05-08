

## 📦 Libraries & Resources

This project uses the following Arduino libraries:

- **Adafruit Motor Shield (AFMotor) Library**  
  Used for controlling DC motors via the L293D motor driver shield.  
  👉 [Download AFMotor Library](https://github.com/adafruit/Adafruit-Motor-Shield-library.git)

- **Servo Library**  
  Used to control the servo motor, which acts as the "head" of the robotic car.

All necessary resources and example code are provided in this repository.

---

## 🛠️ Hardware Requirements

To build this robotic car, you will need:

| Component                              | Quantity |
|-----------------------------------------|:--------:|
| TT Gear Motor                          |    4     |
| Servo Motor                            |    1     |
| Ultrasonic Sensor                      |    1     |
| Arduino UNO R3                         |    1     |
| Rubber Tyres for TT Gear Motors        |    4     |
| L293D Motor Driver Shield              |    1     |
| Jumper Wires (Male/Female as required) |   -      |
| Sun Board (A4 size)                    |    1     |
| Bluetooth Module                       |    1     |
| Battery Holder                         |    1     |
| Li-ion Battery (2200mAh/3200mAh)       |    2     |

---

## 📝 Setup Instructions

1. **Install Libraries**
   - Download and add the [AFMotor library](https://github.com/adafruit/Adafruit-Motor-Shield-library.git) to your Arduino IDE.
   - The Servo library is included by default in the Arduino IDE.

2. **Assemble Hardware**
   - Mount the TT gear motors and rubber tyres to the chassis (sun board).
   - Connect the motors and sensors to the L293D motor driver shield and Arduino UNO as per the wiring diagram (refer to the resources folder).
   - Attach the servo motor to act as the head.
   - Connect the Bluetooth module for wireless control (if used).
   - Insert the batteries into the holder and connect to power the system.

---

## 💡 Notes

- Ensure all connections are secure to avoid malfunction.
- The AFMotor library is essential for motor control with the L293D shield.
- The servo motor can be used for scanning or as a pan/tilt head for sensors.
