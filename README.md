# AUTONOMOSTANK
Building a self-driving tracked tank with an ESP32. It follows a line, detects obstacles with ultrasonic sensors, and aims a laser turret at them. Controlled via PS5 controller or fully autonomous. Includes live FPV camera stream. Self-built and programmed from scratch.

In this project I am building an autonomous tracked tank based on an ESP32 microcontroller. The tank can be controlled manually via a PS5 DualSense Controller over Bluetooth, or switch to fully autonomous mode toggled with the press of a button.
In autonomous mode the tank follows a black line using three IR sensors. Three ultrasonic sensors detect obstacles once one is detected, the tank stops, the self-designed and 3D printed turret rotates via servo motor toward the obstacle and a laser pointer marks it as a visual simulation of a shot. Afterwards the tank avoids the obstacle and independently finds the line again.
Power is supplied by an 11.1V LiPo battery, two BTS7960 motor drivers control the DC motors. As an extension, an ESP32-CAM module transmits a live FPV stream via WiFi. All components were self-assembled, wired and programmed from scratch.
