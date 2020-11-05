---
id: 711
title: I2C Proximity Capacitive Touch Sensor
date: 2017-07-06T15:58:33+01:00
author: Martin Maly
layout: post
guid: https://alitronik.com/?p=711
permalink: /i2c-proximity-capacitive-touch-sensor/
pin_manual:
  - automatic
pin_text:
  - '[post_title]'
pin_board:
  - "326300004191374864"
pin_alt:
  - 'a:3:{i:0;s:0:"";i:1;s:0:"";i:2;s:0:"";}'
pin_index:
  - 'a:3:{i:0;s:0:"";i:1;s:98:"http://alitronik.com/wp-content/uploads/sites/18/2017/07/HTB1GSAuNFXXXXavXXXXq6xXFXXXb-300x300.jpg";i:2;s:177:"//ae01.alicdn.com/kf/HTB1qdY6NFXXXXXVaXXXq6xXFXXXF/1PCS-font-b-MPR121-b-font-Breakout-v12-Proximity-Capacitive-Touch-Sensor-Controller-Keyboard-Development-Board.jpg_220x220.jpg";}'
pin_try:
  - "1"
images_try:
  - 'a:1:{s:32:"4d9d8f99d3e70ba683a3c0a8b733416f";i:1;}'
xyz_twap:
  - "1"
firstpublish:
  - "1"
pins:
  - 'a:1:{i:0;s:98:"http://alitronik.com/wp-content/uploads/sites/18/2017/07/HTB1GSAuNFXXXXavXXXXq6xXFXXXb-300x300.jpg";}'
image: http://alitronik.com/wp-content/uploads/sites/18/2017/07/HTB1GSAuNFXXXXavXXXXq6xXFXXXb.jpg
categories:
  - Tip
tags:
  - Capacitive
  - I2C
  - Proximity
  - sensor
---
<a href="http://s.click.aliexpress.com/e/MbQFIUV" target="_parent"><img src="//ae01.alicdn.com/kf/HTB1qdY6NFXXXXXVaXXXq6xXFXXXF/1PCS-font-b-MPR121-b-font-Breakout-v12-Proximity-Capacitive-Touch-Sensor-Controller-Keyboard-Development-Board.jpg_220x220.jpg" /><span style="display: block;">MPR121 Breakout &#8211; Proximity Capacitive Touch Sensor</span></a>

The MPR121 is a capacitive touch sensor controller driven by an I2C interface. The chip can control up to twelve individual electrodes, as well as a simulated thirteenth electrode. The MPR121 also features eight LED driving pins. When these pins are not configured as electrodes, they may be used to drive LEDs.

There a four jumpers on the bottom of the board, all of which are set (closed) by default. An address jumper ties the ADD pin to ground, meaning the default I2C address of the chip will be 0x5A. If you need to change the address of the chip (by shorting ADD to a different pin), make sure you open the jumper first. Jumpers also connect SDA, SCL and the interrupt pin to 10k pull-up resistors. If you don&#8217;t require the pull-up resistors you can open the jumpers by cutting the trace connecting them.

There is no regulation on the board, so the voltage supplied should be between 2.5 and 3.6VDC. The VREG pin is connected through a 0.1uF capacitor to ground, which means, unless you modify the board, you can&#8217;t operate the MPR121 in low-supply voltage mode (1.71-2.75VDC).