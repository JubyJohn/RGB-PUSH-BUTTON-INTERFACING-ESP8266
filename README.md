# RGB-PUSH-BUTTON-INTERFACING-ESP8266

## AIM
To blink different colors of RGB sensor by push button count


## COMPONENTS
1.	ESP8266 NodeMCU
2.	RGB Sensor
3.	Push Button
4.	Jumper Wire
5.	USB cable


## CONNECTION

### RGB Sensor Module Pin Diagram

![rgb module](https://github.com/JubyJohn/RGB-PUSH-BUTTON-INTERFACING-ESP8266/assets/81866407/7bae2dd7-9795-493a-9625-d78daa90552b)
 

<br>  - = Ground  ---->  GND
         <br> B   ---->  D2
         <br> G   ---->  D1
         <br> R   ---->  D0

### Push Button Pin Diagram

![push-button-module](https://github.com/JubyJohn/RGB-PUSH-BUTTON-INTERFACING-ESP8266/assets/81866407/b68e81e9-fb72-4a2a-a38b-9a1450fa35b7)

 
<br>  S = Output     ---->  D5
<br>  middle  = power supply  ---->  3V3
<br>  –  = ground          ---->  GND


## PROCEDURE

<br> Step 1 : Interface ESP8266 microcontroller to Arduino IDE using port.
<br> Step 2 : Interface ESP8266 microcontroller with push button and print the digital values on serial monitor.
<br> Step 3 : Interface ESP8266 microcontroller with RGB Sensor to blink red,green,blue light with delay.
<br> Step 4 : Interface ESP8266 microcontroller with RGB Sensor and push button by modifying both the programs.


## OUTPUT

<br> When push button is pressed:
<br> &ensp;&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;          On first press, red light turned on
<br> &ensp;&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;          On second press, green light turned on
<br> &ensp;&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;          On third press, blue light turned on
<br> &ensp;&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;          On fourth press, rgb led turned off and the pattern repeated.


