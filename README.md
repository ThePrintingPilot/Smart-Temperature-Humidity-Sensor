# **DIY Temperature/Humidity Sensor** <img src="https://raw.githubusercontent.com/ThePrintingPilot/Smart-Temperature-Humidity-Sensor/refs/heads/main/Pictures/3.jpg" width="90" height="70" /> ✨


## **Welcome!**

For a while, I've been using Zigbee and Bluetooth temperature and humidity sensors around my house.
After many issues with Zigbee disconnecting and batteries running out 3 times a week. And since I've been constantly repairing Home Assistant sensors, I've decided to design the best smart home temperature and Humidity Sensor for myself.

I've designed a plug-in, temperature/humidity sensor that works over Wi-Fi, and it's all open source!

**If you like to support us, we offer a fully assembled version of the sensor at our store. [link](https://theprintingpilot.com/products/smart-home-temperature-humidity-sensor)**



## **Why Choose My Design?**

Fully plug-in design - no batteries needed.
Fully Open Source - All code is available using ESPHOME.
Automatically discovered and connected to Home Assistant.
Only 5 components for the PCB. 

## **What do I need?**

- PCB 
- 10 KΩ resistor x2 - [Link](https://www.lcsc.com/product-detail/C17902.html)
- 100nF capacitor - [Link](https://www.lcsc.com/product-detail/C1590.html)
- ESP 32 - [Affiliate Link](https://s.click.aliexpress.com/e/_c3afmmmj)
- SHT40 - [Link](https://www.digikey.com/en/products/detail/sensirion-ag/SHT40-AD1B-R2/13532084)
- 3D Printed Enclosure - [Link](placeholder)

## **3D Printed Enclosure:**
Open the 3mf file as a project, that way you can see the mid print pause to add the magnets

<img src="https://raw.githubusercontent.com/ThePrintingPilot/Smart-Temperature-Humidity-Sensor/refs/heads/main/Pictures/2.gif" width="300" height="200" />

---
**The project is open-source, but please consider supporting us and helping us with feature developments by purchasing the PCBs from our [Offical Shop](https://theprintingpilot.com/products/smart-home-temperature-humidity-sensor) . Thank you!**

---
## **Check out the full step by step instruction video on our youtube channel:**

[![Video Title](https://img.youtube.com/vi/L6Fg58wCgnI/0.jpg)](https://www.youtube.com/watch?v=L6Fg58wCgnI)




## **Join Our Discord Server**
---
To discuss everything about our custom made PCBs or everything 3D printed!

[<img src="https://discordapp.com/api/guilds/763458034440863814/widget.png?style=banner2" alt="Discord Banner 2"/>](https://discord.gg/cdHPTxnrM8)


---
## **Follow us on Social Media**

[<img src="https://raw.githubusercontent.com/ThePrintingPilot/Smart-Air-Refreshener/refs/heads/main/Pictures/Tiktok.png" width="150" height="150" />](https://www.tiktok.com/@the_printing_pilot)
[<img src="https://upload.wikimedia.org/wikipedia/commons/f/fd/YouTube_full-color_icon_%282024%29.svg" width="150" height="150" />](https://www.youtube.com/@ThePrintingPilot)


## **Instructions:** 
**- Assemble the PCB:**
 Solder the capacitor, 2 resistors, the temperature sensor, and the esp as shown in the images.

<img src="https://raw.githubusercontent.com/ThePrintingPilot/Smart-Temperature-Humidity-Sensor/refs/heads/main/Pictures/4.jpg" width="300" height="200" />
<img src="https://raw.githubusercontent.com/ThePrintingPilot/Smart-Temperature-Humidity-Sensor/refs/heads/main/Pictures/3.jpg" width="300" height="200" />

**- Software:**
Download the compiled bin file from GitHub, and go to the ESPhome [installer.](https://web.esphome.io/)
Connect the PCB to your computer, press the connect button, and choose your esp in the pop-up window.

<img src="https://raw.githubusercontent.com/ThePrintingPilot/Smart-Temperature-Humidity-Sensor/refs/heads/main/Pictures/5.png" width="300" height="350" />

Then press install and add the bin file. and wait for the installation to complete.

<img src="https://raw.githubusercontent.com/ThePrintingPilot/Smart-Temperature-Humidity-Sensor/refs/heads/main/Pictures/6.png" width="300" height="350" />

If the ESP keeps disconnecting, press the reset button on the ESP and connect it to the computer simultaneously. That will ensure the esp is in pairing mode.





**- Next** go to your phone, look for the Wi-Fi hotspot the ESP is transmitting, and connect to it.

<img src="https://raw.githubusercontent.com/ThePrintingPilot/Smart-Temperature-Humidity-Sensor/refs/heads/main/Pictures/2.jpg" width="300" height="350" />



 Enter the Wi-Fi credentials on the page that opens. If nothing opens, go to your browser and type 192.168.4.1

<img src="https://raw.githubusercontent.com/ThePrintingPilot/Smart-Temperature-Humidity-Sensor/refs/heads/main/Pictures/1.jpg" width="300" height="450" />


**- Next,** you need to adopt the sensor into Home Assistant. Home Assistant should discover it automagically, and the sensor should appear in the integration page.(Check the video to see the software and the process).


**- Last,** put the PCB inside the enclosure, and enjoy!

<img src="https://raw.githubusercontent.com/ThePrintingPilot/Smart-Temperature-Humidity-Sensor/refs/heads/main/Pictures/1.gif" width="500" height="300" />


**AND that's it, you're done making the DIY Smart Home Temperature/Humidity Sensor For Home Assistant.**

<img src="https://raw.githubusercontent.com/ThePrintingPilot/Smart-Temperature-Humidity-Sensor/refs/heads/main/Pictures/Revision%201-5.png" width="500" height="350" />