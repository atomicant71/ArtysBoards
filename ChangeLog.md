# Changelog for Artys SRS MB5 Board
The board variant is derived  from Adafruit Trinket M0
## V 1.0.0 2022.03.02

First Release bor board SRS_MB5

## V 1.0.1 2022.03.03

* Change LED_BUILTIN port

## V 1.0.2 2022.03.11

 * Same feature of thre prevoous version bua added versioning in package_artys_index.json
 
## V 1.0.3 2022.03.29
 
 * I2C working on sercom3  
 
### modification details

PinDescription added 2 items now has 24 items: 
 * PinDescription[0] (I2c SDA) on PORTA 22
 * PinDescription[2] (I2c SCL) on PORTA 22
 * PinDescription[9] on PORTA 7 (PORTA 28 used for led)
 * PinDescription[12]same as PinDescription[13]
 * PinDescription[13] (LED BUILTIN) on PORTA 28
 * PinDescription[23] on PORTA 19 EN3
 * PinDescription[24] on PORTA 10 DIR_U
