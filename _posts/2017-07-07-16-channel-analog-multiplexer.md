---
id: 717
title: 16-Channel Analog Multiplexer
date: 2017-07-07T15:49:44+01:00
author: Martin Maly
layout: post
guid: https://alitronik.com/?p=717
permalink: /16-channel-analog-multiplexer/
pin_manual:
  - automatic
pin_text:
  - '[post_title]'
pin_board:
  - "326300004191374864"
pin_alt:
  - 'a:2:{i:0;s:0:"";i:1;s:0:"";}'
pin_index:
  - 'a:2:{i:0;s:0:"";i:1;s:173:"//ae01.alicdn.com/kf/HTB1bE_IQpXXXXb6XpXXq6xXFXXX9/Smart-Electronics-CD74HC4067-16-Channel-Analog-Digital-Multiplexer-font-b-Breakout-b-font-Board-Module-for.jpg_220x220.jpg";}'
pin_try:
  - "1"
images_try:
  - 'a:1:{s:32:"cfb64e89327f68389574e792eeafad1a";i:1;}'
xyz_twap:
  - "1"
firstpublish:
  - "1"
pins:
  - 'a:1:{i:0;s:173:"//ae01.alicdn.com/kf/HTB1bE_IQpXXXXb6XpXXq6xXFXXX9/Smart-Electronics-CD74HC4067-16-Channel-Analog-Digital-Multiplexer-font-b-Breakout-b-font-Board-Module-for.jpg_220x220.jpg";}'
image: http://alitronik.com/wp-content/uploads/sites/18/2017/07/HTB1ek5KLXXXXXXmaXXXq6xXFXXXu.jpg
categories:
  - Tip
tags:
  - Analog
  - arduino
  - Breakout
  - module
  - Multiplexer
---
<a href="http://s.click.aliexpress.com/e/AemAYjU" target="_parent"><img src="//ae01.alicdn.com/kf/HTB1bE_IQpXXXXb6XpXXq6xXFXXX9/Smart-Electronics-CD74HC4067-16-Channel-Analog-Digital-Multiplexer-font-b-Breakout-b-font-Board-Module-for.jpg_220x220.jpg" /><span style="display: block;">CD74HC4067 16-Channel Analog Digital Multiplexer Breakout Board Module</span></a>

This chip is like a rotary switch &#8211; it internally routes the common pin (COM in the schematic, SIG on the board)to one of 16 channel pins (CHANxx). It works with both digital and analog signals (the voltage can&#8217;t be higher than VCC), and the connections function in either direction. To control it, connect 4 digital outputs to the chip&#8217;s address select pins (S0-S3), and send it the binary address of the channel you want (see the datasheet for details). This allows you to connect up to 16 sensors to your system using only 5 pins! Since the mux/demux also works with digital signals, you can use it to pipe TTL-level serial data to or from multiple devices. For example, you could use it to connect the TX pins of 16 devices to one RX pin on your microcontroller. You can then select any one of those 16 devices to listen to. If you want two-way communications, you can add a second board to route your microcontroller&#8217;s TX line to 16 device&#8217;s RX lines. By using multiple boards, you can create similar arrangements for I2C, SPI, etc. The internal switches are bidirectional, support voltages between ground and VCC, have low “on” resistance and low “off” leakage, and to prevent crosstalk, perform “break-before-make” switching. The board also breaks out the chip&#8217;s “enable” pin, which when driven high, will completely disconnect the common pin (all switches “off”).