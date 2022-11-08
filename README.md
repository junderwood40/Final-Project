# Final-Project
CIS2020601 Fundamentals of Unix


![image](https://user-images.githubusercontent.com/111941742/200641493-dae0a715-575b-4ad0-9358-1f44bd252ab5.png)

from gpiozero import DistanceSensor, LED
from signal import pause

sensor = DistanceSensor(23, 24, max_distance=1, threshold_distance=0.2)
led = LED(16)

sensor.when_in_range = led.on
sensor.when_out_of_range = led.off

pause()

