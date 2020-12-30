# Arduino Burn Shield

## Overview

This is the Arduino shield used for burning the Arduino boot-loader and program the Arduino programs onto the microcontroller

### PCB - Bottom

![Bottom](https://644db4de3505c40a0444-327723bce298e3ff5813fb42baeefbaa.ssl.cf1.rackcdn.com/2be838f2449c643c4b11c26bc7b97eda.png)

### PCB - Top

![Top](https://644db4de3505c40a0444-327723bce298e3ff5813fb42baeefbaa.ssl.cf1.rackcdn.com/e1fd5f965604395a09e0be9307e647f2.png)

## Instructions to use the Shield

### Step 0 - Burn the bootloader

TBA

### Step 1 - Programming the Arduino as a Programmer

1. Select the `File->Examples->11. ArduioISP->ArdunioISP` sketch.
1. Verify
1. Upload

### Step 2 - Burning the program into ATTiny

1. Select `Tools->Board->ATtiny Microcontroller->ATtiny25/45/85` as the board. (**Note:** this option will only appear when we add the board using the board manager)
1. Select `Tools->Processor->ATtiny??` 
1. Select `Tools->Clock->??`
1. Select `Tools->Programmer->Arduino as ISP`

## References

1. AVR <-> Arduino Pin Map - [link](https://learn.sparkfun.com/tutorials/tiny-avr-programmer-hookup-guide/attiny85-use-hints)

2. ATTiny Arduino Tutorial (including the original schematics) - [link](https://makersportal.com/blog/2018/5/19/attiny85-arduino-board-how-to-flash-the-arduino-bootloader-and-run-a-simple-sketch)


## License

<a rel="license" href="http://creativecommons.org/licenses/by/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by/4.0/88x31.png" /></a><br /><span xmlns:dct="http://purl.org/dc/terms/" property="dct:title">Arduino Burn Shield</span> by <a xmlns:cc="http://creativecommons.org/ns#" href="https://github.com/rkrishnasanka/arduino-burn-shield" property="cc:attributionName" rel="cc:attributionURL">Radhakrishna Sanka</a> is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by/4.0/">Creative Commons Attribution 4.0 International License</a>.<br />Based on a work at <a xmlns:dct="http://purl.org/dc/terms/" href="https://makersportal.com/blog/2018/5/19/attiny85-arduino-board-how-to-flash-the-arduino-bootloader-and-run-a-simple-sketch" rel="dct:source">https://makersportal.com/blog/2018/5/19/attiny85-arduino-board-how-to-flash-the-arduino-bootloader-and-run-a-simple-sketch</a>.<br />Permissions beyond the scope of this license may be available at <a xmlns:cc="http://creativecommons.org/ns#" href="https://github.com/rkrishnasanka/arduino-burn-shield/LICENSE.md" rel="cc:morePermissions">https://github.com/rkrishnasanka/arduino-burn-shield/LICENSE.md</a>.

