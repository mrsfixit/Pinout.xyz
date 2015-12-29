<!--
---
name: Display-o-Tron 3000
description: A 3-line character LCD with an RGB backlight and joystick
pincount: 26
pin:
  '3':
    mode: i2c
  '5':
    mode: i2c
  '7':
    name: Joystick Button
    mode: input
    active: low
  '11':
    name: Joystick Left
    mode: input
    active: low
  '13':
    name: Joystick Up
    mode: input
    active: low
  '15':
    name: Joystick Right
    mode: input
    active: low
  '19':
    mode: spi
  '21':
    name: Joystick Down
    mode: input
    active: low
  '22':
    name: LCD CMD/DATA
    mode: output
    active: high
  '23':
    mode: spi
-->
#Display-o-Tron 3000

You can use the one-line product installer to get Display-o-Tron 3000 set up and ready to go, just:

```bash
curl get.pimoroni.com/dot3k | bash
```

And follow the instructions!