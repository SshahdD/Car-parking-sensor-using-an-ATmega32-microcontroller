# Car-parking-sensor-using-an-ATmega32-microcontroller
This project implements a car parking sensor system using the ATmega32 microcontroller, ultrasonic sensor (HC-SR04), 16x2 LCD, RGB LEDs, and buzzer. The system measures the distance between the vehicle and obstacles in real-time, providing visual and auditory warnings to assist drivers in parking safely.

The ultrasonic sensor emits ultrasonic waves and calculates the distance based on reflected signals. The measured distance is displayed on the LCD in centimeters, with a special message "Stop" when the obstacle is closer than 5 cm. The system features dynamic LED indicators that change based on proximity: all LEDs flash and the buzzer sounds when an obstacle is within 5 cm; LEDs turn ON/OFF progressively as the distance increases, providing intuitive visual cues. The buzzer also activates as an alert for very close obstacles.

This layered architecture leverages GPIO, ICU, LCD, LED, and Buzzer drivers to create a comprehensive obstacle detection and warning system, enhancing parking safety.
