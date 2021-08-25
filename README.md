## Overview

* Created a portable system to check body temperature and detect Face Mask.
* The system can be implemented in places where people are gathering in large number and people need to wear facemasks as it will help in reducing any chance of spreading the virus.
* Person will stand in front of a Camera which will detect if the person is wearing mask or not and an infrared temprature sensor will detect the temperature.
* If the person is wearing mask and has body temperature under certain threshold (37 C/ 98.6 F) the gates will open else, administrator will be informed about the situation using an E-mail service. 

Equipments needed:
- Raspberry pi (any model 3)
- 9MLX9061 temperature sensor.
- Screen for displaying message.
- Buzzer
- LEDs (green, red)
- Servo Motor for door.

On system(Using Laptop)
* Run the facemask_train python file to train the model. // need to train once.
* Run detection python file to detect the face mask.
* Run datasend python file to send the data collected to Raspberry. (You need to change the ip accordingly) 

On Raspberry pi
- Run temperature.py.
