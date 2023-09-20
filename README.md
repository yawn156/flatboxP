# FlatboxP: Flatbox rev5 fork 

This fork is now using WS2812B-V5 from JLC, which include capacitors inside the circuit and also operate on 3.3v logic from the RP2040.
Switch footprint supports Kaihl choc v1 and v2.

For the case I remixed Pettman's flatbox5 case to have a little window to show the active area of the screen.
I'll only upload the remixed top case here, go to their repo for details and the bottom plate:
https://github.com/pett-j/Flatbox-rev5-remix

If you want to use Choc V1 switches I recommend getting chocfox keycaps and using this button model:
https://www.thingiverse.com/thing:6196955

For V2 switches you can use SGF's buttons:
https://github.com/sgfdevices/Bridget/tree/main/Buttons

3D Printed Tact switch buttons:
https://www.printables.com/model/470120-flatbox-tactile-switch-button

This repository contains a 3D-printable model and PCB design files to make an arcade controller that looks like this:

![Assembled Flatbox](pictures/IMG_20230627_002206.jpg)


Note: Cheatbuttons are two extra buttons for easy thumb access, they have been added on the pcb but the case is still WIP.

MISC INFO:
As I'm not keeping up with this project enough to have an updated build version with every release I'll note here the changes on the webconfigurator that you need to do in order for this to work, you can use the Flatbox rev5 or Flatbox rev5 RGB uf2 from the GP2040-CE repository.

-Display Configuration:

Use Display = Enabled

SDA Pin = 0

SCL Pin = 1


-RGB LED Configuration:

Data Pin = 29

LED layout = Hit Box Layout

Leds per button = 1


-Pin Mapping

S1 = 15

S2 = 14

L3 = 27

R3 = 28

A1 = 26

A2 = -1



