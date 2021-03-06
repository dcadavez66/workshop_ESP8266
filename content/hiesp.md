# Introduction - Hello ESP8266

Like the Arduino, this microcontroller has **GPIO pins** (*General Purpose Input/Output*) to interact with the real world. However, while the Arduino operates at and outputs 5V, **the ESP8266 chip runs at 3.3V**, the same voltage as it's logical outputs. This difference is very important to keep in mind when connecting them to other devices like sensors and motors, because there is the possibility of applying too little voltage and the sensor not being able to operate properly, or applying too much and ending up by frying the components. Caution is always advised. The pins are organized as follows:

![WeMos D1 Mini Pinout](./images/wemos-pinout.jpg)

As you can see there are many types of identifications on each pin, which means the same pin can have more that one function. Not at the same time though.

We advise you to keep this tab open on the side as you will need to reference to it later.

Now lets get our hands on something meaningfull!

[Main Menu](../readme.md) | [Next](./Material.md)