# Prusa_i3-CRAMPS
Prusa_i3 CRAMPS velocity based extraction configuration for Machinekit

3D printer configuration using Machinekits Python API for my Prusa-i3
( Originated from:  https://github.com/strahlex/MendelMax-CRAMPS )

    Uses gantry control on Z-axis
    Gantry Right --> Y stepdriver  (z-min(<) limit-switch input)
    Gantry Left  --> E2 stepdriver (z-max(>) limit-switch input)

    Bed thermistor --> Therm input 0
    E0 thermistor  --> Therm input 1

    Extruder body fan <-- FET6
    Cooling fan       <-- FET5

With individual Left/Right Z-axis offset-adjustment in machinekit-client



![](./images/Prusa-i3_dev.jpg)
