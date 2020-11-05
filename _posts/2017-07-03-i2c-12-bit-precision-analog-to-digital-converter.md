---
id: 688
title: I2C 12 bit precision analog-to-digital converter
date: 2017-07-03T15:48:23+01:00
author: Martin Maly
layout: post
guid: https://alitronik.com/?p=688
permalink: /i2c-12-bit-precision-analog-to-digital-converter/
pin_manual:
  - automatic
pin_text:
  - '[post_title]'
pin_board:
  - "326300004191374864"
pin_alt:
  - 'a:3:{i:0;s:0:"";i:1;s:0:"";i:2;s:0:"";}'
pin_index:
  - 'a:3:{i:0;s:0:"";i:1;s:98:"http://alitronik.com/wp-content/uploads/sites/18/2017/06/HTB1ImirNFXXXXaPXXXXq6xXFXXXK-300x300.jpg";i:2;s:157:"//ae01.alicdn.com/kf/HTB1mzqsPXXXXXcpapXXq6xXFXXXD/-font-b-ADS1015-b-font-12-bit-precision-analog-to-digital-converter-ADC-module-development.jpg_220x220.jpg";}'
pin_try:
  - "1"
images_try:
  - 'a:1:{s:32:"d303e1907bd14a27b46b0fc4435f1c86";i:1;}'
xyz_twap:
  - "1"
firstpublish:
  - "1"
pins:
  - 'a:1:{i:0;s:98:"http://alitronik.com/wp-content/uploads/sites/18/2017/06/HTB1ImirNFXXXXaPXXXXq6xXFXXXK-300x300.jpg";}'
image: http://alitronik.com/wp-content/uploads/sites/18/2017/06/HTB1ImirNFXXXXaPXXXXq6xXFXXXK.jpg
categories:
  - Tip
tags:
  - ADC
  - Analog
  - Converter
  - Digital
  - I2C
  - module
---
<a href="http://s.click.aliexpress.com/e/urfEieI" target="_parent"><img src="//ae01.alicdn.com/kf/HTB1mzqsPXXXXXcpapXXq6xXFXXXD/-font-b-ADS1015-b-font-12-bit-precision-analog-to-digital-converter-ADC-module-development.jpg_220x220.jpg" /><span style="display: block;">ADS1015 12 bit precision analog-to-digital converter ADC module development board</span></a>

ADS1015 provides 12-bit precision at 3300 samples/second over I2C. The chip can be configured as 4 single-ended input channels, or two differential channels. As a nice bonus, it even includes a programmable gain amplifier, up to x16, to help boost up smaller single/differential signals to the full range. We like this ADC because it can run from 2V to 5V power/logic, can measure a large range of signals and its super easy to use. It is a great general purpose 12 bit converter.

The chip&#8217;s fairly small so it comes on a breakout board with ferrites to keep the AVDD and AGND quiet. Interfacing is done via I2C. The address can be changed to one of four options (see the datasheet table 5) so you can have up to 4 ADS1015&#8217;s connected on a single 2-wire I2C bus for 16 single ended inputs.

  * WIDE SUPPLY RANGE: 2.0V to 5.5V
  * LOW CURRENT CONSUMPTION: Continuous Mode: Only 150μA Single-Shot Mode: Auto Shut-Down
  * PROGRAMMABLE DATA RATE: 8SPS to 860SPS
  * INTERNAL LOW-DRIFT VOLTAGE REFERENCE
  * INTERNAL OSCILLATOR
  * INTERNAL PGA
  * I2C INTERFACE: Pin-Selectable Addresses
  * FOUR SINGLE-ENDED OR TWO DIFFERENTIAL INPUTS
  * PROGRAMMABLE COMPARATOR
  * This board/chip uses I2C 7-bit addresses between 0x48-0x4B, selectable with jumpers.