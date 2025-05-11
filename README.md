# Automatic Gate Demo Kit 🚗🔐

This Arduino project simulates an automatic gate using a microcontroller (Arduino Uno), an ultrasonic distance sensor, a servo motor, LEDs, and a buzzer.

## 🎯 Features

- 🚶 Detects objects using an ultrasonic sensor.
- 🚪 Opens the gate (servo rotates to 90°) when an object is within 50 cm.
- ⏱️ Closes the gate after 5 seconds if no object is detected.
- 🔴 Red LED turns on when the gate is closed.
- 🔵 Blue LED lights up when the gate is open.
- 🔊 Buzzer beeps continuously when the gate is open.

## 🛠️ Components Used

- Arduino Uno
- Ultrasonic Sensor (HC-SR04)
- Servo Motor
- Red and Blue LEDs
- Buzzer
- Resistors
- Breadboard + Jumper Wires

## 🧠 How It Works

1. The ultrasonic sensor continuously measures distance.
2. When something comes within 50 cm, the gate opens.
3. While open, the blue LED lights up and the buzzer beeps.
4. After 5 seconds of no detection, the gate closes, red LED turns on, and the buzzer stops.

## 👨‍💻 Author

AGAHIRE Nikita 
