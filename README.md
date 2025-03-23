🚗 Smart Parking System (4 Slots)

This Arduino-based Smart Parking System detects vehicle parking using IR sensors and displays slot availability on an LCD screen. A servo motor controls the gate, opening when a vehicle enters and closing after it exits.

🛠 Components Used
- Arduino UNO
- Servo Motor (for gate control)
- IR Sensors (to detect cars)
- I2C LCD Display (to show parking status)
- Jumper Wires

🔧 How It Works
1. IR sensors detect cars in 4 slots.
2. The LCD screen shows available and occupied slots.
3. If a car enters and slots are available:
   - The servo motor opens the gate.
   - The available slot count updates.
4. If a car **exits, the slot count increases.
5. The servo closes automatically after each action.

🚀 Code Overview
- Setup: Initializes sensors, LCD, and servo motor.
- Loop: Continuously checks slot availability and updates the LCD.
- IR Sensor Readings: Detects occupied or empty slots.
- Servo Control: Opens/closes gate based on car entry/exit.

🔌 How to Use
1. Connect all components as per the circuit diagram.
2. Upload the code to Arduino UNO using Arduino IDE.
3. Power the system and check the LCD display.
4. Place an object in front of an IR sensor to simulate a car.
5. Watch the servo motor open and close the gate automatically.

📌 Future Improvements
- IoT integration for remote monitoring.
- RFID access control for automated parking.
- Payment system for smart parking fees.
