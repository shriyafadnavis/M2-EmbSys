# Table of Contents
1. Abstract
2. Requirements
3. SWOT Analysis
4. 4W's and 1H
5. Block Diagram
6. Test Plan
7.  Components
8.  Applications

# Abstract
Solar Tracker using Arduino uno

Solar tracker, a system that positions an object at an angle relative to the Sun. The most-common applications for solar trackers are positioning photovoltaic (PV) panels (solar panels) so that they remain perpendicular to the Sun's rays and positioning space telescopes so that they can determine the Sun's direction.

In modern solar tracking systems, the solar panels are fixed on a structure that moves according to the position of the sun.

In this project the focus is on the implementation of solar tracker using ldr sensors, arduino uno and servo motor.

LDRs are used as the main light sensors. Two servo motors are fixed to the structure that holds the solar panel. The program for Arduino is uploaded to the microcontroller.

LDRs sense the amount of sunlight falling on them. Four LDRs are divided into top, bottom, left and right.

For east – west tracking, the analog values from two top LDRs and two bottom LDRs are compared and if the top set of LDRs receive more light, the vertical servo will move in that direction. If the bottom LDRs receive more light, the servo moves in that direction.

For angular deflection of the solar panel, the analog values from two left LDRs and two right LDRs are compared. If the left set of LDRs receive more light than the right set, the horizontal servo will move in that direction.

If the right set of LDRs receive more light, the servo moves in that direction.
