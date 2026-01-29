# Speedtrack-System
SpeedTrack System is a microcontroller-based project using the 8051 to measure speed. It calculates the time taken by an object to travel between two IR sensors placed at a fixed distance and displays the speed on a 16x2 LCD. It's useful for traffic monitoring and educational purposes.

🎯 Project Objectives

* Measure and display vehicle speed accurately
* Monitor speed in real time
* Enhance safety and system reliability

🧠 Core Components

AT89C51 (8051 Microcontroller) – Main control unit 
IR Obstacle Sensors – Detect vehicle movement and calculate speed
LM016L LCD Display – Displays speed and system messages
Red LED Indicator – Alerts for over‑speed conditions
Logic Toggles – Control and signal handling

⚙️ How It Works

1. IR sensors detect when a vehicle enters and exits a monitored zone.
2. The microcontroller calculates time taken and determines speed.
3. Speed is displayed on the LCD.
4. If speed exceeds the threshold (e.g., 72 km/h):

   * 🚨 **OVER SPEED** message is shown
   * 🔴 Red LED is activated
5. Otherwise, the system displays **NORMAL SPEED**.

💻 Programming & Technical Skills

Languages:C
Hardware: 8051, IR Sensors, LCD Interfacing
Tools: Keil, Proteus
