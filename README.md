
# Temperature Based Fire Control System

Components Required:

    1. DHT11 (Temperature and Humidity Sensor)
    2. 16x2 Liquid Crystal Display (without I2C)
    3. Arduino Uno R3
    4. Relay Module (JQC3F-5VDC-C)
    5. Buzzer
    6. Potentiometer (8-10K)
    7. Red and Green LEDs (If u want to)
    8. Breadboard,
    9. Wires (as required)





## 🔗 Libraries
1. [DHT.h](https://github.com/RobTillaart/Arduino/blob/master/libraries/DHTlib/dht.h)
2. [LiquidCrystal.h](https://github.com/arduino-libraries/LiquidCrystal)



## Deployment

```bash
  git clone https://github.com/itsxtemper/temp-based-fire-control-system
```





## Connections

1. LCD 
``` 
1. LCD RS pin to digital pin 12
2. LCD Enable pin to digital pin 11
3. LCD D4 pin to digital pin 5
4. LCD D5 pin to digital pin 4
5. LCD D6 pin to digital pin 3
6. LCD D7 pin to digital pin 2
7. LCD R/W pin to GND
8. LCD VSS pin to GND
9. LCD VCC pin to 5V
10.LCD LED+ to 5V through a 220 ohm resistor LCD LED- to GND 
```
2. Relay datapin on D6
3. Buzzer and Red led parallel on D7
4. DHT11 datapin on A0
## Support

For support, email harshprakash06@outlook.com richardkonsam@gmail.com.

