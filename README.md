## Components: 
STM32U575RIT6Q 
TCAN1473ACDRQ1 
RFM96PW 
TPS259474L 


GIT Link: https://github.com/Kutty-GT/EPS_Housekeeping_Beacon_PCB


This is a PCB Task as specified below: 

Build a stack of 2 control PCBs, both have 1 MCU each, communicating via CAN protocol(see transceivers and breakout acc to necessity).  

Keep one as main PCB, responsible for housekeeping/control: Put a radiation sensor, current sensor, temperature sensor management IC like LTC2986 that can handle atleast 3 different types of thermal sensors.  

The 2nd board is required to have a Beacon Transceiver chip - you may choose whatever configuration to execute this part. Try to take some info from TTC for the antenna and design the breakout.  
