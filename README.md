# HandheldRetropie
<img src="https://github.com/vives-project-xp/HandheldRetropie/assets/113902824/48aa0142-ecd1-4de3-a172-c52fbe51333d" width= "500"/>

<img src="https://github.com/vives-project-xp/HandheldRetropie/assets/113902824/c3d0e3a4-2eeb-40a0-a56e-c8859b5e5226" width="500" />

These pictures are early renders of how the project should look.


## Introduction
Welcome to the RetroPie Project! RetroPie is a versatile software solution that allows you to transform your Raspberry Pi into a full-fledged retro gaming console. It takes you back to the golden days of gaming where the concept was very simple but still fun. So you can play all the classic games you want, from Tetris to Mario. It does take you back to your childhood.

## Features

- The console is battery-powered.
- Easy to switch batterys.
- Designing PCB so that it takes up as little space as possible.
- Custom made casing.
- Uploading new games trough wifi.
- Battery indicator.
- Active cooling with PWM fans.
- Build in speaker.


## Software
One of the essential parts of the Retropie and maybe the beating heart of the project is the emulator. This is a software that makes it possible to put older games on a recent console. They actually form a bridge between the present and the past. This allows gamers to enjoy old games without playing on an old console. There will be a program running parallel with the games that calculates a PWM signal for cooling the system. This is calculated by the temperature inside the processor. the hotter it gets, the higher the PWM duty cycle gets, and thus cooling the system more.

## 3d prints
We've devided the 3d print in multiple parts so that these are easier to print. That's why there are 6 diffrent parts for the controller itself. The rest of the prints are the buttons. The controller can be connected trough connecting points that need to be glued together, this is only for the top side. The bottom side will be mounted with screws to the topside.
All of our prints were designed with fusion 360, the instructions to design certain models is in the 'handleiding fusion 360' folder.

## PCB design
Our pcb is also designed with fusion 360. The instructions to design 1 yourself are also in the 'xxxxxxxxxxxxxxxxxxxxx' folder. Our pcb holds all the buttons, the amplifier and the battery indicator. The PCB also has some holed that are provided to mount the pcb to the 3d case.

# Hardware
Since the batterys operate at a voltage between 7,4V to 8,2V we need an inverter so that we can create a 5V circuit since most components only work with 5V. The sound is produced by our own aplifier system and a small 8 Ohm 1 Watt speaker. We have PWM fans that are spinning accordanly to the CPU temperature. To monitor our battery life we are using an led-indicator, which simpely uses resistors,leds and diodes

## Setup
-emulator install
-mounting everything at place x


## Tests
since we have a gathering of small projects fused in to 1 we had to test multiple components and circuits.
-converter
-amplifier
-screen
-emulator
-batterys
-3d prints





