# macrokeyboard
Custom macrokeyboard using raspberry pi pico
### Objective:

Here we are trying to make a custom macro keyboard with  a knob and a customizable OLED display which can display variety of things. Here we have designed and fabricated a PCB for connecting the components in a compact package. However, you can use a solderable breadboard for a cheaper and easier alternative.

### Designing Hardware:

Hardware Selection in really important and it can highly personalized as per the user requirement. I will do my best to provide you with as many options as possible and guides on how to obtain them.

### Parts Used:

1. Raspberry pi pico 
2. rotary encoder
3. oled display
4. mechanical switches 
5. keycaps
6. LED lights(optional)
7. Access to a pcb manufacturer
8. Soldering accessories 

### Circuit Diagram:

here is my approach in circuit diagram,however feel free to change it as per your need. Lot of guides and websites may use the column and row approach for wiring the keys with micro controller. However since we only have 9 keys and fewer accessories than the n.o of pins out choice of micro controller seems to offer. We can directly wire our keys to a individual pins.
![image](https://github.com/user-attachments/assets/2650cf80-ca17-48cc-a1a2-7e1cf4bbf7a8)



here the LEDs are completely optional and you can skip the rotary encoder and display connection if you want.

### Obtaining Hardware

**Pi pico** - pi pico can be obtained through the authorized vendors in your region, you can find them through this [link](https://www.raspberrypi.com/products/raspberry-pi-pico/) .

**rotary encoder and oled** - I have bought mine from [Robu](http://www.robu.in) However you can buy it from any vendor from your region.

**key switches and key caps** - I have bought mine from [Meckeys](https://www.meckeys.com/) but you can usually get yours from websites dedicated to mechanical keyboards or even amazon will do fine.

PCB Fabrication - Since we had access to PCB fabrication facility in our university it has hassle free for us . But you can use the service of PCB manufacturers like PCB power or PCB way or use a solder able breadboard to create your own tracks.

### PCB

Down here is the routing i have followed but you can change it as per your requirements:

![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/11efc2b9-f43e-43fe-9b05-3878c054a73d/fb3253c9-dbd7-43dc-bb0f-0f2d1edfebf2/Untitled.png)

links to footprint:

[key switches](https://github.com/kiswitch/kiswitch) 

[raspi pico](https://www.snapeda.com/parts/RASPBERRY%20PI%20PICO/Raspberry%20Pi/view-part/)

### Files

This zip file contains all the kicad files along with gerber files in gerber.zip

[macro keyboard.zip](https://prod-files-secure.s3.us-west-2.amazonaws.com/11efc2b9-f43e-43fe-9b05-3878c054a73d/47a508b6-a13e-4840-bca5-544fbc6fd0b9/macro_keyboard.zip)

### Assembly

switches can be soldered directly to the board.

you may solder female pin header for pico, oled and rotary encoder for hot swapabality, i highly suggest female pin header for pico alone as the hardware can be repurposed easily when needed.
