🤖 Light Following Robot Using Arduino Uno

📌 Project Insight - 
This project demonstrates a Light Following Robot using an Arduino Uno and LDR (Light Dependent Resistor) sensors. The robot detects the direction of the strongest light source and automatically moves toward it by controlling the motors through a motor driver.

⚙️ Design Details - 
Parameter	Description,
Controller	Arduino Uno, 
Sensors	2 × LDR Sensors, 
Motor Driver	L298N / L293D, 
Actuators	DC Motors, 
Power Supply	Battery Pack, 
Robot Type	Autonomous Light Following Robot.

📖 Working Principle - 
The robot uses two LDR sensors placed on the left and right sides. The Arduino continuously reads the light intensity from both sensors.
If the left LDR detects more light, the robot turns left.
If the right LDR detects more light, the robot turns right.
If both sensors detect equal light intensity, the robot moves forward.
The robot keeps adjusting its direction until it reaches the light source.

🛠️ Components Required - 
Arduino Uno,
LDR Sensors (2),
L298N/L293D Motor Driver,
DC Motors (2),
Robot Chassis,
Wheels,
Battery Pack,
Jumper Wires.

🎯 Objectives - 
Detect light intensity using LDR sensors.
Follow the direction of the light source.
Control robot movement using Arduino Uno.
Demonstrate autonomous navigation.

✅ Advantages - 
Simple and low-cost design.
Autonomous operation.
Easy to implement and modify.
Useful for learning robotics and sensor interfacing.

🚀 Applications - 
Educational Robotics Projects,
Autonomous Navigation Systems,
Light Tracking Systems,
Research and Development,
Sensor-Based Automation,

📊 Result -
The robot successfully detects the brightest light source and moves toward it automatically by adjusting its direction based on LDR sensor readings.

🔮 Future Scope - 
Add obstacle avoidance sensors.
Implement wireless control.
Use solar panels for power.
Integrate AI-based path optimization.

👨‍💻 Tools Used - 
Arduino IDE
Embedded C
Arduino Uno
LDR Sensors
Motor Driver Module



