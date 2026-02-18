This is my journal of the design and building process of Reactor, a high score reaction game.

## 6/29/2025 - First Devlog
My first devlog, yippie! My first hardware project as well. Currently I'm following the Pathfinder YSWS created by the amazing Meghana. A foundation of an idea is emerging as I learn and navigate KiCAD.
Reactor will be a high score reaction game were the player have to click the corresponding button indicated by the LED within a set amount of time (configurable by the game difficulty) else the reactor explodes (i.e. you lose). Think of it as pocketable Bop It that you can pull out when you're bored.

![KiCAD](https://github.com/Rubey4112/reactor/blob/4af18052efb66bb33f1bc0a6f45e0560a277a0ec/images/journal/kicad_6_29_25.jpg)

## 6/30/2025 - Game Loop Prototype
I'm almost finished with prototyping the game loop for Reactor (info on how the game work in the first devlog). I might add more game mode to the game as well.

![First Prototype](https://github.com/Rubey4112/reactor/blob/4af18052efb66bb33f1bc0a6f45e0560a277a0ec/images/journal/arduino_6_30_25.jpg)

## 7/1/2025 - Prototype Code Finished
Another late night devlog. Not much interesting update other than that I got my Arduino code to compiled. Finished the prototyping phase of the game. Now I just got to get the logic to work.

![Finished Prototype](https://github.com/Rubey4112/reactor/blob/4af18052efb66bb33f1bc0a6f45e0560a277a0ec/images/journal/arduino_7_1_25.jpg)

## 7/2/2025 - Wokwi Sim
Return flight got cancelled, so fun! So, to pass the time I created a demo of the game in Wokwi. Additionally, I'm using Wokwi to simulate and debug my code because right now it is not working.

![Created Hardware Sim](https://github.com/Rubey4112/reactor/blob/4af18052efb66bb33f1bc0a6f45e0560a277a0ec/images/journal/wokwi_7_2_25.jpg)

## 7/4/2025 - PCB Design Finished
I finished designing the PCB and had it quoted on JLC PCB and it is under $10! ($5.50 + $3.12 shipping to be exact). I just submitted it to Pathfinder YSWS and is now waiting for it to be verified.

![PCB Finished](https://github.com/Rubey4112/reactor/blob/4af18052efb66bb33f1bc0a6f45e0560a277a0ec/images/journal/pcb_7_4_25.jpg)

## 7/5/2025 - Debugging Sim
I try to use PlatformIO and Wokwi for VSCode to use the debugging feature. I spent more time trying to get the debugger to work than actually debugging my code. The debugger still doesn't work as intended and I give up.

![VSCode Debugging](https://github.com/Rubey4112/reactor/blob/4af18052efb66bb33f1bc0a6f45e0560a277a0ec/images/journal/vscode_7_5_25.jpg)

## 7/5/2025 - Shipping Project
I fixed my code and uploaded it to Wokwi and tested it to ensure it worked. I'm ready to ship this project!

![Final Wokwi Sim](https://github.com/Rubey4112/reactor/blob/4af18052efb66bb33f1bc0a6f45e0560a277a0ec/images/journal/wokwi_7_5_25.jpg)

## 8/31/2025 - Assembly
The parts arrived and I finally had the time to assemble it. Also fixed the pins definitions in the code so that the correct buttons corresponded to the right LEDs.

[Link to Wokwi Sim](https://wokwi.com/projects/435296600249931777)

[![Reactor Demo](https://img.youtube.com/vi/G-2TqjjQF9Q/0.jpg)](https://www.youtube.com/watch?v=G-2TqjjQF9Q)
