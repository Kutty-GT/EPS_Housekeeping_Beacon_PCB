This is a PCB Task as specified below: 

Build a stack of 2 control PCBs, both have 1 MCU each, communicating via CAN protocol(see transceivers and breakout acc to necessity).

Keep one as main PCB, responsible for housekeeping/control: Put a radiation sensor, current sensor, temperature sensor management IC like LTC2986 that can handle atleast 3 different types of thermal sensors.

The 2nd board is required to have a Beacon Transceiver chip - you may choose whatever configuration to execute this part. Try to take some info from TTC for the antenna and design the breakout.

Research and implement atleast 2 different OCPC IC modules.

(Components on a board should be interfaced with the respective MCU on the same board obviously.)

__________

Folder Structure

My_Satellite_Stack/             <-- A master folder holding everything  
│
├── Housekeeping_Main/          <-- Folder for Board 1 
│   ├── Housekeeping_Main.kicad_pro
│   ├── Housekeeping_Main.kicad_sch
│   └── Housekeeping_Main.kicad_pcb
│
└── Beacon_Transceiver/         <-- Folder for Board 2 
    ├── Beacon.kicad_pro
    ├── Beacon.kicad_sch
    └── Beacon.kicad_pcb