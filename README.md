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

Button component:
 - Button 
    - GPIO 2 and GND


![BUTTON](https://user-images.githubusercontent.com/111941742/206001918-a88c5148-4b2b-4d8e-bf20-770fc5234b5b.jpg)


LED components:
 - Blue LED 
     - GPIO 13 and GND  
 - Red LED
    - GPIO 26 and GND 


![LEDs](https://user-images.githubusercontent.com/111941742/206002096-9cedcd59-df94-4675-845b-c2893dce13f1.jpg)

Distance sensor component:
- DistanceSensor (GPIO 23, GPIO 24)
   - Raspberry Pi:
    - GPIO 23, GPIO 24 and GND


![DistanceSensor](https://user-images.githubusercontent.com/111941742/206002285-104a0a3d-eeb4-4911-a17d-624c7ed5e23c.jpg)


Consollidated Images:
 
 
 ![Image 1](https://user-images.githubusercontent.com/111941742/205985015-fcab7f05-2eae-4a39-a202-61a158d79100.jpg)


![Image 2](https://user-images.githubusercontent.com/111941742/205984990-b43e04e9-0a53-4dc2-be80-697d4215b944.jpg)


![Image 3](https://user-images.githubusercontent.com/111941742/205985046-9201b1ea-e719-4e97-99dc-ec0686599bf8.jpg)
