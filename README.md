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


---
This repository was build upon original firmware by Repetier https://github.com/repetier/Repetier-Firmware  
This repository, like Repetier, is open source licensed under the GPL V3.  
  
---

**DISCLAIMER**  

This library and Grasshopper plugin was created out of the good intension of education and promotion of technology.  
User should take their own caution and risk when using this library.  
The creator(s) and contributors of this library do not provide any garantee or waranty to the use of this library and/or digital tool derives from this library.  
  
---
**CAUTION**  
  
Working with electronic devices could be dangerous.  
Always take precaution accordingly and make sure you are well trained and informed to work on the specific system
Failure to operate your machine correctly could result in hardware damage and/or serious injuries