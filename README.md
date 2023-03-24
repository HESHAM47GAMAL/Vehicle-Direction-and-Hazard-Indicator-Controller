# Vehicle-Direction-and-Hazard-Indicator-Controller 🚗
- [Description](#Description)
- [Schematic](#Schematic)
  - [Main Component](#Main-Component)
- [System Architecture](#System-Architecture)
  - [Finite State Machine](#Finite-State-Machine)
- [IDE](#IDE)
- [Demo](#Demo)
  - [Waiting](#Waiting)
  - [Right Sign](#Right-Sign)
  - [Left Sign](#Left-Sign)

  
  
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
  <img src="https://github.com/HESHAM47GAMAL/Vehicle-Direction-and-Hazard-Indicator-Controller/blob/main/pic/system_Architecture.png">
</p>

  ### Finite State Machine
  <p align="center">
  <img src="https://github.com/HESHAM47GAMAL/Vehicle-Direction-and-Hazard-Indicator-Controller/blob/main/pic/FSM.png">
</p>

## IDE
 <p>⚡IDE are Eclipse (Atmel studio to upload code to MCU) & Proteus</p>
 
 
##Demo 

### Waiting 
<p> ⚡Waiting indicator make Right and Left Led high for 500ms and low for 500ms and during 500ms High led on with specific intensity that was setten  in fast PWM </p>
<p> ⚡ Waiting work If engine power on/off</p>
<p align="center">
  <img src="https://github.com/HESHAM47GAMAL/Vehicle-Direction-and-Hazard-Indicator-Controller/blob/main/GIF/press%20waiting%20button%20during%20Engine%20is%20off.gif">
  </p>

  
  
  
