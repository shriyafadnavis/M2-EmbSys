# Table of Contents
1. Abstract
2. Requirements
3. SWOT Analysis
4. 4W's and 1H
5. Circuit Diagram
6. Test Plan
7.  Components
8.  Applications
9.  Output

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


# Requirements

High Level Requirements

|  ID|Description|Status|
  |---|---|---|
  | HR01 | Movement of solar panel according to the position of the sun| To be Done|
  | HR02 | Comparison of the analog values recevied on both right and left side ldr|To be Done|
  | HR03 | According to  the more light the servo motor moves in that direction|To be Done|
  
  
Low Level Requirements

 |  ID|Description|Status|
  |---|---|---|
  | LR01 | LDRs used as main light sensors |To be Done|
  | LR02 | Arduino uno | To be Done|
  | LR03 | Servo motors for movement|To be Done|
  | LR04 | 100k resistors|To be Done|
  
  
  # SWOT ANALYSIS
  Strength  Solar tracker positions an object at an angle relative to the sun. It tracks the sun east to west,rotating on a single point,moving either in unison,panel or by section.

Weakness Requires more maintenance and are slightly more expensive.

Opportunities This tracker not only tracks the sun as it moves east to west,buit also follows it as it moves from north to south.

# 4W 1H

4W 1H What - Solar Tracker

Where - Solar trackers are typically used for ground-mounted solar panels and large, free-standing solar installations like solar trees.

When - Solar tracker help maximize solar production by following the sun throughout the day.

Why - solar tracker, a system that positions an object at an angle relative to the Sun. Solar trackers generate more electricity than their stationary counterparts due to an increased direct exposure to solar rays.

How - LDRs are used as main light sensors.Two servo motors are fixed to the structure that holds the solar panel. Ldr sense the amount of light falling on them.For east-west tracking , the analog values from two top LDRs and bottom two LDRs are compared and if the top set of LDRs receive more light, the vertical servo will move in that direction.


# Circuit Diagram

  
