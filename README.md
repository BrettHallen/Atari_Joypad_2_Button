# Atari Joypad (Two Button) aka Brett's Clueless Joypad
Simple two-button joypad using Atari pinout, compatible with both Atari 2600 & Atari 7800.<br>

Its purpose is for use as a small "troubleshooting" joypad when you are trying to repair a vintage computer and you have its bare motherboard on the bench.<br>

It has no higher aspirations than that.<br>

It is no larger than 100mm so its fabrication falls under the cheapest PCB cost (i.e. ten PCBs for US$5 at PCBWAY).<br>

There are three [right handed](/RightHanded) versions:<br>
- Rev. A matches the Atari 7800 layout: FIRE1 on left, FIRE2 on right
- Rev. B matches the NES layout: FIRE1/A on right, FIRE2/B on left
- Rev. C where FIRE1/FIRE2 position is selectable via solder bridge (default is Rev. A layout)

In testing I found my right thumb naturally resting on the FIRE2 (rightmost) button, hence the Rev. B design.  The Rev. C design has them selectable via solder bridge (thanks to suggestion by SheldonHarold/YouTube).<br>

![Clueless Joypad RH Rev. C](/RightHanded/RevC/Atari_Joypad_2_Button_RevC_3D.png)

Of course using it with something that expects Atari 2600 it doesn't matter as both FIRE buttons function the same.<br>

![Clueless Joypad RH Rev. C](/Clueless_Joypad_RH_RevA.png)

I have started a [left-handed](/LeftHanded) version ... any need?

![Clueless Joypad LH 3D](/LeftHanded/Atari_Joypad_2_Button_LH_3D.png)

## YouTube Videos
- [Part 1: Initial test (right handed, Rev. A)](https://youtu.be/WF11pfEDQUY)

## [Paddle](/Paddle)
Design for a troubleshooting paddle based on Atari design (thanks to suggestion by Ascania/YouTube).<br>

Suggested linear potentiometer values I've seen are 1MΩ for Atari and 470KΩ for Commodore.<br>

![Paddle 3D](/Paddle/Atari_Paddle_3D.png)

## [MSX Adaptor](/MSX_Adaptor)
I had an idea that an MSX adaptor board could be connected underneath the Atari 2600/7800 board to serve as an adaptor.<br>

The one joypad could then be connected natively to either Atari 2600/7800 (top PCB) or MSX (bottom PCB).<br>

![MSX adaptor 3D](/MSX_Adaptor/MSX_Adaptor_3D.png)

