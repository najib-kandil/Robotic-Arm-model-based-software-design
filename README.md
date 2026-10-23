# Robotic-Arm-model-based-software-design

A Stateflow chart selects which joint to control. Joystick readings (0-1023) are scaled linearly to 0-180° and sent to that joint’s servo, and two buttons switch between joints.

steps:
1- connect the components using SimulIDE (If you are using 5V battery connect it to Vin)

2- use XLoader to upload the emulater.hex file

components:

Arduino Uno

Robotic arm with servo motors (6 servos in the SimulIDE circuit)

2 analog joystick modules (each gives X/Y analog axes plus a push button)

Breadboard

Jumper wires

USB cable (for power and upload)

5V battery (for power supply)

