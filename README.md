# Stepper Motor Controller
CAN capable stepper motor control hardware based on the Trinamic TMC2100 driver, developed iteratively through breakout, test, and integrated STM based revisions.
<br>

## TMC2100 Breakout Board
Initial breakout board designed to validate pinout, basic operation, and electrical behavior of the TMC2100 stepper motor driver.
<br>

- Simple breakout for rapid bring up and probing
- Direct access to control and configuration pins
<br>

<div align="left">
<img src="TMC2100-T-TA%20Breakout%20Layout.png" alt="TMC2100 Breakout Board Layout" width="500px" style="display: block; margin-left: auto; margin-right: auto;">
</div>
<br>

## TMC2100 Test Board
Expanded test board used to evaluate real world motor driving behavior, thermal performance, and power routing under load.
<br>

- Integrated motor connectors and power input
- Designed for hands on testing and tuning
- Used to validate driver configuration and protection behavior
<br>

<div align="left">
  <img src="TMC2100-T-TA%20Test%20Board%203D.png" alt="TMC2100 Test Board 3D View" width="500px" style="display: block; margin-left: auto; margin-right: auto;">
</div>
<br>

## STM Rev 0.5 Integrated Board
Current integrated revision combining the TMC2100 driver with an onboard STM microcontroller for closed loop control and future CAN integration.
<br>

- Onboard STM microcontroller for real time control
- Designed as a stepping stone toward full CAN based motion control
- Revision 0.5 reflects an iterative development stage rather than a finalized design
<br>

<div align="left">
  <img src="TMC2100-T-TA%20STM%20Layout%20Rev0.5.png" alt="STM Rev 0.5 Board Layout" width="500px" style="display: block; margin-left: auto; margin-right: auto;">
</div>
<br>

## Project Status
This is an ongoing development effort. The hardware is being iterated alongside firmware development, testing, and system level integration. Schematics, layouts, and board revisions are expected to change as lessons are learned and requirements evolve.
<br>
