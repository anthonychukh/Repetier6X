# Repetier-6-axis

Repeiter 6 axis is a WIP project to bring 6-axis + E capability to Repetier.
Repeiter 6 axis is base on version 1.0.3.
To see modification, search for "6axis" comments for modified code.
This project was made possible by the generous support of SPACE10 through a research resident program in summer 2019.


Note:
 * Set NUM_AXES in Configuration.h from 3-6
 * A,B,C stepper pin assignment will override E0, E1, E2. Adjust A,B,C,E pin assignment in Configuration.h
 * To accommodate extra function, DELTASEGMENTS_PER_PRINTLINE is reduced to 10(original 24). This might cause slight reduction to movement fidelity.



Hardware:

The hardware used to develop this firmware
 * Anycubic Linear Plus Delta
 * Azteeg Pro X3. Support up to 8 stepper motor
 * 6 axis attachment with Spherical Parallel Mechanism
 * Remote drive cable from Zesty Technology


-------------------DISCLAIMER------------------------
This is a WIP! Always do dry run before running a task and take extra caution.
Sporadic turning direction happens on ABC axes.
User should take their own caution and risk when using this library
.
The creator(s) of this library do not provide any garantee and waranty to use of this library and digital tool derives from this library.

--------------------CAUTION---------------------------

Working with electronic devices could be dangerous.
Always take precaution when working on electronic devices.
Make sure you are well trained and informed to work on the specific system
.
Failure to appropriately operate your machine could lead to hardware damage and/or serious injuries.