# Light-Detector-Tinkercad

In this project I have made a Light Detector on Tinkercad. The following components were used for making this-

1) Photoresistor
2) LCD
3) Arduino UNO board
4) Piezo Buzzer
5) Red and Green LEDs
6) Slide switch

Now let's see how it works-
The photoresistor receives input in the form of light rays with variable intensity which can be controlled by us. The photoresistor input received is in the form of a 10-bit value (in the range 0-1023) , to process this further and pass it on to the LED , we use the map function to convert it into an 8-bit value ( brings it in the range 0-255). 
Once we have the 8-bit value between 0-255, we put an if condition that if the value is >=150 , the RED LED glows else, the GREEN LED glows. 

The second part of this involves a buzzer, wherein I've coded it such that the intensity of the Buzzer sound will be relative to the photoresistor output value, that is, with increase in light intensity, the buzzer satrts beeping louder. Also, to control the buzzer , we use a ON-OFF slide switch.
