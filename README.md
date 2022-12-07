# Final-Project
CIS2020601 Fundamentals of Unix

## Closeness Sensor for Rasperry Pi
This set up allows the distance sensor to have flashing LEDs when the distance gets withing certain parameters once the button is pushed. The flashing red light starts when distance is between 10 to 15cm.   Then flashing red and blue lights at .25 seconds when distance is between 5 to 10cm. Finally flashing red and blue lights at .1 seconds when distance is 5cm or less.

Resources Needed:
 - Raspberry Pi
 - Breadboard
 - Resistors
 - Components:
    - Red and Blue LEDs
    - Button
    - Distance Sensor
 - Jumper Wires


Install the Button component by connecting the button to the breadboard and using the jumper wires to connect the corresponding positive cable to GPIO 2 and the negative to a GND pin on the Raspberry Pi.

![BUTTON](https://user-images.githubusercontent.com/111941742/206001918-a88c5148-4b2b-4d8e-bf20-770fc5234b5b.jpg)


Install the LED components by connecting the Blue LED to the breadboard and using the jumper wires to connect the corresponding positive cable to GPIO 13 on the Raspberry Pi. Using a resistor going from the negative to the negative power rail then using a jumper cable from the power rail. For the Red LED by connect it to the breadboard and using the jumper wires to connect the corresponding positive cable to GPIO 26 on the Raspberry Pi. Using another resistor going from the negative to the negative power rail. Then using a jumper cable from the negative power rail to a GND pin on the Raspberry Pi. 


![LEDs](https://user-images.githubusercontent.com/111941742/206002096-9cedcd59-df94-4675-845b-c2893dce13f1.jpg)

Install the Distance Sensor by connecting the sensor to the breadboard and using the jumper wires to connect the corresponding positive cables to GPIO 23 and the second positive cable to GPIO 24.  Using a resistor going from the negative using a jumper cable from the negative power rail to a GND pin on the Raspberry Pi. Using another resistor going from the negative using a jumper cable from the negative power rail to a GND pin on the Raspberry Pi.


![DistanceSensor](https://user-images.githubusercontent.com/111941742/206002285-104a0a3d-eeb4-4911-a17d-624c7ed5e23c.jpg)


Consollidated Images:
 
 
 ![Image 1](https://user-images.githubusercontent.com/111941742/205985015-fcab7f05-2eae-4a39-a202-61a158d79100.jpg)


![Image 2](https://user-images.githubusercontent.com/111941742/205984990-b43e04e9-0a53-4dc2-be80-697d4215b944.jpg)


![Image 3](https://user-images.githubusercontent.com/111941742/205985046-9201b1ea-e719-4e97-99dc-ec0686599bf8.jpg)
