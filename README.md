# PicoStation PCB remixed with some improvements!

Heres a remix of the original PCB with some admendments and improvements.
* Added USBC port for easy updates!
* Changed MicroSD slot for a surface mounted design with spring mechanism
* Adjusted spacing for the mounts as they were not correct originally
* Removed debug port - dont think its needed
* Created a 3D Printed cover as well as mounts

As for ordering the PCB's, stock 1.6mm settings are fine. You can also find gerbers for QSB's here: https://github.com/WakaMax/PS1_Picostation_QSB

![PXL_20250805_163745202](https://github.com/user-attachments/assets/2e4be4e6-0be2-450e-bf76-546648c15591)
![PXL_20250805_183013231](https://github.com/user-attachments/assets/8ee25980-4481-4f70-9fe6-0606b7957a68)


| PART | LINK |
|---|---|
| Pico | https://www.aliexpress.com/item/1005007393927221.html  |
| USBC Connector 10mm | https://www.aliexpress.com/item/1005007522269561.html |
| 0805 10uF | https://www.aliexpress.com/item/32964553793.html |
| 0805 10k resisors | https://www.aliexpress.com/item/1005005600798857.html |
| 0805 4.7k resisors | https://www.aliexpress.com/item/1005005600798857.html |
| 0805 LED | https://www.aliexpress.com/item/1005007252088951.html Whatever colour you prefer! |
| SOD-123 1N5819 | https://www.aliexpress.com/item/1005005707644429.html |
| MicroSD Slot | https://www.aliexpress.com/item/1005001331379046.html |
| 20pin 1mm pitch FFC Socket | https://www.aliexpress.com/item/10000348360254.html |
| 20pin 1mm pitch FFC Cable | https://www.aliexpress.com/item/1005007561337665.html Reversed direction, 200mm long |
| TO-252 7505 | https://www.aliexpress.com/item/1005005872653015.html |


* Soldering the Pico requires extra attention as the USBC port uses test pads on the bottom of the Pico which are fairly close to each other, these need to be accurately lined up and board completely flat else may cause bridges, would recommend soldering two pads on the Pico at opposite ends to anchor when you're happy with the placement then flood filling the underside holes ensuring theres no bridges between them before solding the rest of the Pico pins. If USBC port doesnt work, apply additional heat/solder to the holes as likely didnt attach properly

