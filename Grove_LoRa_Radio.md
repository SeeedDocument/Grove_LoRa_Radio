---
title: Grove - LoRa Radio
category: Communication
bzurl: https://www.seeedstudio.com
oldwikiname: Grove - LoRa Radio
prodimagename: Grove-LoRa Radio.jpg
surveyurl: https://www.research.net/r/Grove_LoRa_Radio
sku:  113060006/113060007
---

![](https://github.com/SeeedDocument/Grove_Recorder/raw/master/img/Grove-Recoder.jpg)

Grove - LoRa Radio is a wireless radio LoRa module with Grove Connector based on SX1276, it integrates richful features, like extra long communication, high penetrability, low consumption and etc.

Grove - LoRa Radio can help people to make their applications adapted in a longstanding, remotely and complex terrain condition. The communication of the distance of two LoRa node at least 2KM in a open field by the default antenna, and simultaneously people can add extra antenna to the reserved port.

LoRaWAN™ is a Low Power Wide Area Network (LPWAN) specification intended for wireless battery operated Things in a regional, national or global network. LoRaWAN targets key requirements of Internet of Things such as secure bi-directional communication, mobility and localization services. The LoRaWAN specification provides seamless interoperability among smart Things without the need of complex local installations and gives back the freedom to the user, developer, businesses enabling the roll out of Internet of Things.

Due to the spread spectrum technology, communications with different data rates do not interfere with each other and create a set of "virtual" channels increasing the capacity of the gateway. LoRaWAN data rates range from 0.3 kbps to 50 kbps. To maximize both battery life of the end-devices and overall network capacity, the LoRaWAN network server is managing the data rate and RF output for each end-device individually by means of an adaptive data rate (ADR) scheme.


[![](https://github.com/SeeedDocument/Seeed-WiKi/raw/master/docs/images/300px-Get_One_Now_Banner-ragular.png)](https://www.seeedstudio.com)

##  Features
---
- Using RFM95 module based on SX1276 LoRa®
- Working Voltage:5V/3.3V
- ~28mA(Avg) @+20dBm continuous transmit
- ~8.4mA(Avg)@standby mode
- ~20mA(Avg) @receive mode, BW-500kHz
- Working Temperature:-20 – 70℃
- Interface:Grove - UART(RX,TX,VCC,GND)
- Simple wire antenna or MHF Connector for external high gain antenna
- Working Frequency:868MHz/433MHz
- +20dBm 100 mW Power Output Capability
- Size:20*40mm
- Rate:0.3kps~50kps

##  Interface Function
---
to be improve

## Application Ideas
---
- Food
- Water
- Safety
- Health
- City IoT
- Sensor networks

##Getting Started

After this section, you can make **Grove - LoRa Radio** run with only few steps.

###Preparations

Now we are making a demo for P2P(point to point) communication with the Grove - Lora Radio 433MHz, the Grrove - LoRa Radio 868MHz is the same way to use.

* [Seeeduino Lotus](https://www.seeedstudio.com/Seeeduino-Lotus-ATMega328-Board-with-Grove-Interface-p-1942.html)*2
* [Grove - LoRa Radio 433MHz](https://www.seeedstudio.com/)*2


If this is your first time using [Seeeduino Lotus](https://www.seeedstudio.com/Seeeduino-Lotus-ATMega328-Board-with-Grove-Interface-p-1942.html), please refer to [Seeeduino Lotus's wiki](http://www.seeedstudio.com/wiki/Seeeduino_Lotus_v1.0)

Seeeduino Lotus is fully compatible with Arduino which works as simple as Arduino.

If this is your first time using Arduino, Please put hand on [here](http://arduino.cc) to start your Arduino journey.

###Connecting hardware

[Seeeduino Lotus](https://www.seeedstudio.com/Seeeduino-Lotus-ATMega328-Board-with-Grove-Interface-p-1942.html) is a combination of Seeeduino and Base Shield. We can connect the LoRa Radio module to the D5 socket directly as the below picture shows.

![enter image description here](https://raw.githubusercontent.com/SeeedDocument/Grove-Uart_Wifi/master/img/Grove_uart_wifi_connect.jpg)

As shown below:

![enter image description here](https://raw.githubusercontent.com/SeeedDocument/Grove-Uart_Wifi/master/img/Grove_uart_wifi_connect.jpg)

###Download

Click [here](https://raw.githubusercontent.com/SeeedDocument/Grove-Uart_Wifi/master/res/Grove_uart_wifi_test.zip) to download testing code and decompress it to any folders(e.g. Drive D or desktop)


Now you need simple [configurations for Arduino](https://seeeddoc.github.io/Sketchbook%E7%9A%84%E4%BD%BF%E7%94%A8) sketchbook.

Launch Arduino IDE and click File>Preferences and add absolute location for downloaded testing code at Sketchbook location .

![enter image description here](https://raw.githubusercontent.com/SeeedDocument/Grove-Uart_Wifi/master/img/Grove_uart_wifi_wiki_sketchbook.png)

After configurations, please restart Arduino, click File>Sketchbook and choose grove_uart_wifi_wiki after which testing code will show up.

![enter image description here](https://raw.githubusercontent.com/SeeedDocument/Grove-Uart_Wifi/master/img/Grove_uart_wifi_wiki_sketchbook2.png)

Click Tools>Board to choose Seeeduino Lite and select respective serial port.

Now click Upload(CTRL+U) to burn testing code. Please refer to here for any error prompt and you can also add comment on forum


###Review Results

After upload completed, you can see AP identifier on OLED display.Following AP identifiers are found in our office.

![enter image description here](https://raw.githubusercontent.com/SeeedDocument/Grove-Uart_Wifi/master/img/Grove_uart_wifi_result.jpg)

##Firmware update

Our module board got a firmware burned into it for factory settings, you can burn other firmware to it if you like. Click [here](https://raw.githubusercontent.com/SeeedDocument/Grove-Uart_Wifi/master/res/Grove-Uart_Wifi_Firmware-code.zip) to download source code of factory setting firmware.

###Preparations

* A USB to serial converter is required for firmware updating, you can choose UartSBee V5 we offered if you don't know where to get one.
* A Grove-Jump converting cable is required and we also offered for sale. Click here to check.
* A micro USB cable(type A to type C) is required.

###Connecting hardware

**1.**Connect one end of Grove-Jump converting cable with grove socket on Grove - Uart Wifi and connect other end with UartSBee V5 which shown as following.

![enter image description here](https://raw.githubusercontent.com/SeeedDocument/Grove-Uart_Wifi/master/img/Grove_uart_wifi_firmware_connect.jpg)

**2.**Then connecting cables like following figure:

![enter image description here](https://raw.githubusercontent.com/SeeedDocument/Grove-Uart_Wifi/master/img/Grove_uart_wifi_firmware_connect2.jpg)

###Download burning tools

* [FLASH DOWNLOAD TOOLS](https://raw.githubusercontent.com/SeeedDocument/Grove-Uart_Wifi/master/res/FLASH_DOWNLOAD_TOOLS_v1.2_150512.zip)
* [Bin files of firmware](https://raw.githubusercontent.com/SeeedDocument/Grove-Uart_Wifi/master/res/Grove-uart-wifi-firmware-bin.zip)

###Operation steps

Now make sure you have downloaded burning software and bin file of firmware. Let us start burning to board.

* Press and hold button until red LED indicator light on which indicate it is ready to burn firmware.
* Start executable files in FLASH DOWNLOAD TOOLS files (double click) to make configurations like following steps:

![enter image description here](https://raw.githubusercontent.com/SeeedDocument/Grove-Uart_Wifi/master/img/Grove_uart_wifi_firmware_tools1.jpg)

**1.** Choose desired files from firmware bin file downloaded.

**2.** Check SpiAutoSet.

**3.** Choose respective COM port and BAUDRATE.

###Click to START to burn firmware

* Progress bar will be displayed in firmware-burning process.

![enter image description here](https://raw.githubusercontent.com/SeeedDocument/Grove-Uart_Wifi/master/img/Grove_uart_wifi_firmware_tools2.1.jpg)

* Finally, firmware-burning is done.

![enter image description here](https://raw.githubusercontent.com/SeeedDocument/Grove-Uart_Wifi/master/img/Grove_uart_wifi_firmware_tools3.jpg)



##  Resources
---
*   [Grove - Recorder v1.0 Schematics (Eagle files)](https://github.com/SeeedDocument/Grove_Recorder/raw/master/res/Grove-Recorder_v1.0.zip)

*   [Grove - Recorder v1.0 Schematics (pdf)](https://github.com/SeeedDocument/Grove_Recorder/raw/master/res/Grove-Recorder_v1.0.pdf)

*   [Datasheet ISD1820P.pdf (Chinese)](https://github.com/SeeedDocument/Grove_Recorder/raw/master/res/ISD1820P.pdf)
