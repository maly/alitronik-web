---
id: 926
title: 2 channel PWM frequency generator
date: 2017-10-09T10:21:05+01:00
author: Martin Maly
layout: post
guid: https://alitronik.com/?p=926
permalink: /2-channel-pwm-frequency-generator/
pin_manual:
  - automatic
pin_text:
  - '[post_title]'
pin_board:
  - "326300004191374864"
pin_alt:
  - 'a:3:{i:0;s:0:"";i:1;s:0:"";i:2;s:0:"";}'
pin_index:
  - 'a:3:{i:0;s:0:"";i:1;s:133:"//ae01.alicdn.com/kf/HTB1pIF2NVXXXXacXpXXq6xXFXXXe/2-Channel-font-b-PWM-b-font-font-b-Generator-b-font-font-b-Pulse-b.jpg_220x220.jpg";i:2;s:98:"http://alitronik.com/wp-content/uploads/sites/18/2017/10/HTB1g9FBNVXXXXaQaXXXq6xXFXXXx-300x300.jpg";}'
pin_try:
  - "1"
images_try:
  - 'a:1:{s:32:"7efb9a90611d5e3d965c5cad543b7d3e";i:1;}'
xyz_twap:
  - "1"
firstpublish:
  - "1"
pins:
  - 'a:1:{i:0;s:133:"//ae01.alicdn.com/kf/HTB1pIF2NVXXXXacXpXXq6xXFXXXe/2-Channel-font-b-PWM-b-font-font-b-Generator-b-font-font-b-Pulse-b.jpg_220x220.jpg";}'
image: http://alitronik.com/wp-content/uploads/sites/18/2017/10/HTB1g9FBNVXXXXaQaXXXq6xXFXXXx.jpg
categories:
  - Tip
tags:
  - Frequency
  - Generator
  - PWM
  - Tool
---
<a href="http://s.click.aliexpress.com/e/vB2bIuJ" target="_parent"><img src="//ae01.alicdn.com/kf/HTB1pIF2NVXXXXacXpXXq6xXFXXXe/2-Channel-font-b-PWM-b-font-font-b-Generator-b-font-font-b-Pulse-b.jpg_220x220.jpg" /><span style="display: block;">2 Channel PWM Generator Pulse Frequency Duty Cycle Adjustable Square Wave Rectangle Signal Generator For Stepper Motor Driver</span></a>

**Product Introduction:**

  1. Operating Voltage:5-30V,support micro USB 5.0V power supply
  2. Frequency Range:1Hz~150KHz
  3. Frequency Precision:2%
  4. Signal Load Capaciity:output current is within 8&#8211;30mA
  5. Output Range:default 5V V-pp (can be changed by external power)
  6. Ambient Temperature:-30 Celsius ~70 Celsius

Application Fields:

  * As square wave generator to generate square wave for experiment development
  * Used to drive steeping motor driver&#8217;s square wave
  * Generate adjustable pulse for MCU using
  * Generate adjustable pulse for controlling relative circuit (PWM adjust light speed etc)

Serial Port Control

  * Communication Standard:9600 bps
  * Data Bit:8
  * Stop Bit:1
  * Parity Bit: none
  * Flow Control: none

Setting PWM Frequency

  * &#8220;S1FXXXT&#8221;:set PWM1 frequency as XXX HZ (001~999)
  * &#8220;S1FXX.XT&#8221;:set PWM1 frequency as XX.X KHZ (00.1~99.9)
  * &#8220;S1F:X.X.X.T&#8221;:set PWM1 frequency as XXX KHZ (0.0.1.~1.5.0.)
  * &#8220;S1&#8221;:PWM1
  * &#8220;S2&#8221;:PWM2
  * &#8220;F&#8221;:frequency
  * &#8220;D&#8221;:duty cycle
  * &#8220;T&#8221;:stop sign bit

Setting PWM Duty Cycle

  * &#8220;S1DXXXT&#8221;:set PWM1 duty cycle as XXX;(001~100)
  * &#8220;S2DXXXT&#8221;:set PWM2 duty cycle as XXX;(001~100)

Setting successfully back: DOWN

Setting unsuccessfully back: FALL

Parameter Setting

  * Module has 3-channel key: Set, Up, Down
  * By short press SET key, you can shift display 4 parameter values 
      * FR1:PWM1 frequency
      * dU1:PWM1 duty cycle
      * FR2:PWM2 frequency
      * dU2:PWM2 duty cycle
  * before shifting, there will be corresponding parameter name flashing
  * Directly press UP,DOWN key to modify current parameter value
  * 2-channel PWM are set 3 kinds frequency value, in frequency display interface, by long press SET to shift, 3 kinds frequency&#8217;s duty cycle are the same (XXX:1Hz~999Hz; XX.X:0.1Khz~99.9Khz;X.X.X.:1Khz~150Khz)