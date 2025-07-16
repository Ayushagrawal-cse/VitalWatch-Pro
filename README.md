We recently built a basic but functional smart health assistant using Arduino and Python — designed to monitor patient room conditions and potential risks in real-time.

🧰 Technologies Used:
Microcontroller: Arduino Uno
Sensors: DHT11, Flame, Sound, Shock, Reed Switch, Touch, Ball Switch, LDR
Interface: Python GUI built with PyQt5
Libraries: serial, csv, time, sys, and PyQt5 modules (QLabel, QTextEdit, QVBoxLayout, QTimer, etc.)

📊 Key Features:
Real-time data reading from multiple sensors
GUI status dashboard with live updates (Normal, Warning, Critical)
Alerts for fire risk, loud sound, shock, motion, and inactivity
Serial communication with Arduino
Logs and timestamps for basic diagnostics
