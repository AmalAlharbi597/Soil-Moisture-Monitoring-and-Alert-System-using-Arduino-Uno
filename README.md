# Soil-Moisture-Monitoring-and-Alert-System-using-Arduino-Uno


This project utilizes an Arduino Uno board to measure soil moisture levels using a soil moisture sensor. When the moisture level drops below a predefined threshold, the system alerts the user by lighting up a red LED and activating a buzzer. If the soil moisture is sufficient, a green LED lights up to indicate no watering is required.




Components Used:
Arduino Uno Board:
-The main microcontroller board for the project.

-Soil Moisture Sensor:
Measures the moisture level in the soil and sends the data to the Arduino.

-Red LED:
Lights up when the soil moisture level is low to alert the user.

-Green LED:
Lights up when the soil moisture is sufficient.

-Buzzer:
Produces a sound alert when the soil moisture level is low.

-Resistors:
Two resistors (330Ω) to regulate the current to the LEDs.


-Jumper Wires:
For connecting the components to the Arduino board.
Breadboard:
To organize and connect the components easily.


![Frantic Esboo](https://github.com/user-attachments/assets/70f68536-e760-4409-96f9-7225f4dbe944)













How the Project Works:


The soil moisture sensor measures the soil's moisture level and sends the reading to the Arduino.
If the moisture level is below the threshold (200 in the code):
The red LED turns on.
The buzzer activates.
If the moisture level is above the threshold:
The green LED turns on.
The buzzer remains off.
The moisture level readings are displayed on the Serial Monitor in the Arduino IDE.
