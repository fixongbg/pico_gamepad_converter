# Pico Gamepad Converter

Credit goes out to the original creator: https://github.com/Loc15/PicoGamepadConverter

---

This is my simplified guide of that project: 

### Installation

1. [Download](https://github.com/Loc15/PicoGamepadConverter/releases) the build program.
   
2. Hold down the **BOOTSEL** button on the pico, connect the USB-cable to the PC, the pico should now show up as a USB-drive. Copy the downloaded **.uf2** file to the pico. The pico should now restart and be programmed.  

4. Make the connections. You can just hold a wire from **VBUS (+5V)** to **pin GP18** during boot of the pico. LED on the pico will start to flash, now you're in config mode. 

![schematic](./docs/pico_pinout.png)
![conections1](./docs/bread_board1.jpg)
![conections2](./docs/bread_board2.jpg)

4. Go to configuration mode pressing the button on 18 GPIO on start. On WEB mode the LED start to blink.

5. Choose the modes on the web server. Access http://192.168.3.1 in a web browser to begin configuration.

![web_mode](./docs/web_configurator.png)

6. Connect your gamepad, when it connected successfully the LED on the board gonna turn on.

7. Enjoy!


