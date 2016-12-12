---
title: Grove - LoRa Radio
category: Communication
bzurl: https://www.seeedstudio.com
oldwikiname: Grove - LoRa Radio
prodimagename: Grove-LoRa Radio.jpg
surveyurl: https://www.research.net/r/Grove_LoRa_Radio
sku:  113060006/113060007
---

![](https://raw.githubusercontent.com/SeeedDocument/Grove_LoRa_Radio/master/img/LoRa.jpg)

Grove - LoRa Radio is a wireless radio LoRa module with Grove Connector based on SX1276, it integrates richful features, like extra long communication, high penetrability, low consumption and etc.

Grove - LoRa Radio can help people to make their applications adapted in a longstanding, remotely and complex terrain condition. The communication of the distance of two LoRa node at least 2KM in a open field by the default antenna, and simultaneously people can add extra antenna to the reserved port.

Due to the spread spectrum technology, communications with different data rates do not interfere with each other. Data rates range from 0.3 kbps to 50 kbps.

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
- Ready-to-go Arduino libraries
- Resered MHF antenna connector

##  Interface Function
---

![](https://raw.githubusercontent.com/SeeedDocument/Grove_LoRa_Radio/master/img/Interface.jpg)

1. ATMega168 MCU
2. MHF
3. ANT
4. RFM95 Module
5. Grove Interface

## Application Ideas
---
- Food
- Water
- Safety
- Health
- City IoT
- Sensor networks
- Long distance wireless communication

##Getting Started

After this section, you can make **Grove - LoRa Radio** run with only few steps.

###Preparations

Now we are making a demo for P2P(point to point) communication with the Grove - Lora Radio 433MHz, the Grrove - LoRa Radio 868MHz is the same way to use.

* [Seeeduino Lotus](https://www.seeedstudio.com/Seeeduino-Lotus-ATMega328-Board-with-Grove-Interface-p-1942.html)*2
* [Grove - LoRa Radio 433MHz](https://www.seeedstudio.com/)*2


If this is your first time using [Seeeduino Lotus](https://www.seeedstudio.com/Seeeduino-Lotus-ATMega328-Board-with-Grove-Interface-p-1942.html), please refer to [Seeeduino Lotus's wiki](http://www.seeedstudio.com/wiki/Seeeduino_Lotus_v1.0).

Seeeduino Lotus is fully compatible with Arduino which works as simple as Arduino.

If this is your first time using Arduino, Please put hand on [here](http://arduino.cc) to start your Arduino journey.

###Connecting hardware

[Seeeduino Lotus](https://www.seeedstudio.com/Seeeduino-Lotus-ATMega328-Board-with-Grove-Interface-p-1942.html) is a combination of Seeeduino and Base Shield. We can connect the LoRa Radio module to the D5 socket directly as the below picture shows.

![enter image description here](https://raw.githubusercontent.com/SeeedDocument/Grove_LoRa_Radio/master/img/demo.jpg)


###Download

Click [here](https://github.com/Seeed-Studio/Grove_LoRa_433MHz_and_915MHz_RF/) to download the library and example code and decompress it to any folders(e.g. Drive D or desktop).

Now you need simple [configurations for Arduino](https://seeeddoc.github.io/Sketchbook%E7%9A%84%E4%BD%BF%E7%94%A8) sketchbook.

Launch Arduino IDE and click File>Preferences and add absolute location for downloaded testing code at Sketchbook location.

![enter image description here](https://raw.githubusercontent.com/SeeedDocument/Grove_LoRa_Radio/master/img/perference.jpg)

After configurations, please restart Arduino, click File>Sketchbook and choose rf95_client.

![enter image description here](https://raw.githubusercontent.com/SeeedDocument/Grove_LoRa_Radio/master/img/down_client.jpg)

Click Tools>Board to choose "Arduino/Genuino Uno" and select respective serial port.

Then connect another Seeeduino Lotus to PC and download rf95_server code.

![enter image description here](https://raw.githubusercontent.com/SeeedDocument/Grove_LoRa_Radio/master/img/down_server.jpg)

**Note:**
If you're using Grove - LoRa Radio 868MHz module change the following code.

```c 

//rf95.setFrequency(434.0);
rf95.setFrequency(868.0);

```

###Review Results

After upload completed, you can open the serial monitor to see the result.

![enter image description here](https://raw.githubusercontent.com/SeeedDocument/Grove_LoRa_Radio/master/img/result.jpg)

###Date Rate

The below chart shows the relationships between the band rate signal band width spreding factor and sensitivity.

![enter image description here](https://raw.githubusercontent.com/SeeedDocument/Grove_LoRa_Radio/master/img/DateRate.png)


##  Resources
---
*   [Grove - LoRa Radio Library and Examples](https://github.com/Seeed-Studio/Grove_LoRa_433MHz_and_915MHz_RF/)
*   [Grove - LoRa Radio 433MHz v1.0 Schematics (Eagle files)](https://github.com/SeeedDocument/Grove_LoRa_Radio/blob/master/res/Grove%20-%20LoRa%20Radio%20433MHz%20v1.0sch.rar)
*   [Grove - LoRa Radio 433MHz v1.0 Schematics (PDF files)](https://github.com/SeeedDocument/Grove_LoRa_Radio/blob/master/res/Grove%20-%20LoRa%20Radio%20433MHz%20v1.0pdf.rar)
*   [Grove - LoRa Radio 433MHz v1.0 PCB (Eagle files)](https://github.com/SeeedDocument/Grove_LoRa_Radio/blob/master/res/Grove%20-%20LoRa%20Radio%20433MHz%20v1.0brd.rar)
*   [Grove - LoRa Radio 868MHz v1.0 Schematics (Eagle files)](https://github.com/SeeedDocument/Grove_LoRa_Radio/blob/master/res/Grove%20-%20LoRa%20Radio%20868MHz%20v1.0sch.rar)
*   [Grove - LoRa Radio 868MHz v1.0 Schematics (PDF files)](https://github.com/SeeedDocument/Grove_LoRa_Radio/blob/master/res/Grove%20-%20LoRa%20Radio%20868MHz%20v1.0pdf.rar)
*   [Grove - LoRa Radio 868MHz v1.0 PCB (Eagle files)](https://github.com/SeeedDocument/Grove_LoRa_Radio/blob/master/res/Grove%20-%20LoRa%20Radio%20868MHz%20v1.0brd.rar)
*   [LoRa Alliance](https://www.lora-alliance.org/)
*   [RFM95/96/97 Data Sheet](https://github.com/SeeedDocument/Grove_LoRa_Radio/blob/master/res/RFM95_96_97_98_DataSheet.pdf)


