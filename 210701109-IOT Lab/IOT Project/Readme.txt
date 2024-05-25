ABSTRACT:

This project introduces an advanced Drowsiness detection for car drivers system by using Arduino and infrared sensor technology. Statistics highlight the substantial impact that fatigued driving plays in a number of traffic incidents that result in serious injuries and fatalities. Fatigued driving is a major cause of road accidents. To avoid potential accidents caused by drivers falling asleep, a great deal of testing has been conducted to develop systems that can assess driver tiredness and send out alerts beforehand. Vehicle-based measurements have been the focal point of many conventional techniques' system designs; nevertheless, these metrics are heavily impacted by variables including road conditions, vehicle type, and driving skill. On the other hand, other approaches have included psychological tests in their systems, which leads to a more accurate determination of the driver's level of exhaustion. In our suggested method, we measure the driver's level of exhaustion by using the eye closure ratio as an input parameter. When the eye closure ratio deviates from the expected value, a buzzer is used to notify the driver. The main component of the system is a Raspberry Pi, which is used to take pictures of the driver's eyes using a Raspberry Pi cam.


MATERIALS REQUIRED:

Hardware Requirements:
Arduino Uno: A microcontroller board that will collect sensor data and send it to the ESP32 via serial communication.
board based on your project needs and available options 
Buzzer : An audio signaling device such as a buzzer, beeper, or other similar device can be 
electromechanical, piezoelectric, or mechanical. Its main job is to transform audio impulses 
into sound. Depending on the design, it can produce a variety of sounds, including sirens, 
music, bells, and alarms.
Eye blink sensor : This eye blink sensor detects fluctuations in the eye with each blink by using infrared technology to identify eye blinks. When the eye is closed, its output registers as high; otherwise, it registers as low.
Power Supply: Provides power to the Arduino Uno and ESP32 board. A USB cable connected to your computer or a dedicated power supply can be used.



Software Requirements:

Arduino IDE: Integrated Development Environment (IDE) used to write and upload code to the Arduino Uno and ESP32 boards. * **Blynk App:** Mobile application for creating a user interface to visualize sensor data. Download it from the App Store or Google Play Store.
Library Library: 
IRremote Library (Arduino): Controls Infrared (IR) devices like TVs with your Arduino.
Two-way Street: Decode IR signals from remotes (understand commands) and transmit IR signals (control devices).
Protocol Savvy: Works with various IR remote protocols (NEC, Sony, etc.).
Simple Use: Easy-to-learn functions for sending and receiving IR codes.
Open Source: Free and constantly updated on GitHub.
Board Friendly: Compatible with many Arduino boards (Uno, Mega, Nano, etc.).


WORKING OF THE PROJECT:
1.Data Collection: Multiple sensors, including cameras (for eye and facial monitoring), wearable devices (measuring heart rate and other physiological indicators), and vehicle-based sensors (tracking steering patterns and lane deviations), collect real-time data on the driver’s condition.

2. Data Transmission: These sensors transmit the collected data to a central processing unit via the IoT platform. The IoT platform ensures secure and reliable communication between the sensors and the processing unit.

3. Data Processing and Analysis: The central processing unit uses machine learning algorithms to analyze the incoming data. It looks for patterns and signs of drowsiness, such as prolonged eye closure, slow reaction times, irregular heart rates, and erratic driving behaviors.

4.Drowsiness Detection: When the system detects signs of drowsiness, it evaluates the severity based on pre-set thresholds and the analyzed data patterns.

5.Alert Mechanism: If drowsiness is detected, the system triggers an alert mechanism to warn the driver. This can include visual alerts on a dashboard display, auditory alerts through the vehicle's sound system, and haptic feedback such as vibrations in the steering wheel.