---
layout: project
type: project
image: images/weatherbox_bottom_view.png
title: Weatherbox
permalink: projects/weatherbox
date: 2017
labels:
  - C++
  - Xbee
  - Google Sketchup
summary: Designed and developed a low-cost, accurate, and reliable environmental sensor module.
---
<div class="ui small rounded images">
  <img class="ui image" src="../images/scel_xbee.jpg">
  <img class="ui image" src="../images/weatherbox_width_view.png">
  <img class="ui image" src="../images/team_snapdragon_board.png">
   <img class="ui image" src="../images/software_diagram.png">
</div>

<hr>


The objective for this project was to design a self-sustainable sensor node, otherwise known as a weatherbox, which collects weather and solar irradiance data which then gets sent over to a database for analysis and storage. This system would utilize two different methods of supplying power to the ATMEGA microcontroller, XBee wireless transceiver, and various on-board sensors. During the daytime, a solar panel is used to supply power for the weatherbox and to charge the system’s battery pack. When the sun sets and there isn’t enough power being supplied from the solar panel, the system will switch power sources to the battery which is able to keep the system powered until the solar panel becomes the primary power source during periods of daylight. This constant switching of power supplies enables our system to be truly self-sustainable. The sensor node has a plethora of sensors to collect barometric, humidity, solar irradiance, and temperature data and is programmed to poll the sensors at a user-specified period. The data is then consolidated into the appropriate packet format and is sent over to the lab database via an XBee wireless transceiver.

For this project, I was in charge of prototyping the weather box housing. With our custom PCB design which allowed us to replace the breakout board and Arduino, we were able to design the weather box to be compact with the following dimensions of 7” x 4” x 5”. There are two main components to our weather box which is the mount and housing itself. 

Our box was designed to be opened from the bottom to make it weathertight. The bottom of the weather box can be open or closed by screwing/unscrewing four 4-40 screws that connects the weather box housing to the mount. The mount was designed to be fastened to a clamp which is then placed to the top of Holmes Hall roof.  

Inside the weather box there are four short pillars and four long pillars hanging from the top of the weather box, three large holes, and several small holes. The four short pillars will be used to mount our PCB to the weather box with 4-40 screws. The long pillars will be used to have a foundation for the battery to lie on. There are three large holes to accommodate the power input from the solar panel, the irradiance sensor (SP-215), and the Xbee. A flexible grommet will be used with the holes to help minimize any water from going inside of the weather box. The small holes are used to help with ventilation in the weather box.

<hr>



