# Weather station
## Introduction
A weather station is a facility, either on land or sea, with instruments and equipment for measuring atmospheric conditions to provide information for weather forecasts and to study the weather and climate.

## Details
In this project the sensing of pressure, temperature, humidity, light level and rain is sensed by various sensors and data of each sensor can be collected and recorded.
### Sensors used are as follows:
1.	Air temperature and atmospheric pressure using a Bosch BMP180 breakout board
2.	Air humidity using a DHT11
3.	Light level using a LDR (light dependent resistor)
4.	Rain sensing

### List of components used:
1.	ATMEGA328P
2.	Microcontroller w/ Arduino bootloader
3.	DHT11 temperature/humidity sensor
4.	BMP180 Pressure/temperature sensor
5.	Rain Sensor a breakout board + a bare pcb with some exposed copper traces
6.	Pololu U1V11F5 Boost converter, input 0.5V to 5.5V, output 5V
7.	LDR Visible light level sensor
8.	Cristal oscillator 16MHz, for Arduino
9.	22pF capacitor for filtering the Arduino crystal oscillator
10.	Micro SD card module


## Future scope of developement
One of the comments made for the project showed very interesting application as battery life monitor. A battery-endurance test, featuring a solar panel to charge the Li-ion cell back. They were able to gather some data, showing that the solar radiation available during the day was not enough to recharge the batteries. Or maybe my hardware concept is not working that well.
![image](https://user-images.githubusercontent.com/88575247/174485000-50fe5196-66a0-4399-b4f4-9c3050c2468c.png)
