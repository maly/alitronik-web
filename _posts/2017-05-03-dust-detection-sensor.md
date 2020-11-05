---
id: 164
title: Dust Detection Sensor
date: 2017-05-03T09:19:12+01:00
author: Martin Maly
layout: post
guid: https://alitronik.com/?p=164
permalink: /dust-detection-sensor/
xyz_twap:
  - "1"
image: http://alitronik.com/wp-content/uploads/sites/18/2017/04/10pcs-LOT-Nova-PM-dust-sensor-SDS011-particle-sensor-Laser-PM2-5-sensor-with-connecting-cable.jpg_640x640.jpg
categories:
  - Tip
tags:
  - Air
  - Dust
  - Laser
  - sensor
---
<a href="http://s.click.aliexpress.com/e/qRZRfey" target="_parent"><img src="//ae01.alicdn.com/kf/HTB11VqJPFXXXXb9XFXXq6xXFXXXZ/Nova-PM-sensor-font-b-SDS011-b-font-High-precision-laser-pm2-5-air-quality-detection.jpg_220x220.jpg" /><span style="display: block;">Nova PM sensor SDS011 &#8211; High precision laser dust detection sensor module</span></a>

**Technical Parameters:**

<table border="1" cellpadding="5">
  <tr>
    <th>
      Item
    </th>
    
    <th>
      Parameter
    </th>
  </tr>
  
  <tr>
    <td>
      Measuring output
    </td>
    
    <td>
      PM2.5,PM10
    </td>
  </tr>
  
  <tr>
    <td>
      Range
    </td>
    
    <td>
      0.0-999.9 µg/m3
    </td>
  </tr>
  
  <tr>
    <td>
      Power supply voltage
    </td>
    
    <td>
      5V
    </td>
  </tr>
  
  <tr>
    <td>
      Maximum working current
    </td>
    
    <td>
      100mA
    </td>
  </tr>
  
  <tr>
    <td>
      Sleep current
    </td>
    
    <td>
      2 mA
    </td>
  </tr>
  
  <tr>
    <td>
      Operating temperature range
    </td>
    
    <td>
      -20-50℃
    </td>
  </tr>
  
  <tr>
    <td>
      Response time
    </td>
    
    <td>
      1s
    </td>
  </tr>
  
  <tr>
    <td>
      Serial data output frequency
    </td>
    
    <td>
      1 time/s
    </td>
  </tr>
  
  <tr>
    <td>
      Particle diameter resolution
    </td>
    
    <td>
      Less than 0.3µm
    </td>
  </tr>
  
  <tr>
    <td>
      Relative error
    </td>
    
    <td>
      10%
    </td>
  </tr>
  
  <tr>
    <td>
      Product size
    </td>
    
    <td>
      71x70x23mm
    </td>
  </tr>
</table>

**Interface specification:**

<table border="1" cellpadding="5">
  <tr>
    <th>
      Pin
    </th>
    
    <th>
      Name
    </th>
    
    <th>
      Explain
    </th>
  </tr>
  
  <tr>
    <td>
      1
    </td>
    
    <td>
      CTL
    </td>
    
    <td>
      Control pin, reserved
    </td>
  </tr>
  
  <tr>
    <td>
      2
    </td>
    
    <td>
      1µm
    </td>
    
    <td>
      >0.3 Micron particle concentration, PWM Output
    </td>
  </tr>
  
  <tr>
    <td>
      3
    </td>
    
    <td>
      5V
    </td>
    
    <td>
      5V power input
    </td>
  </tr>
  
  <tr>
    <td>
      4
    </td>
    
    <td>
      25µm
    </td>
    
    <td>
      >2.5 Micron particle concentration, PWM Output
    </td>
  </tr>
  
  <tr>
    <td>
      5
    </td>
    
    <td>
      GND
    </td>
    
    <td>
      GND
    </td>
  </tr>
  
  <tr>
    <td>
      6
    </td>
    
    <td>
      Rx
    </td>
    
    <td>
      Serial port receiver RX
    </td>
  </tr>
  
  <tr>
    <td>
      7
    </td>
    
    <td>
      Tx
    </td>
    
    <td>
      Serial port transmission TX
    </td>
  </tr>
</table>

**Communication protocol:**

Serial communication protocol: 9600 8N1. (Rate of 9600, data bits 8, parity none, stop bits 1)  
Serial report communication cycle: 1+0.5 seconds  
Data frame (10 bytes): message header + order+ data(6 bytes) + checksum + message trailer

<table border="1" cellspacing="1" cellpadding="1">
  <tr>
    <th>
      #
    </th>
    
    <td>
      Name
    </td>
    
    <td>
      Content
    </td>
  </tr>
  
  <tr>
    <td>
    </td>
    
    <td>
      message header
    </td>
    
    <td>
      AA
    </td>
  </tr>
  
  <tr>
    <td>
      1
    </td>
    
    <td>
      order
    </td>
    
    <td>
      C0
    </td>
  </tr>
  
  <tr>
    <td>
      2
    </td>
    
    <td>
      data 1
    </td>
    
    <td>
      PM2.5 low byte
    </td>
  </tr>
  
  <tr>
    <td>
      3
    </td>
    
    <td>
      data 2
    </td>
    
    <td>
      PM2.5 high byte
    </td>
  </tr>
  
  <tr>
    <td>
      4
    </td>
    
    <td>
      data 3
    </td>
    
    <td>
      PM10 low byte
    </td>
  </tr>
  
  <tr>
    <td>
      5
    </td>
    
    <td>
      data 4
    </td>
    
    <td>
      PM10 high byte
    </td>
  </tr>
  
  <tr>
    <td>
      6
    </td>
    
    <td>
      data 5
    </td>
    
    <td>
      0(reserved)
    </td>
  </tr>
  
  <tr>
    <td>
      7
    </td>
    
    <td>
      data 6
    </td>
    
    <td>
      0(reserved)
    </td>
  </tr>
  
  <tr>
    <td>
      8
    </td>
    
    <td>
      checksum
    </td>
    
    <td>
      checksum
    </td>
  </tr>
  
  <tr>
    <td>
      9
    </td>
    
    <td>
      message trailer
    </td>
    
    <td>
      AB
    </td>
  </tr>
</table>

Checksum: data 1 + data 2 + &#8230;+ data 6  
PM2.5 data content: PM2.5 (µg/m3) = ((PM2.5 high byte*256 ) + PM2.5 low byte)/10  
PM10 data content: PM10 (µg/m3) = ((PM10 high byte*256 ) + PM10 low byte)/10

<div>
</div>

<div>
</div>