HomeAutomation
==============
### License: GPLv3
### Description:

Java lib for Hue.

It will allow you to control your Hue light bulbs from everywhere. 

Currently for programmers only (you have to compile it yourself), but I will release a consumer friendly version soon (compiled, ready for use)

### This lib will allow you to:
- Register to the Hue hub
- Individually control every bulb
 - Dim bulb
 - Change color [Hue, Sat]
- Light animations:
 - Rainbow animation
 - Random Light animation
- Ability to register more than one hub (so if you bought 2 starters packs, it will allow you to controll all your bulbs)

### In the near future: (short term stuff)
- Web interface / Mobile interface
- Scene: (allows you to configure every bulb and save / restore it)
 - Save / Restore Scenes
 - Can consist of an animation / static color / put light off
- Schedule: 
 - Enable a Scene on a given time (for example as wake up light)
- Events: 
 - If your phone is entering WiFi, enable Scene(s)
 - If your phone is no longer connected to the WiFi, enable Scene(s)
- Auto restore light:
 - When you switch your Hue bulb on, it always starts in a white state. When enabled, this will detect the bulb a.s.a.p. and switch it to the color of the current selected scenario

### And eventually: (long term stuff)
- Change lights on sound (disco mode)
- Change lights on tv (ambilight mode)

Requires referenced libs:
- gson 2.2.2
- apache http client: 4.2.3
