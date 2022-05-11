# Requirements

# Introduction
Wiper Control System is basic need in the vehicles. To develop a good wiper system some basic requirements should be fulfilled, so that one can develop a trust worthy,
so that one can develop a trust worthy wiper control system. Because wiper protects the vehicle to meet an accident. Wiper helps the driver to easily view the traffic
and road. Wiper wipes out all the dust, dew, fog, and water setteled on the wind screen  as well as rear shield.

## 4Ws and 1H

## Who

    The peeson/driver who drives any vehicle can use it to avoid accidents.

## What

    Wiper Control System is a safety system installed in all the vehicles to provide a clear vision to the driver by the wind screen. 

## When

    Whenever there is rain or dust particles setteled on the wind screen driver may use this system to clean the wind screen to get
    a clear view of the traffic.

## Where

    Where there is heavy or light rain falls or dust or dew in atmosphere.

## How

    This system can run by the enigine of the vehicle directly or simply it can get power from the battery installed in vehiles.
    
# Detail requirements
##  High level Requirements

| ID    | Name | Description                             | Status              | 
|-------|---|-----------------------------------------|---------------------|
| HLR01 | Push Button   |  To mimic the key of vehicle to start                      |Implemented          |
| HLR02 |LEDs | In the absence of wiper blade we use LEDs                             |Implemented          |
| HLR03 |Timer | To control the speed/frequency of wiper blade | Implimented |
| HLR04 |Arm Cortex -M4 CPU | To mimic the wiper motor we use Arm Cortex -M4 CPU to run wiper blade/LEDs | Implimented | 

##  Low level Requirements


| ID    | Description                             | Status              | 
|-------|-----------------------------------------|---------------------|
| LLR01 |Press and hold the push button for 2 seconds to start the system of vehicle or to set on ACC mode   |Implemented          |
| LLR02  |Press the push button to start the wiper system|Implemented          |
| LLR03 | Press it one more time to to increase the frequency of wiper | Implemented |
| LLR04 | Press it one more time to further increase the frequency | Implemented |
| LLR05 | Press and hold the push button for again 2 seconds to turn-off the wiper system | Implemented|
| LLR06 | Again press and hold it for 2 seconds to turn-off the vehicle system| Implimented|
