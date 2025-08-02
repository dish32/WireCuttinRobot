Wire Cutting Robot – Arduino Project
This project is an automated wire cutting robot powered by Arduino. Designed to cut wires to custom lengths entered by the user, it’s perfect for small-scale manufacturing, prototyping, and electronics work. The system increases efficiency by automating repetitive tasks with accuracy and minimal human effort.

🚀 Features
User-defined wire length input via keypad

Real-time status display on a 16x2 LCD

Accurate wire feeding using a stepper motor

Clean cutting action via a servo-controlled blade

IR sensor detection for length tracking

Automatic reset after each cutting cycle

🧠 Technologies Used
Arduino Uno (microcontroller)

Embedded C/C++

Stepper Motor (for feeding wire)

Servo Motor (for blade movement)

IR Sensor (for distance detection)

4x4 Keypad (for user input)

16x2 LCD with I2C Module (for display)

⚙️ How It Works
The user enters the desired wire length and quantity using the keypad.

Input is displayed on the LCD screen for confirmation.

The wire is fed using a stepper motor based on the input length.

Once the target length is reached, the servo blade cuts the wire.

The system repeats until the desired number of pieces is cut.

Finally, the robot resets, ready for a new set of inputs.

Built with simplicity, accuracy, and real-world application in mind, this project showcases the power of Arduino in solving everyday hardware automation problems.


