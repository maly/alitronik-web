---
id: 1002
title: Clock Generator 8KHz to 160MHz
date: 2018-01-21T13:52:38+01:00
author: Martin Maly
layout: post
guid: https://alitronik.com/?p=1002
permalink: /clock-generator-8khz-to-160mhz/
xyz_twap:
  - "1"
firstpublish:
  - "1"
pins:
  - 'a:1:{i:0;s:159:"//ae01.alicdn.com/kf/HTB1fWKijtfJ8KJjy0Feq6xKEXXax/-font-b-CJMCU-5351-b-font-Si5351A-Si5351-I2C-25MHZ-Controller-Clock-Generator-Breakout-Board.jpg_220x220.jpg";}'
pin_manual:
  - automatic
image: http://alitronik.com/wp-content/uploads/sites/18/2018/01/HTB1gcPFgC_I8KJjy0Foq6yFnVXaQ.jpg
categories:
  - Tip
tags:
  - Clock
  - Generator
  - I2C
---
<a href="http://s.click.aliexpress.com/e/F6E2vzr" target="_parent"><img src="//ae01.alicdn.com/kf/HTB1fWKijtfJ8KJjy0Feq6xKEXXax/-font-b-CJMCU-5351-b-font-Si5351A-Si5351-I2C-25MHZ-Controller-Clock-Generator-Breakout-Board.jpg_220x220.jpg" /><span style="display: block;">CJMCU-5351 Si5351A I2C 25MHZ Controller Clock Generator 8KHz to 160MHz</span></a>

<span data-spm-anchor-id="2114.10010108.1000023.i0.8b503d9FxYpiI">Never hunt around for another crystal again, with the Si5351A clock generator breakout ! This chip has a precision 25MHz crystal reference and internal PLL and dividers so it can generate just about any frequency, from <8KHz up to 150+ MHz.</span>

The Si5351A clock generator is an I2C controller clock generator. It uses the onboard precision clock to drive multiple PLL&#8217;s and clock dividers using I2C instructions. By setting up the PLL and dividers you can create precise and arbitrary frequencies. There are three independent outputs, and each one can have a different frequency. Outputs are 3Vpp, either through a breadboard-friendly header or, for RF work, an optional SMA connector.

We put this handy little chip onto it&#8217;s own breakout board PCB, with a 3.3V LDO regulator so it can be powered from 3-5VDC. We also put level shifting circuitry on the I2C lines so you can use this chip safely with 3V or 5V logic.

Best of all, we even have a great tutorial and library to get you started! Our code is designed for use with the Arduino microcontroller and IDE but is easily ported to your favorite platform with I2C support