# Universal Water Source Heat Pump Controller (WSHP)

This WSHP controller is an open-source project intended for facility engineers and HVAC technicians.


This repository contains:


    1) .INO file that can be uploaded to the controller with the popular Arduino IDE

    2) Wiring Diagram for a typical field application

    3) Gerber Files ready for PCB printing

    4) Bill of Materials


Some Features of include:

    1) Error Codes via flashing LED for specific faults (LPS,HPS,FRZ,COND - see bottom right corner of wiring diagram for codes).

    2) DIP switch selections for:
        -Reversing Valve Energizes in HEAT or Reversing Valve Energizes in COOL
        -Enable/Disable Freeze Protection
        -Enable/Disable Condensate Protection
        -Condensate Sensor (water sense probe) or Condensate Switch (dry contact)
        -Enable/Disable Isolation Valve Relay

    3) Small PCB footprint

    4) Plug-type Connections (no screwdriver required to replace same board)
