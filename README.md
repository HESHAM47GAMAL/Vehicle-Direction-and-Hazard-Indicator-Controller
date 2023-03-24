# Vehicle-Direction-and-Hazard-Indicator-Controller 
- [Description](#Description)
- [Schematic](#Schematic)
  - [Main Component](#Main-Component)
- [System Architecture](#System-Architecture)
- [IDE](#IDE)
- [Demo](#Demo)
  - [Start](#Start)
  - [Pause](#Pause)
  - [Resume](#Resume)
  - [Reset](#Reset)
  
  
  ## Description
  <p>⚡Here Simulate Vehicle Direction sign as when driver want turn right press on Right indicator and can give left indicator and can give wait sign </p>
  <p>⚡This System work in AVR atmega32 and use FreeRTOS and Apply Finite State machine and Periodic Polling </p>
  <p>⚡Polling has High priority  as every specofoc time check pressed button and store in state and then state machine called and handle state and control led intensity using PWM </p>
  
  ## Schematic
  <p align="center">
  <img src="https://github.com/HESHAM47GAMAL/Vehicle-Direction-and-Hazard-Indicator-Controller/blob/main/pic/schema.png">
</p>
  ### Main Component
  - Atmega 32
  - led
  - switch
  - SW-ROT-3
  ## System Architecture
  <p align="center">
  <img src="<p align="center">
  <img src="https://github.com/HESHAM47GAMAL/Vehicle-Direction-and-Hazard-Indicator-Controller/blob/main/pic/schema.png">
</p>">
</p>
  
