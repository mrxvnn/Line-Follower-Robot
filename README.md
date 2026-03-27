# Line-Follower-Robot
An advanced line-following robot with PID-based error correction. Uses analog sensors to detect lines and adjust motor speed for precise navigation. Designed with modular hardware and virtual simulation in Webots for testing and optimization.

**Components & Supplies**
Arduino Nano & I/O Shield
5 × CNY70 sensors (analog line detection)
2 × GP1A01 IR sensors (similar to FC-03)
L298N Dual H-Bridge Motor Driver
2 × DC motors with gearbox & encoder
2 × 18650 3.7V 4200mAh batteries + holder
2-tier circular acrylic chassis, wheels, LEDs, resistors, jumper wires, and pushbutton

**Tools & Machines**
Multitool & screwdriver
Soldering iron & lead-free solder

**Features**
PID-based line following (P & D constants active, I pending)
Analog sensor calibration for optimal line detection
Modular track design for custom courses
Simulation in Webots using Arduino-based control code

**How It Works**
5 analog CNY70 sensors read line position
Arduino interprets sensor data and adjusts motor speeds using PID feedback
Motors powered by series 18650 batteries, control logic powered via 5V USB charger
Physical design and track templates built in TinkerCAD, testable virtually in Webots

