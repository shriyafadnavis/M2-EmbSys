# Requirements

*High level Requirements*

|  ID|Description|Status|
  |---|---|---|
  | HR01 | Movement of solar panel according to the position of the sun| To be Done |
  | HR02 | Comparison of the analog values recevied on both right and left side ldr| To be Done|
  | HR03 | According to  the more light the servo motor moves in that direction| To be Done|
  
 *Low Level Requirements*
 
 |  ID|Description|Status|
  |---|---|---|
  | LR01 | LDRs used as main light sensors | To be Done |
  | LR02 | Arduino uno | To be Done|
  | LR03 | Servo motors for movement|To be Done|
  | LR04 | 100k resistors|To be Done|
 
 # Components
 Arduino uno
 
 Servo motor
 
 Light sensors
 
 LDR
 
 resistors
 
 # SWOT ANALYSIS
 
 *Strength*
 Solar tracker positions an object at an angle relative to the sun. It tracks the sun east to west,rotating on a single point,moving either in unison,panel or by section.
 
 *Weakness*
 Requires more maintenance and are slightly more expensive.
 
 *Opportunities*
 This tracker not only tracks the sun as it moves east to west,buit also follows it as it moves from north to south.
 
 #4W 1H
 What - Solar Tracker
 
 Where - Solar trackers are typically used for ground-mounted solar panels and large, free-standing solar installations like solar trees.
 
 When - Solar tracker help maximize solar production by following the sun throughout the day.
 
 Why - solar tracker, a system that positions an object at an angle relative to the Sun.
 Solar trackers generate more electricity than their stationary counterparts due to an increased direct exposure to solar rays. 
 
 How - LDRs are used as main light sensors.Two servo motors are fixed to the structure that holds the solar panel. Ldr sense the amount of light falling on them.For east-west tracking , the analog values from two top LDRs and bottom two LDRs are compared and if the top set of LDRs receive more light, the vertical servo will move in that direction.
 
 
