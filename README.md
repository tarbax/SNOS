# Sensor Node On Steroids
#
#
# ARCHIVED: read below 
i could not get it right as a diy version with this many improvements this was my mean intestion but after 6 revisions i had to ditch the diy path
had issues with to high cost, hard to solder and temperature sensor had a very large drift from the board heating up.
#
#
#
### What?

so after running the Bruh Multisensors for 2 years it was time to upgrade!

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

i have hopefully the final revision in house around 2nd week of march (waiting on jlcpcb order)

### Parts List UNTESTED YET!
**Aliexpress** (affiliate links)
- [ ] SNOS board
- [x] [NodeMCU 1.0](https://s.click.aliexpress.com/e/_dSPnV6D) option cp102
- [x] [DHT22 Module](https://s.click.aliexpress.com/e/_dX0VELn) [(5x)](https://s.click.aliexpress.com/e/_dSR0BZR) [(10x)](https://s.click.aliexpress.com/e/_dTHlqxf)

    OR  
    
- [x] SHT30 Module

    OR 
    
- [ ] [BME280 Module](https://s.click.aliexpress.com/e/_dUFCwbJ) [(10x)](https://s.click.aliexpress.com/e/_dXqmLUl)
- [x] [CCS811 Module](https://s.click.aliexpress.com/e/_d9deomd) [(10x)](https://s.click.aliexpress.com/e/_d8LB1Kt)
- [ ] LDR Photoresistor Module

    OR
    
- [x] [BHP1570](https://s.click.aliexpress.com/e/_dY1WFdX) [(10x)](https://s.click.aliexpress.com/e/_d8COgN3)
- [x] [WS1812b Led](https://s.click.aliexpress.com/e/_d7BmdCN)
- [x] [AM312 Mini PIR Sensor](https://s.click.aliexpress.com/e/_dUSQcW5) [(5x)](https://s.click.aliexpress.com/e/_d81pmW5) [(10x)](https://s.click.aliexpress.com/e/_dTI8JVJ)
- [ ] piezo buzzer
- [ ] [3p 5mm terminal](https://s.click.aliexpress.com/e/_dZ96QS5)

#### types of temperature sensors sorted by accuracy from less to highest accuracy

|     type      |     Temperature    |      Humidity       | price +/- |                     note                    |
| ------------- | ------------------ | ------------------- | ------ | ------------------------------------------- |
|     DHT22     | ±0.5 @ -40 ->125 °C | ±5   @  0-100%  RH |  2,4 € | -- no Air quality sensor. -- temp accuracy may be worse|
|     BME280    | ±1   @ -40 ->85  °C | ±3   @ 20-80%   RH |  2   € | bonus pressure sensor (300Pa-1100hPa ±1 hPa)|
|     SHT30     | ±0.3 @   0 ->65  °C | ±3   @ 10-90%   RH |  1,9 € |                                             |
|     SHT31     | ±0.2 @ -40 ->90  °C | ±3   @ 10-100%  RH |  3,5 € |                                             |
|     SHT35     | ±0.1 @  20 ->60  °C | ±1.5 @  0-80%   RH |  9   € |                                             |

### Got questions?

- Home Assistant [Community Forum](https://community.home-assistant.io/t/snos-sensor-node-on-steroids/)

### Finale
is there any requests for next revision or even a esp32 version ? like nfc, more leds, display, …
This will be published with instructions once the design is finalized

Don’t hesitate to share your feedback or your ideas of improvement!
Have fun :+1:

<a href="https://www.buymeacoffee.com/tarbax" target="_blank"><img src="https://cdn.buymeacoffee.com/buttons/default-orange.png" alt="Buy Me A Beer" style="height: 51px !important;width: 217px !important;" ></a>
