# Sensor Node On Steroids
### What?

so after running Bruh Multisensors for 2years possibly it was time to upgrade!

This project is a relative easy way to get started with your own SNOS Multisensor with ESPhome firmware.

This project requires **soldering !**

### Why?

I wanted a smaller and more smart sensor so i get to the drawing board.
Decided to start of with a esp8266 amica

### my wish list:

Motion sensor
Accurate temperature and humidity sensor
Light sensor (bh1750 or/both LDR )
Air quality sensor (aiq, tvoc, eCO2 )
Better led notification (brightness and colour saturation)
Sound notification
External temperature sensor (for monitoring entertainment closet, water temp, fridge,…)
now you probably going to say this cant be possibly smaller than the awesome Bruh Multisensor
but your wrong is roughly half the size!

### pictures:

i created a daughterboard that will fit this all
![alt text](https://community-home-assistant-assets.s3.dualstack.us-west-2.amazonaws.com/original/3X/8/f/8f68f64889ca64955a9f1a51cd59972b41a57870.jpeg?raw=true "pcb")

comparison with a Bruh Multisensor:

![alt text](https://community-home-assistant-assets.s3.dualstack.us-west-2.amazonaws.com/original/3X/9/4/94a146183faba7578926db0bbe43dd35c51e2de5.jpeg?raw=true "pcb")

i have hopefully the final revision in house within 3 weeks (waiting on jlcpcb order)

### Parts List
**Aliexpress**
- [SNOS board](http://geni.us/)
- [NodeMCU 1.0](http://geni.us/)
- [DHT22 Module](http://geni.us/)
    OR
- [SHT3x Module](http://geni.us/)
- [CCS811 Module](http://geni.us/)
- [LDR Photoresistor Module](http://geni.us/)
    OR
- [BHP1570](http://geni.us/)
- [WS1812b Led](http://geni.us/)
- [AM312 Mini PIR Sensor](http://geni.us/)
- [piezo buzzer](http://geni.us/)
- [3p 5mm terminal](http://geni.us/)

#### types of temperature sensors sorted by accuracy from less to highest accuracy

|     type      |     Temperature    |      Humidity       | price +/- |                     note                    |
| ------------- | ------------------ | ------------------- | ------ | ------------------------------------------- |
|     DHT22     | ±0.5 @ -40 ->125 °C | ±5   @  0-100%  RH |  2,4 € | -- no Air quality sensor. -- temp accuracy may be worse|
|     bme280    | ±1   @ -40 ->85  °C | ±3   @ 20-80%   RH |  2   € | bonus pressure sensor (300Pa-1100hPa ±1 hPa)|
|     SHT30     | ±0.3 @   0 ->65  °C | ±3   @ 10-90%   RH |  1,9 € |                                             |
|     SHT31     | ±0.2 @ -40 ->90  °C | ±3   @ 10-100%  RH |  3,5 € |                                             |
|     SHT35     | ±0.1 @  20 ->60  °C | ±1.5 @  0-80%   RH |  9   € |                                             |

### Finale
is there any requests for next revision or even a esp32 version ? like nfc, more leds, display, …
This will be published with instructions once the design is finalized

Don’t hesitate to share your feedback or your ideas of improvement!
Have fun :+1:
