STM32F446ZEJx UFBGA144 Target Board for ChipWhisperer

* [STM32F446ZEJx-SW308-UFO-V1.0](#stm32f446zejx-sw308-ufo-v10)
   * [Jumpers](#jumpers)
   * [Schematic](#schematic)
   * [Testing Blanks &amp; Real Paprium](#testing-blanks--real-paprium)

It is no secret that I am affiliated with the group of people focusing on [efforts to dump the Watermelon Games Paprium cart](https://github.com/ArcadeHustle/WatermelonPapriumDump). As part of this effort there became a need to 
attack an STM32F4 based chip. Sadly that chip wound up being in RDP2 mode, but the resulting tool that was created serves a greater purpose, so it is being shared here. 

At the time the work effort was put forth there was no UFBGA144 compatible Target Board for ChipWhisperer, so we worked with a trusted PCB design partner [@javier-rodas](https://github.com/javier-rodas) owner of SEVENIX INGENIERIA & the [@XTREME-MISTER](https://github.com/XTREME-MISTER) project to work out what was needed. This board will connect easily to a STLink V2, 
or a ChipWhisperer depending on where the jumpers are placed. The initial project this board was created for never moved past the STLink jumpers, we immediatly found that the chip was fully protected with all debug interfaced 
disabled. 

None the less, this is a perfect platform for learning Chip Whisperer based glitching logic, or attacking other UFBGA144 STM32 chips. 

# STM32F446ZEJx-SW308-UFO-V1.0

[Documentation](https://github.com/MAVProxyUser/STM32F446ZEJx-SW308-UFO-V1.0/tree/main/STM32F446ZEJx-SW308-UFO%20V1.0/DOCS) is fairly simple, set the jumpers accordingly, treat it as you would any other ChipWhisperer target board. 

## Jumpers
Enable jumpers as follows for CW usage. 
<img src="https://github.com/MAVProxyUser/STM32F446ZEJx-SW308-UFO-V1.0/blob/main/STM32F446ZEJx-SW308-UFO%20V1.0/DOCS/STM32F446ZEJx-SW308-UFO%20V1.0%20-%20JUMPER%20SETTINGS%20-%20ChipWhisperer%20mode.png">

## Schematic
You can see how the jumpers impact the schematic below.  
<img src="https://github.com/MAVProxyUser/STM32F446ZEJx-SW308-UFO-V1.0/blob/main/STM32F446ZEJx-SW308-UFO%20V1.0/DOCS/STM32F446ZEJx-SW308-UFO%20V1.0%20-%20JUMPER%20SETTINGS%20SCH%20-%20ChipWhisperer%20mode.png">

## Testing Blanks & Real Paprium 
We tested this design with a number of now rare blank STM32F446ZEJ6 chips, as well as an excavated STM32 from a Paprium game cart. 
<img src="https://github.com/MAVProxyUser/STM32F446ZEJx-SW308-UFO-V1.0/blob/main/STM32F446ZEJx-SW308-UFO%20V1.0/PHOTOS/IMG_7290.jpg">
<img src="https://github.com/MAVProxyUser/STM32F446ZEJx-SW308-UFO-V1.0/blob/main/STM32F446ZEJx-SW308-UFO%20V1.0/PHOTOS/IMG_7052.jpg">
<img src="https://github.com/MAVProxyUser/STM32F446ZEJx-SW308-UFO-V1.0/blob/main/IMG_1627.jpg">

If you need an amazing PCB designer, please let me know, and I can put you in touch with one. 


