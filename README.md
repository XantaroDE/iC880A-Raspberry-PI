# Raspberry PI + IMST iC880A Gateway Shield



<img src="https://raw.githubusercontent.com/XantaroDE/iC880A-Raspberry-PI/master/pictures/RPI-Lora-Gateway-Shield.installed.jpg" alt="Installed" width="600">   

Based on the idea of [ch2i][1], but complete rework.

This PCB is used to connect Raspberry PI and ISMT [iC880A][2] LoraWan concentrator Gateway (SPI version) togehter and to be able to put the whole thing into a outdoor enclosure. Power can be supplied via passive or active PoE adapters.

:warning: **Use at your own risk, always check your layout before manufacturing!**

## Features

 - highvoltage power regulator for passive PoE -48V usage based on LM2576
 - optional use DC/DC module for active PoE adapters with +12V output
 - BME280 header for temperature & humidity measurement within the housing, optional BMP280
 - DS18S20 Header for outside & inside/case sensor
 - added GPS module for time & PPS sync
 - optional +3V3 -> +5V TTL serial converter, could be used for other sensors like [SDS011][3] dust particle sensor 
 - LC filters on power supply rails
 - LED for GPS PPS and signal routed to GPIO25
 - DS1307 RTC hardware clock for Raspberry + Battery 

## Schematic


![schematic](https://raw.githubusercontent.com/XantaroDE/iC880A-Raspberry-PI/master/pictures/RPI-Lora-Gateway-Shield.sch.png)<br>
[PDF download](https://raw.githubusercontent.com/XantaroDE/iC880A-Raspberry-PI/master/pictures/RPI-Lora-Gateway-Shield.sch.pdf)

## Board

**Top side**

<img src="https://raw.githubusercontent.com/XantaroDE/iC880A-Raspberry-PI/master/pictures/RPI-Lora-Gateway-Shield.top.jpg" alt="PCB TOP" width="400">    

**Bottom side**

<img src="https://raw.githubusercontent.com/XantaroDE/iC880A-Raspberry-PI/master/pictures/RPI-Lora-Gateway-Shield.bot.jpg" alt="PCB BOT" width="400">    


You can order the PCB of this board at [elecrow][4] with the supplied gerbers.

## License

<img alt="Creative Commons Attribution-NonCommercial 4.0" src="https://i.creativecommons.org/l/by-nc/4.0/88x31.png">   

This work is licensed under a [Creative Commons Attribution-NonCommercial 4.0 International License](http://creativecommons.org/licenses/by-nc/4.0/)    
If you want to do commercial stuff with this project, please contact [Xantaro Deutschland GmbH](https://www.xantaro.net) so we can organize an simple agreement.

 
[1]: https://github.com/ch2i/iC880A-Raspberry-PI/
[2]: http://webshop.imst.de/ic880a-spi-lorawan-concentrator-868mhz.html
[3]: https://luftdaten.info/
[4]: https://www.elecrow.com/pcb-manufacturing.html
