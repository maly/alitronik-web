---
id: 844
title: Miniature laser harp
date: 2017-08-21T09:15:38+01:00
author: Martin Maly
layout: post
guid: https://alitronik.com/?p=844
permalink: /miniature-laser-harp/
pin_manual:
  - automatic
pin_text:
  - '[post_title]'
pin_board:
  - "326300004191374864"
pin_alt:
  - 'a:3:{i:0;s:0:"";i:1;s:0:"";i:2;s:0:"";}'
pin_index:
  - 'a:3:{i:0;s:0:"";i:1;s:131:"//ae01.alicdn.com/kf/HTB12cWrSFXXXXaTXVXXq6xXFXXX3/-font-b-CNIKESIN-b-font-DIY-Kits-51-SCM-font-b-Laser-b-font-font.jpg_220x220.jpg";i:2;s:90:"http://alitronik.com/wp-content/uploads/sites/18/2017/08/HTB10PyUSFXXXXXpXpXXq6xXFXXXz.jpg";}'
pin_try:
  - "1"
images_try:
  - 'a:1:{s:32:"265a945b0dd54c968ca934a6cdd2480c";i:1;}'
xyz_twap:
  - "1"
firstpublish:
  - "1"
pins:
  - 'a:1:{i:0;s:131:"//ae01.alicdn.com/kf/HTB12cWrSFXXXXaTXVXXq6xXFXXX3/-font-b-CNIKESIN-b-font-DIY-Kits-51-SCM-font-b-Laser-b-font-font.jpg_220x220.jpg";}'
image: http://alitronik.com/wp-content/uploads/sites/18/2017/08/HTB10PyUSFXXXXXpXpXXq6xXFXXXz.jpg
categories:
  - Tip
tags:
  - "8051"
  - "8052"
  - audio
  - harp
  - Laser
  - Sound
---
<a href="http://s.click.aliexpress.com/e/Qbqzvvn" target="_parent"><img src="//ae01.alicdn.com/kf/HTB12cWrSFXXXXaTXVXXq6xXFXXX3/-font-b-CNIKESIN-b-font-DIY-Kits-51-SCM-font-b-Laser-b-font-font.jpg_220x220.jpg" /></a><span style="display: block;"><a href="http://s.click.aliexpress.com/e/Qbqzvvn" target="_parent">DIY Kit &#8211; Laser harp</a> with 8051</span>

&nbsp;

A laser harp is a harp without strings. Instead of a bright beam, the user only needs to toggle the beam, as if  
he had struck a string and still played a melody. The photosensitive resistor and the monolithic integrated  
circuit STC89C52 two parts constitution. The laser beam emission tube is blocked, and the corresponding  
photosensitive resistance induction resistance changes, changes of system of eight photosensitive resistor  
which produces high and low potential, and the MCU reads the change of photosensitive resistance of high  
and low potential, complete the operation command input, SCM according to the instruction information to  
control the data transmission through the serial port, both docking the speaker&#8217;s p0^2 port and then light water  
P1 port assignment, to produce the corresponding reaction.

When a laser is irradiated, the microcontroller reads the voltage of the photosensitive resistor, which is low at  
this time. When no laser radiation, the microcontroller reads the voltage of the photosensitive resistor, then it  
is high level. Thus, when the light of the laser is shielded, the effect of the switch can be generated in the  
circuit.

The frequency of the human ear can be heard from 20Hz to 20kHz, and the harp note frequency should be in  
this range. Just different notes have their own fixed frequencies. Through the 52 microcontroller comes with  
16 bit timer, you can produce the above audio. For example, the harp&#8217;s standard tone, La, is 440Hz. By  
calculation, the half period is 1136 Mu s. Thus, the square wave of the 440Hz can be generated as long as the  
jump pin level is changed in the half cycle. And then through the electroacoustic conversion element (horn),  
you can produce standard tone La, and other notes are the same way.

Our laser harp features

  * there are 7 strings, when the string is cut, the buzzer corresponds to the sound level
  * cutting strings, corresponding to the string LED lit, a total of 7 LED
  * play two pieces of music stored by button
  * medium high bass switch